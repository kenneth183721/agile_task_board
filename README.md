# Agile Task Board (Backend API)
A scalable NoSQL backend for dynamic task management

## 🚀 Overview
This project demonstrates a backend for an Agile Kanban system. Unlike rigid SQL structures, 
this implementation leverages MongoDB to handle the fluid nature of task metadata—such as dynamic tags and 
nested sub-tasks—essential for modern agile environments.

## 🛠 Tech Stack
- Runtime: Node.js
- Framework: Express.js
- Database: MongoDB Atlas (Cloud NoSQL)
- ODM: Mongoose
- Tools: Postman (API Testing), MongoDB Compass (Data Visualization), Dotenv (Security)

## 📊 Data Modeling (NoSQL)
In this project, I transitioned from relational modeling to Document-based modeling. The task schema is designed for performance and flexibility:

Dynamic Schema: Utilized MongoDB's schema-less nature to store arrays of tags and metadata without complex JOINs.

Indexing: Implemented indexes on frequently queried fields to ensure sub-second response times as the dataset scales.

## 🔌 API Documentation (RESTful)
The backend exposes a clean REST API for full CRUD operations:

<img width="1110" height="270" alt="table_2" src="https://github.com/user-attachments/assets/1759dd08-2776-4757-8a47-e52e441b306c" />

## 📸 Development Proof (API Testing)

Since this is a backend-focused repository, the functionality is verified via Postman and MongoDB Atlas:

<img width="700" height="780" alt="postman 1" src="https://github.com/user-attachments/assets/c810d0a6-0465-4049-a1c4-dbef336fa49f" />
