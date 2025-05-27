# ONLINEQUIZ
##🎯 Project Title: AI-Powered Online Quiz Platform

##🧠 Overview

This is a smart **AI-driven online quiz application** that allows users to generate, attempt, and analyze multiple-choice quizzes dynamically. The system uses **Google Gemini** (or other LLMs) through a FastAPI microservice to generate MCQs based on user-provided topics. It integrates a **Spring Boot** backend and an **Angular** frontend to deliver a smooth, interactive experience.

---

### 🚀 Key Features

* **Dynamic Quiz Generation:** Users input a topic, and AI generates multiple-choice questions.
* **Real-Time Scoring & Feedback:** Users receive instant score updates after submission.
* **Performance Analysis:** Visual dashboard with performance metrics, accuracy, and AI-based feedback.
* **User Authentication & Profile:** Secure login and personalized dashboard.
* **Theme Settings:** Users can switch between dark/light themes (stored in local storage).
* **Reminders/Calendar Integration:** Set quiz reminders with optional email alerts.

---

### ⚙️ Tech Stack

| Layer         | Technology                      |
| ------------- | ------------------------------- |
| Frontend      | Angular, HTML/CSS, Bootstrap    |
| Backend (API) | Spring Boot (Java)              |
| Microservice  | FastAPI (Python, Gemini API)    |
| AI Engine     | Gemini (Google AI)              |
| Database      | MySQL   |
| Deployment    | GitHub Pages  |

---

### 🤖 AI Integration

The core intelligence of the app is powered by **Google Gemini AI**. When a user submits a topic (e.g., "PYTHON" or "World War II"), the backend sends a prompt to Gemini, which returns a structured list of MCQs with options and correct answers. This not only saves content creation time but also allows limitless quiz topics.

---

### 📊 Performance Analytics

After submitting a quiz:

* Scores are calculated immediately.
* AI compares your score against historical attempts (if available).
* Displays charts (accuracy, question difficulty, topic coverage).
* Personalized feedback such as:

  * "You're strong in basics but need improvement in advanced questions."
  * "Try revising definitions and concept-based MCQs."

---

### 🛠️ How It Works

1. User logs in and enters a topic.
2. Angular frontend sends request → Spring Boot backend → FastAPI microservice.
3. FastAPI generates questions using Gemini and sends them back.
4. User takes the quiz and submits answers.
5. Scores and AI analysis shown on the dashboard.

---

### 📁 Repository Structure

```
/frontend         → Angular App
/backend          → Spring Boot App
/ai-service       → FastAPI + Gemini AI integration
```

---

### 📈 Future Improvements

* Adaptive learning paths based on user performance
* Gamification (badges, XP points)
* Question review and feedback submission
* Admin panel to monitor usage and manage quizzes

---

### 💡 Use Cases

* Students preparing for competitive exams
* Teachers generating rapid assessments
* Corporate training platforms with AI-generated evaluations

---

