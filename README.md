# 🏏 CricketPulse

**CricketPulse is an AI-powered cricket analytics platform that delivers intelligent match predictions, real-time insights, and an interactive user experience.**

---

## 🚀 Overview

CricketPulse is a full-stack web application designed to enhance the cricket experience using **data-driven insights and AI-powered predictions**. It provides live match data, player statistics, and predictive analytics to help users make informed decisions.

---

## ✨ Features

* 📊 **Live Match Insights** – Real-time match data and updates
* 🤖 **AI Match Prediction** – Predict match outcomes using intelligent algorithms
* 🧠 **AI Chatbot Assistant** – Ask cricket-related queries
* 🔐 **Authentication System** – Secure login with Google & GitHub
* 🏆 **Leaderboard System** – Track user predictions and rankings
* 📈 **Player & Team Stats** – Detailed analytics and performance insights
* ⚡ **Server Wake Detection UI** – Handles backend sleep/wake states smoothly

---

## 🛠️ Tech Stack

### 🌐 Frontend

* React.js (Vite)
* CSS / Custom Styling
* Axios

### ⚙️ Backend

* Django
* Django REST Framework
* PostgreSQL (Neon DB)

### ☁️ Deployment

* Frontend: Vercel / Netlify
* Backend: Render
* Database: Neon PostgreSQL

---

## 📁 Project Structure

```
cricketpulse/
│── frontend/        # React frontend
│   ├── src/
│   ├── public/
│   ├── package.json
│
│── backend/         # Django backend
│   ├── core/
│   ├── cricketpulse/
│   ├── manage.py
│   ├── requirements.txt
│
│── .gitignore
│── README.md
```

---

## ⚙️ Installation & Setup

### 🔽 Clone Repository

```bash
git clone https://github.com/vruthvik-chinthoju/cricketpulse.git
cd cricketpulse
```

---

### 🧩 Backend Setup

```bash
cd backend
pip install -r requirements.txt
python manage.py migrate
python manage.py runserver
```

Backend runs at:

```
http://127.0.0.1:8000/
```

---

### 🎨 Frontend Setup

```bash
cd frontend
npm install
npm run dev
```

Frontend runs at:

```
http://localhost:5173/
```

---

## 🔗 API Integration

Make sure your frontend API base URL points to backend:

```js
http://127.0.0.1:8000/api/
```

For production:

```js
https://your-backend-url.onrender.com/api/
```

---

## 🤖 AI Prediction System

The AI engine analyzes:

* Team performance
* Player statistics
* Historical match data

It then predicts:

* Match winner
* Probability insights

---

## 📸 Screenshots

*(Add screenshots here later for better presentation)*

---

## 🌐 Deployment Guide

### Backend (Render)

* Connect GitHub repo
* Add environment variables
* Set start command:

```bash
gunicorn cricketpulse.wsgi:application
```

---

### Frontend (Vercel)

* Import GitHub repo
* Set build command:

```bash
npm run build
```

---

## ⚠️ Important Notes

* Do NOT upload `node_modules`
* Use `.env` for secrets
* Backend may sleep on free hosting (handled in UI)

---

## 🤝 Contributing

Contributions are welcome!
Feel free to fork the repo and submit a pull request.

---

## 📌 Future Improvements

* 🔥 Better AI prediction accuracy
* 📊 Advanced analytics dashboard
* 📱 Mobile responsiveness improvements
* 🧠 More AI features

---

## 👨‍💻 Author

**Ruthvik Chintu**

* GitHub: https://github.com/vruthvik-chinthoju

---

## ⭐ Support

If you like this project:

* ⭐ Star the repo
* 🍴 Fork it
* 🧑‍💻 Contribute

---

## 📄 License

This project is licensed under the MIT License.
