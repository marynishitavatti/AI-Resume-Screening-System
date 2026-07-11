# AI Resume Screening System

## Overview

The AI Resume Screening System is a Machine Learning project that automatically screens and ranks resumes based on their similarity to a selected job description. The system uses Natural Language Processing (NLP) techniques to compare resume content with job requirements and identify the most relevant candidates.

This project helps recruiters save time by automatically shortlisting the best applicants instead of manually reviewing every resume.

---

## Problem Statement

Recruiters often receive hundreds of resumes for a single job opening, making manual screening time-consuming and inefficient.

This project automates the resume screening process by analyzing resume text and ranking candidates according to their relevance to a given job role.

---

## Objectives

- Read resume data from an Excel dataset.
- Accept a job role as input.
- Retrieve the corresponding job description.
- Convert text into numerical features using TF-IDF.
- Calculate similarity scores using Cosine Similarity.
- Rank resumes from highest to lowest match.
- Display the top matching candidates.

---

## Features

- AI-based Resume Screening
- Automatic Candidate Ranking
- Job Role Selection
- TF-IDF Text Vectorization
- Cosine Similarity Matching
- Top Candidate Recommendation
- Fast Resume Shortlisting

---

## Dataset

This project uses a custom dataset containing:

- Candidate Names
- Resume Text
- Skills
- Experience
- Job Roles

Dataset Format:

- Excel (.xlsx)

> **Note:** The dataset used in this project is a custom demo dataset created for educational purposes and is not publicly available.

---

## Technologies Used

- Python
- Pandas
- Scikit-learn
- TF-IDF Vectorizer
- Cosine Similarity
- Matplotlib
- Jupyter Notebook

---

## Machine Learning Techniques

- Natural Language Processing (NLP)
- TF-IDF Vectorization
- Cosine Similarity

---

## Project Workflow

1. Load the resume dataset.
2. Select a job role.
3. Retrieve the corresponding job description.
4. Convert text into TF-IDF vectors.
5. Compute cosine similarity scores.
6. Rank resumes based on similarity.
7. Display the top matching candidates.

---

## Project Structure

```
AI-Resume-Screening-System/
│
├── README.md
├── AI_Resume_Screening_System.ipynb
├── Demo_Resume_Dataset_30.xlsx
---

## Output

The system generates:

- Resume similarity scores
- Ranked list of candidates
- Top matching applicants for a selected job role
  
---
Author
Vatti Mary Nishita

B.Tech in Computer Science and Engineering

Interested in Data Analytics, Machine Learning, Artificial Intelligence, NLP, and Data Science.
