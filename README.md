# 🧠 AI-Based Resume Shortlisting System

This project automates the initial resume screening process using Natural Language Processing (NLP) and Machine Learning. It compares candidate resumes against a given job description and ranks them based on textual relevance using **TF-IDF vectorization** and **Cosine Similarity**.

---

## 📌 Project Overview

Recruiters often face hundreds of job applications for a single job role. Manually filtering resumes is time-consuming, inconsistent, and error-prone.  
This project addresses these issues by providing:
- ✅ Automated resume shortlisting
- ✅ Scoring system based on match relevance
- ✅ Ranking of candidates using Python-based similarity analysis

---

## 🛠️ Technologies Used

- Python 3
- NumPy
- scikit-learn (TF-IDF, Cosine Similarity)

---

## 🗂️ Files Included

| File Name              | Description                          |
|------------------------|--------------------------------------|
| `resume_shortlist.py`  | Python script that runs the shortlisting logic |
| `Project__Report.docx` | Final project documentation and explanation |

---

## ⚙️ How It Works

1. Takes a job description and multiple resumes as text inputs.
2. Converts them into TF-IDF vectors.
3. Calculates cosine similarity between each resume and the job description.
4. Outputs a match percentage for each resume and ranks them.

---

## 📊 Sample Output
A_Resume.docx: 83.42% match
B_Resume.docx: 61.05% match
C_Resume.docx: 18.23% match

## 👨‍💻 Developed By

**Siddaram Goranal**  
