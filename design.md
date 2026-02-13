# Design Document

## Project Title
AI Practitioner Study Assistant

---

## 1. System Overview

The AI Practitioner Study Assistant is a web-based learning platform designed to help students prepare for the AWS Certified AI Practitioner exam.

It provides:

- Topic notes
- Practice quizzes
- AI explanations

---

## 2. Architecture Design

### High-Level Architecture

User → Web App → Quiz Engine → AI Explanation Module → Database

---

## 3. Module Design

### 3.1 User Module
- Handles login and registration
- Stores user profile data

### 3.2 Learning Module
- Displays AWS AI topics
- Provides structured notes

### 3.3 Quiz Module
- Generates MCQs dynamically
- Tracks answers and scores

### 3.4 AI Assistant Module
- Explains correct answers
- Provides concept clarity

### 3.5 Database Module
Stores:
- User data
- Quiz history
- Topic progress

---

## 4. Technology Stack

| Component | Technology |
|----------|------------|
| Frontend | HTML, CSS, JavaScript |
| Backend  | Node.js / Python Flask |
| Database | MongoDB / MySQL |
| Hosting  | AWS / GitHub Pages |

---

## 5. Data Flow Design

1. User selects a topic
2. System loads study content
3. User starts quiz
4. System evaluates answers
5. AI module generates explanations
6. Score stored in database

---

## 6. Future Enhancements

- Add full-length mock exams
- Integrate AWS Bedrock for GenAI tutor
- Add certification progress tracker

---

## 7. Conclusion

This design document provides the system structure and component-level architecture.
