# 🍽️ MealConnect

> A full-stack food donation and distribution platform that bridges the gap between food donors and NGOs, helping reduce food waste while serving communities in need.

![License](https://img.shields.io/badge/License-MIT-blue.svg)
![Node.js](https://img.shields.io/badge/Backend-Node.js-green)
![MongoDB](https://img.shields.io/badge/Database-MongoDB-success)
![Express](https://img.shields.io/badge/Framework-Express.js-lightgrey)

---

## 📌 Overview

MealConnect is a full-stack web application designed to simplify food donation management by connecting restaurants, hotels, event organizers, and individuals with NGOs and volunteers. The platform enables donors to post surplus food, while NGOs can efficiently claim and distribute it to people in need.

The application aims to reduce food wastage, streamline donation logistics, and promote sustainable community support.

---

## ✨ Features

- User Authentication & Authorization
- Secure Login and Registration
- Food Donation Management
- NGO Dashboard
- Donor Dashboard
- Food Request System
- Real-Time Donation Tracking
- SMS Notifications (Twilio Integration)
- RESTful APIs
- MongoDB Database Integration
- Responsive User Interface
- Secure Environment Variable Management
- Error Handling & Validation

---

## 🛠️ Tech Stack

### Frontend
- REST API
- Tailwind.css
- JavaScript
- Bootstrap

### Backend
- Node.js
- Express.js

### Database
- MongoDB

### APIs & Services
- Twilio API

### Tools
- Git
- GitHub
- Postman
- VS Code

---

## 📂 Project Structure

```
MealConnect/
│
├── backend/
│   ├── config/
│   ├── controllers/
│   ├── middleware/
│   ├── models/
│   ├── routes/
│   ├── services/
│   ├── twilio/
│   ├── server.js
│   └── package.json
│
├── frontend/
│   ├── eslint.config.js
│   ├── package-lock.json
│   ├── uno.config.js
│   ├── vite.config.js
│   └── public/
    │   ├── home.PNG
    │   ├── peep.PNG
    │   ├── peep1.PNG
    │    └── peep2.PNG
      src/
    │   ├── assets/
    │   ├── components/
    │   ├── pages/
    │   ├── utils/
        |── App.css
        |── index.css
        |── main.js

│
└── README.md
```

---

## ⚙️ Installation

### Clone Repository

```bash
git clone https://github.com/sayali6804/MealConnect.git
```

### Navigate to Backend

```bash
cd backend
```

### Install Dependencies

```bash
npm install
```

### Configure Environment Variables

Create a `.env` file and add:

```env
PORT=5000
MONGODB_URI=YOUR_MONGODB_CONNECTION_STRING
JWT_SECRET=YOUR_SECRET_KEY

TWILIO_ACCOUNT_SID=YOUR_ACCOUNT_SID
TWILIO_AUTH_TOKEN=YOUR_AUTH_TOKEN
TWILIO_PHONE_NUMBER=YOUR_PHONE_NUMBER
```

### Start Server

```bash
npm start
```

or

```bash
node server.js
```

---

## 🚀 Future Enhancements

- Live location tracking
- AI-based food demand prediction
- Email notifications
- Donation analytics dashboard
- QR-based food verification
- Mobile application
- Payment gateway for NGO support

---

## 📈 Project Objectives

- Reduce food wastage
- Enable quick food distribution
- Improve NGO accessibility
- Simplify donation management
- Promote sustainable community support

---

## 🔒 Security

- JWT Authentication
- Environment Variables
- Password Encryption
- Input Validation
- Secure REST APIs

---

## 🤝 Contributing

Contributions, suggestions, and improvements are welcome.

1. Fork the repository
2. Create your feature branch
3. Commit your changes
4. Push to your branch
5. Create a Pull Request

---

## 📄 License

This project is developed for educational and social impact purposes.

---

## 👩‍💻 Author

**Sayali Lagad**

- GitHub: [https://github.com/yourusername](https://github.com/sayali6804/)
- LinkedIn: [https://linkedin.com/in/yourprofile](https://linkedin.com/in/sayali-lagad-970519361)

---

⭐ If you found this project useful, consider giving it a Star!
