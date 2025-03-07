AI Resume Screening & Candidate Ranking System

Overview

This project is an AI-powered Resume Screening & Candidate Ranking System built using Streamlit, PyPDF2, and Scikit-learn. The system ranks resumes based on their relevance to a given job description using TF-IDF vectorization and cosine similarity.

Features:

1.It Allows users to input a job description.

2.It Supports uploading multiple resumes in PDF format.

3.It Extracts text from resumes and ranks them based on similarity to the job description.

4.It Displays the ranking in descending order of relevance.

Installation

Prerequisites:

Ensure you have Python installed on your system. Install the required dependencies using:

           pip install streamlit PyPDF2 scikit-learn pandas

Usage:

Run the application using the command:

                streamlit run app.py

->Enter a job description in the provided text box.

->Upload PDF resumes to be ranked.

->The system will extract text, compute cosine similarity, and display the ranked resumes.

Code Explanation:

->extract_text_from_pdf(file): Extracts text from uploaded PDF resumes.

->rank_resumes(job_description, resumes):

->Converts job descriptions and resumes into TF-IDF vectors.

->Computes cosine similarity to determine the relevance of each resume.

->Returns similarity scores for ranking.

Streamlit UI:

1.It accepts job descriptions.

2.It allows multiple resume uploads.

3.It displays a ranked list of resumes based on their scores.




