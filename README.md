# 🧠 SmartTaskTracker

SmartTaskTracker is an intelligent, AI-powered task management tool that turns natural language into structured, actionable tasks. Built with Node.js, Express, React, and OpenAI’s GPT-4o, this app helps individuals and teams stay organized effortlessly.

---

## 🚀 Features

- 📝 **Natural Language Input** – Type tasks like _"Finish report by tomorrow 5pm for Sarah"_ and let AI do the parsing.
- 📅 **Auto-Extracts Details** – Automatically detects task name, assignee, due date, and priority.
- 🔁 **Real-time Updates** – Easily add, update, or delete tasks in a responsive interface.
- 🎯 **Prioritization Support** – Supports P1 (Critical) to P4 (Low) task levels.
- 🌐 **Fullstack App** – React frontend + Express backend with TypeScript and OpenAI integration.

---

## 🔧 Setup Instructions

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/SmartTaskTracker.git
cd SmartTaskTracker
```

### 2. Install Dependencies
npm install
cd client && npm install
3. Add Your OpenAI API Key
Create a .env file in the root:
```bash
OPENAI_API_KEY=sk-...
```
💡 Get your API key from: https://platform.openai.com/account/api-keys

### 🛠️ Development
To start the backend and frontend in development mode:
# In root
```bash
npm run dev
```
# In separate terminal, run the frontend
```bash
cd client
npm run dev
```
The backend runs on: http://localhost:5000
The frontend runs on: http://localhost:5173

### 🧠 Example Inputs
Try typing:

Finish landing page for Aman by 11pm 20th June

Call Rajeev tomorrow at 5pm

Review P1 documents Sarah by Friday

AI will respond with:
{
  "taskName": "Review documents",
  "assignee": "Sarah",
  "dueDate": "Friday",
  "priority": "P1"
  
}

## Output ScreenShots

![Screenshot 2025-05-30 152026](https://github.com/user-attachments/assets/ff408ebc-a370-46c6-bc4c-ea351dde1964)
![Screenshot 2025-05-30 152109](https://github.com/user-attachments/assets/199a16fb-9f29-48af-b284-83041ccdb701)



