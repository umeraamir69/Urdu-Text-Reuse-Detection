# Urdu Text Reuse Detection

**Final Year Project (FYP)** | **COMSATS University Islamabad, Lahore Campus**  
**Session 2021–2025**

---

## 📚 Project Overview
In today's digital world, the unauthorized reuse and plagiarism of content, especially in low-resource languages like Urdu, has become increasingly common.

**Urdu Text Reuse Detection** is a research and development project aimed at building Urdu corpora using a *semi-automated back-translation approach* and applying *Machine Learning* (ML), *Deep Learning* (DL), and *Large Language Model* (LLM) techniques for detecting text reuse and plagiarism.

This project also provides a user-friendly **web application** and **REST APIs** for practical usage.

---

## 🌟 Objectives
- **Creation of 9 Urdu Text Reuse Corpora** using back-translation techniques.
- **Training ML and DL models** to predict and classify text reuse:
  - Partially Derived (PD)
  - Wholly Derived (WD)
  - Non-Derived (ND)
- **Development of a Web Application** for plagiarism and reuse detection.
- **Deployment of REST APIs** for external integrations.
- **Contribution to Urdu NLP Resources.**

---

## 📜 Problem Statement
- Lack of large-scale, publicly available Urdu text reuse datasets.
- Urdu's complex grammar makes reuse detection difficult.
- Limited research in Urdu plagiarism detection.

---

## ⚙️ Features
- Creation of multiple Urdu corpora from the COUNTER dataset via back-translation.
- Application of ML (SVM, KNN, Naive Bayes) and DL (CNN, LSTM, Transformers).
- Web App with:
  - Login, Registration, Profile Management
  - Urdu Text Reuse and Plagiarism Detection
  - OCR support for image-to-text extraction
  - API Key Management and Usage Analytics
- REST API services with Rate Limiting and Monitoring.
- Admin Dashboard for system and user management.

---

## 🛠️ Tech Stack
- **ML/DL Frameworks**: Scikit-learn, TensorFlow, Huggingface Transformers
- **Backend**: Python (Flask / Django)
- **Frontend**: React.js / Next.js
- **Database**: PostgreSQL / MySQL
- **OCR**: Tesseract OCR
- **Authentication**: JWT
- **Hosting**: AWS / Heroku / DigitalOcean

---

## 🧪 Project Structure
```bash
Root Directory
|
|— Web Development App
|     |— public/
|     |— src/
|     |— package.json
|     |— README.md
|
|— Python Server API
|     |— app/
|     |— models/
|     |— static/
|     |— templates/
|     |— requirements.txt
|
|— Native App
      |— android/
      |— ios/
      |— src/
      |— App.js
      |— package.json
```
- **Web Development App**: Frontend source code (React.js based)
- **Python Server API**: Backend server code with API routes, ML models, and database integration.
- **Native App**: Mobile application (React Native) for mobile reuse detection.

---

## 🤮 Testing
- Unit Testing
- Integration Testing
- Compatibility Testing
- Acceptance Testing

---

## 🏆 Achievements
- Developed 9 new Urdu reuse corpora via innovative back-translation.
- Integrated trained ML/DL models into a live web system.
- Provided public API access for text reuse detection.
- Contributed to Urdu NLP research and resources.

---

## 🚀 Future Work
- Expanding datasets with more Urdu sources.
- Cross-language reuse detection (e.g., Urdu-English).
- Model optimization for better accuracy and performance.
- Mobile application enhancement for offline use.

---

## ✍️ Contributors
- Muhammad Umer Aamir (FA21-BSE-114)
- Malik Ashas (FA21-BSE-120)
- Usama Tufail (FA21-BSE-053)

**Supervisor:**  
Dr. Muhammad Sharjeel (Assistant Professor, CUI Lahore)

---

> **Note:** This project focuses only on the Urdu language. Cross-lingual and unsupervised approaches are not covered.
