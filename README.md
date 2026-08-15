# 🌍 GlobaLearn — World Culture & Language Learning Platform

> **An interactive full-stack platform for exploring world cultures, learning languages, and making global education engaging through maps, quizzes, gamification, and role-based dashboards.**

---

## 📌 Overview

**GlobaLearn** is a full-stack web application designed to make **world culture and language learning interactive, personalized, and engaging**.

Users can explore countries, discover cultural information, learn useful phrases, participate in quizzes and games, track their learning progress, and interact with a personalized learning environment.

The platform provides two major roles:

* 🧑‍🎓 **Learner** — focuses on personal learning, exploration, gamification, quizzes, and progress.
* 👩‍🏫 **Teacher** — manages classes, monitors students, creates quizzes, uploads learning content, views analytics, and communicates with learners.

The backend is built using the **MERN stack** with **JWT-based authentication and role-based authorization**.

---

# ✨ Key Features

## 🧑‍🎓 Student Dashboard

### 📊 Learning Progress Tracker

Students can track their learning progress through:

* XP points
* Levels
* Badges
* Countries explored
* Overall learning progress

The backend securely stores and updates student progress.

### 🗺️ Personalized Map Journey

Students can explore countries through an interactive world map.

The system tracks:

* Visited countries
* Explored countries
* Unlocked countries based on progress

This creates a personalized world-learning journey.

### 🔥 Streaks & Badges

Gamification keeps students motivated through:

* Daily login streaks
* Achievement badges
* XP rewards
* Progress-based achievements

Example achievements:

* 🌍 Globe Trotter
* 🧠 Culture Guru
* 🏆 Quiz Master

### 📝 Student Notebook

Students can save useful phrases and notes from their learning experience.

The notebook works as a personal:

> **Language Phrasebook + Cultural Notes**

Students can:

* Save notes
* View saved notes
* Delete notes

### 🎮 Quiz & Game Zone

Students can participate in quizzes and track their performance.

The system supports:

* Quiz submissions
* Score tracking
* Quiz history
* Best scores
* Attempts
* XP rewards
* Leaderboards

---

# 👩‍🏫 Teacher Dashboard

### 🏫 Class Management

Teachers can manage their classes.

Features:

* Create classes
* Generate unique class codes
* View their classes
* Allow students to join using class codes
* Delete classes

### 📊 Student Progress View

Teachers can monitor students belonging to their classes.

The system provides:

* XP
* Levels
* Countries explored
* Badges
* Student performance

This data can be used to build:

* Leaderboards
* Student performance tables
* Progress cards

### 🧠 Custom Quiz Builder

Teachers can create their own country-specific quizzes.

Quiz functionality supports:

* Quiz title
* Country
* Difficulty level
* Multiple-choice questions
* Correct answers
* Class-specific quizzes

Teachers can:

* Create quizzes
* View their quizzes
* View class quizzes
* View individual quiz details
* Delete quizzes

### 📚 Teacher Content Upload

Teachers can provide additional learning material for students.

Content can include:

* Cultural facts
* Challenges
* Recommended resources
* Teacher notes

This content can appear on the student dashboard as:

> **Teacher's Note of the Week**

### 📈 Analytics Dashboard

Teachers can view class engagement and learning statistics.

Analytics include:

* Average XP per student
* Most explored countries
* Quiz completion statistics

These insights help teachers understand student participation and performance.

### 💬 Teacher–Student Chat & Feedback

Teachers and students can communicate through a one-to-one messaging system.

Features include:

* Send messages
* View chat history
* Teacher feedback
* Student questions
* Read/unread message status
* Delete messages

---

# 🔐 Authentication & Authorization

GlobaLearn uses **JWT-based authentication**.

Users can register and log in according to their role:

* `learner`
* `teacher`

After successful login, the backend generates a JWT containing the user's identity and role.

Role-based middleware protects dashboard functionality and prevents unauthorized access.

For example:

* Learners access learner functionality.
* Teachers access teacher functionality.

Passwords are securely hashed using **bcrypt** before being stored in the database.

---

# 🛠️ Tech Stack

## Frontend

* React
* Next.js / React-based UI
* Tailwind CSS
* Leaflet.js
* Interactive maps
* Responsive UI

## Backend

* Node.js
* Express.js
* MongoDB
* Mongoose
* REST APIs

## Authentication

* JWT
* bcrypt
* Role-based authorization

## Development & Testing

* VS Code
* Git & GitHub
* Postman
* Nodemon

## Deployment

* Vercel — Frontend
* MongoDB / MongoDB Atlas — Database
* Node.js / Express — Backend

---

# 🗄️ Database

MongoDB is used as the primary database.

The application manages data related to:

* Users
* Student progress
* Badges
* Notebook notes
* Quiz attempts
* Pronunciation practice
* Classes
* Teacher-created quizzes
* Teacher content
* Teacher–student conversations

Mongoose is used for schema definition, validation, and interaction with MongoDB.

---

# 🎯 Project Objectives

GlobaLearn aims to:

* Make cultural education interactive.
* Encourage language learning through practical phrases.
* Introduce gamification into cultural education.
* Provide personalized learning journeys.
* Help teachers monitor student engagement.
* Allow teachers to create customized educational content.
* Connect students and teachers through feedback and communication.

---

# 🌟 What Makes GlobaLearn Different?

### For Learners 🌍

> **Explore → Learn → Play → Earn XP → Unlock → Repeat**

Students get a personalized and gamified learning experience instead of simply reading static cultural information.

### For Teachers 📊

> **Create → Assign → Monitor → Analyze → Guide**

Teachers get tools to manage classes, create educational content, monitor students, and understand learning engagement.

This creates a complete **teacher + learner educational ecosystem**.

---

# 🧪 Testing

The backend has been tested using **Postman**.

Testing includes:

* User registration
* User login
* Authentication
* Role-based authorization
* Student progress
* Badges
* Notebook
* Quiz functionality
* Class management
* Student progress monitoring
* Teacher quiz management
* Teacher content
* Analytics
* Teacher–student communication

Protected functionality uses JWT authentication.

---

# 🔮 Future Enhancements

Possible future improvements include:

* 🤖 AI-powered country-specific native chat
* 🔊 Advanced pronunciation evaluation
* 🎮 Multiplayer quizzes
* 📬 Weekly culture newsletter
* 👩‍🏫 Classroom mode
* 📊 Advanced teacher analytics
* 🌐 More countries and cultural datasets
* 🏆 Global student leaderboard
* 📱 Progressive Web App support

---



# 🌍 GlobaLearn

> **Learn Languages. Explore Cultures. Connect with the World. 🌎**
