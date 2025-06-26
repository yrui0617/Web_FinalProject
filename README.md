# GoLanguage

**GoLanguage** — a web application designed to help users learn and practice language skills interactively.

## Project Features
This website supports the following features:

- **User Authentication**
  - Register and log in with email and password
  - "Remember Me" to stores the user's email and password in local storage and auto-fill the user details at login page next time. 

- **Language Learning**
  - Malay and Chinese available can be selected to learn a new language
  - Real-time progress tracking and feedback (prompt user to select correct answer and navigate to next question or finish until it chose the correct answer.)
  - **Exercise Types**
    - Multiple Choose Question
    - Fill The Blank
    - Reading Exercise
    - Listeninf Exercise

- **Achievements**
  - Track completed exercises
  - Store completion time of achievement using server timestamp
  - Display each achievement that completed by specific user
 
- **User Profile**
  - Show all the user information
  - Allow user to edit their information
  - Upload/Remove the profile picture
  

---

## 🔧 Setup Instructions

###  Change MySQL Database Configuration at application.properties (
  - spring.datasource.url=jdbc:mysql://localhost:3307/golanguage_db?useSSL=false&serverTimezone=Asia/Kuala_Lumpur  # Change to your MySQL port like 3306
  - spring.datasource.username=root       # Change to your MySQL username
  - spring.datasource.password=yourpassword   # Change to your MySQL password
