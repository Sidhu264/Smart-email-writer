# 📧 Smart Email Assistant  

An AI-powered full-stack application that generates professional email replies using **Spring Boot**,**Spring AI**, **React.js**, and **Google Gemini AI API**.  
The project is containerized with Docker, deployed on **Render (backend)** and **Netlify (frontend)**.  

---

## 🚀 Live Demo  
👉 [Smart Email Assistant – Live App](https://graceful-taiyaki-d75bd0.netlify.app)  

---

## ✨ Features    
- 🤖 **AI-powered email reply generation** using Gemini API.  
- 🎨 **Responsive UI** built with React + Material UI.  
- 📋 Copy-to-clipboard functionality for generated replies.  
- ☁️ **Deployed on Render & Netlify** for seamless cloud hosting.  
- 🐳 **Dockerized backend** with multi-stage build for optimized deployment.
- 🧩 **Chrome Extension with Gmail Integration** – Injects an **AI Reply button** directly into Gmail’s compose toolbar.  
   - Captures the email body from Gmail’s UI.  
   - Calls the backend API to generate a professional reply.  
   - Auto-inserts the generated reply into Gmail’s compose box.  
   - Seamlessly blends with Gmail’s native UI/UX.  


---

## 🛠️ Tech Stack  

### Backend (Spring Boot)  
- Java 21  
- Spring Boot (REST API, Spring Security)  
- WebClient for API integration  
- Lombok for cleaner code  
- Docker (multi-stage build)  
- Deployment: Render  

### Frontend (React.js)  
- React 18  
- Material UI (MUI) for modern UI components  
- Axios for API calls  
- Netlify deployment  

### AI Integration  
- Google Gemini API (configurable via environment variables)  

---
