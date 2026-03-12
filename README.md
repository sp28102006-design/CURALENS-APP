 🧬 CURALENS – AI-Based Laboratory Test Interpretation System

 📌 Project Overview

CURALENS is an AI-powered healthcare web application developed during the KreativeGenesis Hackathon 2026 organized by KGiSL Educational Institutions.

The main objective of CURALENS is to simplify the interpretation of laboratory test reports using Artificial Intelligence and automated text extraction.

Many patients find it difficult to understand laboratory reports because they contain complex medical terminology and numerical test values. CURALENS solves this problem by extracting test values from uploaded reports and providing AI-based interpretations that help users understand their health information easily.

The application focuses on **accessibility, automation, and clarity**, making healthcare data easier to interpret for patients and healthcare users.



 🌐 Live Application

🔗 Live Website:  
https://curalens-ai.netlify.app/

The application demonstrates the complete workflow including:

- User registration and authentication  
- Uploading laboratory reports (image or PDF)  
- OCR-based text extraction  
- AI-based laboratory value analysis  
- Display of interpreted health insights  



 🎯 Problem Statement

Medical laboratory reports are often difficult for patients to understand without professional medical knowledge. The values, abbreviations, and medical terms can cause confusion.

CURALENS aims to bridge this gap by automatically extracting laboratory data and converting it into understandable health insights using AI.

---

⚙️ Features

- AI-based laboratory test interpretation  
- OCR-based lab report text extraction  
- Secure user authentication  
- Cloud-based storage of user reports  
- Automated analysis of extracted test values  
- User-friendly interface for easy understanding  



 🧠 Technologies Used

 Frontend
- React.js

 Backend
- Node.js

 Authentication
- Firebase Authentication

 Database
- Cloud Firestore

 Cloud Storage
- Firebase

 OCR Technology
- Tesseract OCR

 Artificial Intelligence
- AI-based analysis for interpreting laboratory values and generating health insights.



 🏗️ Project Architecture
```
User Uploads Lab Report
        │
        ▼
OCR Extracts Text (Tesseract)
        │
        ▼
Extracted Lab Values
        │
        ▼
AI Analysis Engine
        │
        ▼
Health Insight & Interpretation
        │
        ▼
Results Displayed to User
```

---

 📂 Project Structure

```
curalens/
│
├── frontend/
│   ├── components/
│   ├── pages/
│   ├── App.js
│   └── index.js
│
├── backend/
│   ├── routes/
│   ├── controllers/
│   └── server.js
│
├── firebase/
│   └── config.js
│
├── ocr/
│   └── textExtraction.js
│
└── README.md
```

 👩‍💻 Hackathon Experience

CURALENS was developed during a **30-hour hackathon**, where rapid development, teamwork, and innovation were essential.

During the hackathon, the project went through multiple checkpoints including:

- Problem identification and idea presentation  
- Application UI development and authentication setup  
- OCR integration for report extraction  
- AI-based analysis implementation  
- Final demonstration and project presentation  

---

## 📜 License

This project is created for **educational and research purposes**.

---

## 🙌 Acknowledgment

This project was developed during **KreativeGenesis Hackathon 2026** hosted by **KGiSL Educational Institutions**, providing an excellent opportunity to build innovative solutions in the healthcare technology domain.
