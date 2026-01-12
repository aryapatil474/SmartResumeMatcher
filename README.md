# 🚀 CareerConnect – Resume–Job Matching Platform

[![Python](https://img.shields.io/badge/Python-3.11-blue)](https://www.python.org/)
[![Flask](https://img.shields.io/badge/Flask-2.3-green)](https://flask.palletsprojects.com/)
[![MongoDB](https://img.shields.io/badge/MongoDB-6.0-brightgreen)](https://www.mongodb.com/)
[![spaCy](https://img.shields.io/badge/spaCy-3.5-orange)](https://spacy.io/)

**CareerConnect** is a **web-based application** that streamlines **matching candidate resumes with job descriptions** using advanced **Natural Language Processing (NLP)**. It provides an **efficient and user-friendly interface** for both candidates and companies.

---

## 🌟 Features

### 🔹 Main Menu & Navigation
- **Clean and intuitive user interface**  
- Easy navigation to **Login**, **Registration**, **About**, and **Articles** sections

### 🔐 User Authentication
- **Secure user registration and login**  
- **Encrypted password storage** for safety

### 👤 User Roles

**Candidates**  
- Secure registration and login  
- **Upload resumes in PDF format**

**Companies**  
- Register and log in  
- **Post job descriptions** and **search for matching resumes**

### 📄 For Candidates
- **Resume Upload:** Upload resumes in **PDF format**, securely stored in the database

### 🏢 For Companies
- **Job Description Entry:** Enter **job descriptions** to find suitable candidates  
- **Resume Matching (Core Feature):**  
  - Fine-tuned **spaCy English model (`en_core_web_sm`)** extracts **technical and skill-based keywords**  
  - Keywords from job descriptions are matched with **candidate skills in MongoDB**  
  - **Candidates ranked by skill overlap**  
  - **Candidates with no matching skills are excluded**  
  - Companies can **view and download matched resumes**

---

### 📌 Matching Logic Examples
- **Highest skill overlap candidates appear first**  
- **Candidates without relevant skills are not listed**

---

## 🛠️ Tech Stack

**Back-End**  
- **Flask:** Python micro web framework  
- **MongoDB:** NoSQL database for user data & resumes  
- **spaCy:** NLP library for keyword extraction

**Front-End**  
- **HTML5** – Structure & content  
- **CSS3** – Styling & layout  

**Infrastructure**  
- **GitHub** – Version control & collaborative development  

---

## ✅ Conclusion

**CareerConnect** is a **powerful recruitment support platform** that **automates resume–job matching using NLP**. Its **secure authentication system**, **structured workflow**, and **intelligent ranking mechanism** help **recruiters identify the most relevant candidates efficiently**, while providing **job seekers with a smooth and secure experience**.

---

## 🤝 Contributing

**Contributions are welcome!**  

You can contribute by:  
- **Enhancing existing features**  
- **Improving documentation**  
- **Adding new functionality**  

---

💡 **Tip:** Add a **screenshot or demo GIF** of the platform at the top for a professional look.
