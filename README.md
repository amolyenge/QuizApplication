📚 Quiz App – Spring Boot Backend

A full-featured backend for an online quiz platform, built with Java 17, Spring Boot, JWT-based authentication, Spring Security, and MySQL. This backend handles user registration, login, quiz management, evaluation, result tracking, and much more.

🚀 Tech Stack
Java 17

Spring Boot 3.4.1

Spring Security + JWT + OAuth2

Spring Data JPA (Hibernate)

MySQL (Relational Database)

Lombok (Boilerplate reduction)

Maven (Build Tool)

JJWT (JWT implementation)


📂 Project Structure

com.quizApp.amol
├── Controller         # REST controllers
├── Model              # Entity classes (User, Quiz, Question, etc.)
├── Repository         # JPA Repositories
├── Service            # Business logic layer
├── Config             # Security config, JWT helpers, filters

🧪 Features :->

✅ User Registration & Login with role-based access control

✅ JWT Authentication for secure session handling

✅ Quiz Management (CRUD operations for quizzes)

✅ Category Management for organizing quizzes

✅ Question Management for quiz content

✅ Quiz Attempt Evaluation with auto-scoring logic

✅ Result Tracking per user and quiz

✅ Admin & User views

✅ Angular frontend-ready (CORS enabled for http://localhost:4200)

🔐 Authentication
Login via /auth/login returns a JWT token

Token must be included in headers for all secured endpoints:

makefile
Authorization: Bearer <your-token>
Current User Info via /auth/currentUser


🛡️ Security & Roles:->

ROLE_NORMAL: default for newly registered users

ROLE_ADMIN: can be manually assigned for admin privileges

Passwords are hashed using BCrypt


👨‍💻 Author
Amol Yenge
📧 amolyenge.sde2025@gmail.com
