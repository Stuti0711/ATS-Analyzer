# ATS-Analyzer 📄

A powerful AI-powered **Applicant Tracking System (ATS) Resume Analyzer** built with Streamlit. This tool evaluates how well your resume matches a given job description using advanced LLMs (like Google Gemini), helping you optimize your resume to pass through ATS filters used by companies in their hiring process.

🔗 **Live Demo:** [atsanalyzer.streamlit.app](https://atsanalyzer.streamlit.app/)

---

## 📌 Overview

Recruiters often use ATS software to filter resumes based on job relevance, meaning poorly optimized resumes may get rejected before human review.  
**ATS-Analyzer** helps you:

- Improve resume alignment with job descriptions.
- Understand key missing skills and experiences.
- Get actionable suggestions to tailor your resume.

Whether you're a job seeker, a student, or a professional — this tool gives you a competitive edge in the job market.

---

## 🚀 Features

- 📤 Upload your **resume (PDF)**
- 📋 Paste or input the **job description**
- 🤖 Uses **AI (LLM like Google Gemini)** to:
  - Extract relevant skills
  - Match keywords
  - Evaluate experience relevance
- 📊 **Score your resume** against the job post
- 💡 Receive **personalized improvement tips**
- 🧾 Download or copy optimized suggestions

---

## 📂 How It Works

1. **PDF Parsing**  
   Extracts text content from the uploaded resume using `pdfplumber`.

2. **LLM-Based Matching**  
   Sends the resume and job description to a language model API (e.g., Google Gemini) to:
   - Score alignment (e.g., skills, experience, education)
   - Identify missing keywords or required fields

3. **Scoring & Suggestions**  
   Outputs a percentage-based compatibility score and improvement suggestions.
