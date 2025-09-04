# 📝 Simple Quiz Application

A lightweight quiz application built with **Java and Spring Boot**.  
It allows users to attempt quizzes, submit answers, and view their scores.  
The application follows a layered architecture (Controller → Service → Repository) and uses a relational database for storing quiz data.

---

## 🚀 Features

- 📚 **Quiz Service**: Create, update, and delete quizzes  
- ❓ **Question Service**: Store and manage questions with multiple choices  
- 👤 **User Participation**: Attempt quizzes and submit answers  
- 📊 **Score Evaluation**: Automatic result calculation and feedback  
- 🗄️ **Database Integration**: Persistent storage using MySQL  

---

## 🏗️ Tech Stack

- **Backend**: Java, Spring Boot  
- **Database**: MySQL  
- **Security**: Spring Security (optional)  
- **Build Tool**: Maven/Gradle  

---

## 📂 Project Structure

quiz-application/

│── src/main/java/com/example/quiz/ 

│ ├── controller/ # REST APIs for quiz & question handling

│ ├── service/ # Business logic for quiz operations

│ ├── repository/ # JPA repositories for persistence

│ ├── model/ # Entity classes (Quiz, Question, User, Result)

│ └── dto/ # Data Transfer Objects
│
│── src/main/resources/
│ ├── application.properties # DB config

│ └── data.sql # Sample data (optional)

