# 🧞 Gift Genie AI (Beginner Project)

A beginner-friendly AI web application that generates simple gift suggestions based on user input.
This project is built for learning how frontend, backend, and AI APIs work together.

---

## 📌 About This Project

This is an **educational project** created to understand:

* How to connect a frontend with a backend
* How to use an AI API in a real application
* How to handle user input and display results
* Basic full-stack development using JavaScript

---

## 🌟 Features

* Accepts user input (interests, budget, occasion)
* Sends request to backend API
* Uses AI to generate gift suggestions
* Displays results in a clean format
* Simple and interactive UI

---

## 🛠 Tech Stack

### Frontend

* HTML
* CSS
* JavaScript
* Vite

### Backend

* Node.js
* Express.js

### Libraries

* marked (Markdown rendering)
* DOMPurify (safe HTML rendering)

### AI

* OpenAI-compatible API

---

##  How It Works

1. User enters a description
2. Frontend sends request to backend (`/api/gift`)
3. Backend sends request to AI model
4. AI returns gift suggestions
5. Frontend displays the output

---

##  Installation (MAIN PART)

```bash
git clone https://github.com/MunagalaSaiHanish/Gift-Generator-ai.git
cd Gift-Generator-ai
npm install    
npm run start
```

---

## Environment Variables(Grab the details from your "OPENAI" API)

Create a `.env` file:

```
AI_KEY=your_api_key
AI_URL=your_api_url
AI_MODEL=your_model
```


## 👨‍💻 Author

MUNAGALA SAI HANISH
(This project was built as part of learning from SCRIMBA.)
