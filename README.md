# 📄 Resume Screening & Candidate Ranking System

## 📌 Overview

This project builds an NLP-based resume screening system that:

- Parses resume text
- Cleans and preprocesses unstructured data
- Matches resumes against a job description
- Scores candidates using cosine similarity
- Ranks candidates based on role fit
- Identifies missing skills

This simulates modern HR-tech resume screening tools.

---

## ⚙️ Tech Stack

- Python
- Pandas
- NLTK
- Scikit-learn
- TF-IDF
- Cosine Similarity

---

## 🧠 Features Implemented

- Resume text cleaning and preprocessing
- Job description parsing
- TF-IDF feature extraction
- Cosine similarity scoring
- Resume ranking system
- Skill gap identification
- Business explanation & decision logic

---

## 📊 How Ranking Works

1. Job description converted to TF-IDF vector
2. All resumes converted to same feature space
3. Cosine similarity calculated
4. Resumes ranked by similarity score
5. Missing required skills identified per candidate

---

## 🎯 Business Impact

This system helps recruiters:

- Shortlist candidates faster
- Objectively compare applicants
- Identify skill gaps instantly
- Reduce manual screening time
- Improve hiring efficiency

---

## 🚀 How to Run

```bash
pip install -r requirements.txt