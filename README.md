# AI Resume Screening & Candidate Ranking System

## Project Overview

This project is a Machine Learning based Resume Screening and Candidate Ranking System developed using Python in Google Colab.

The system automatically reads multiple PDF resumes, extracts the text, compares each resume with a given job description using Natural Language Processing (NLP) techniques, calculates similarity scores, ranks candidates, identifies missing skills, and generates a final ranking report.

This project demonstrates how AI can assist recruiters in selecting the most suitable candidates efficiently.

---

## Features

- Upload multiple PDF resumes
- Extract resume text automatically
- Text preprocessing using NLP
- TF-IDF Vectorization
- Cosine Similarity based matching
- Resume Ranking
- Missing Skill Identification
- Candidate Recommendation
- Word Cloud Visualization
- Resume Ranking Bar Chart
- Export Results as CSV Report

---

## Technologies Used

- Python
- Google Colab
- PyMuPDF
- NLTK
- Scikit-learn
- Pandas
- NumPy
- Matplotlib
- WordCloud

---

## Project Workflow

1. Upload Resume PDFs
2. Extract Resume Text
3. Clean and Preprocess Text
4. Read Job Description
5. Convert Text using TF-IDF
6. Calculate Cosine Similarity
7. Rank Candidates
8. Identify Missing Skills
9. Visualize Results
10. Export Final Report

---

## Project Structure

```
FUTURE_ML_03/
│── Resume_Screening_System.ipynb
│── requirements.txt
│── README.md
│── job_description.txt
│── Resume1_ML_Engineer.pdf
│── Resume2_Python_Developer.pdf
│── Resume3_Data_Analyst.pdf
│── Resume4_Java_Developer.pdf
│── Resume5_Frontend_Developer.pdf
│── Final_Resume_Ranking_Report.csv
```

---

## Installation

Install the required libraries using:

```bash
pip install -r requirements.txt
```

---

## How to Run

- Open the notebook in Google Colab.
- Install the required libraries.
- Upload the resume PDF files.
- Run all notebook cells.
- View candidate rankings and similarity scores.
- Download the generated CSV report.

---

## Output

The system generates:

- Resume Match Score
- Candidate Ranking
- Missing Skills Report
- Best Candidate Recommendation
- Word Cloud
- Ranking Chart
- CSV Report

---

## Future Improvements

- ATS Score Calculation
- Streamlit Web Application
- Advanced NLP using spaCy
- Resume Classification
- Experience & Education Extraction
- Skill Weighting

---

## Author

**Shaik Karishma**

B.Tech Computer Science and Engineering

Machine Learning Internship Project – Future Interns

---

## License

This project is developed for educational and internship purposes.
