# Phishing Simulation & Awareness System

A web-based application to simulate phishing attacks and raise awareness among users.  
Developed with NestJS (backend), React (frontend), MongoDB (database).

---

## ✅ Features Implemented
- [ ] User registration and login with JWT(partially implemented)
- [x] MongoDB schema for user and phishing tracking
- [x] Sending phishing email via Nodemailer
- [ ] Frontend interface (partially implemented)
- [ ] Docker deployment (not completed)

---

## 🚧 What's Missing
- UI integration with backend
- Phishing click tracking endpoint
- Full phishing history view
- Docker Compose setup

---

## 🔄 Project Structure
- `phishing-attempt-management/` – User login & registration (NestJS)
- `phishing-simulation-service/` – Email sending and click tracking (NestJS)
- `phishing-simulation-front/` – Admin dashboard (React) – *in progress*
- `db/` – MongoDB

---

##  Installation Instructions

### 1. Clone repo
```bash
git clone https://github.com/rut-kramer/Phishing-Simulation.git
cd phishing-app

### 2. Install backend dependencies

cd phishing-attempt-management
npm install
npm run start:dev
(repeat for phishing-simulation-service)

### 3. Start frontend

cd clienphishing-simulation-frontt
npm install
npm start

 Example .env (for NestJS servers)
JWT_SECRET=yourSecret
MONGO_URI=mongodb://localhost:27017/phishing-db
EMAIL_USER=your@email.com
EMAIL_PASS=yourEmailPassword

Notes
This project is still under development. Due to time constraints, not all features are fully functional.
The code structure and logic are prepared for future completion.



---