# 📄 Resume Matching System

**Description:**  
This project is a **Resume Matching System** built using **Python**, **TF-IDF**, and **Cosine Similarity**. It helps HR teams and recruiters automatically **rank resumes** based on how well they match a given job description.  

Currently, the system supports **.txt resumes**, with a preprocessing and ranking pipeline fully implemented. Support for **PDF resumes** (including scanned PDFs) will be added in future updates.  

---

## 🔹 Features

- Upload multiple `.txt` resumes  
- Enter a job description for comparison  
- Automatic text cleaning:
  - Lowercasing  
  - Removing emails, numbers, punctuation  
  - Stopword removal  
  - Lemmatization  
- Convert resumes and job description to **numerical vectors** using **TF-IDF**  
- Compute **cosine similarity** to rank resumes  
- Interactive **Streamlit app** for easy use  

---

## 🔹 Technology Stack

- **Python**  
- **Scikit-learn** (TF-IDF, cosine similarity)  
- **NLTK** (text preprocessing)  
- **Streamlit** (interactive web app)  

---
## 🔹 Future Enhancements

- Support for PDF resumes (text + scanned images)
- Advanced NLP features for skills extraction and matching
- Deployment to cloud platforms (Streamlit Cloud / Heroku / AWS)
