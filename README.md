# ATS-Analyzer 🧠📄

An AI-powered resume analyzer built with **Streamlit**, designed to help job seekers tailor their resumes to specific job descriptions. It uses **LLMs like Google Gemini** to evaluate resume relevance and improve chances of passing Applicant Tracking Systems (ATS).

🔗 **Live Demo:** [atsanalyzer.streamlit.app](https://atsanalyzer.streamlit.app/)

---

## 🚀 Features

- 📄 Upload resume (PDF)
- 🧾 Paste a job description
- 🤖 AI analyzes skills, keywords, and relevance
- 📊 Compatibility score between resume & job post
- 💡 Improvement suggestions

---

## 🧠 Tech Stack (Detailed)

### 🖥️ Frontend – **Streamlit**
- Provides an interactive UI for users to upload resumes and paste job descriptions.
- Clean, fast, and mobile-responsive experience using minimal code.
- Displays results like resume score, keyword matches, and AI suggestions.

### 🧠 AI/LLM – **Google Gemini API (or similar)**
- Powers the core intelligence of the app.
- Compares resume content with the job description.
- Returns:
  - Skill match analysis
  - Keyword gaps
  - Personalized suggestions to enhance alignment.

### 🐍 Backend – **Python**
- Handles the logic for parsing, preparing prompts, calling the LLM, and processing responses.
- Manages file uploads and data formatting before AI analysis.

### 📄 PDF Parsing – **pdfplumber**
- Extracts readable text content from uploaded resume PDFs.
- Ensures only useful sections are passed to the AI for analysis.

### ☁️ Deployment – **Streamlit Cloud**
- Free cloud hosting of the app with one-click deployment.
- Automatically updates the app on every GitHub push.
- Securely manages `.env` API keys through Streamlit secrets.

---

Let me know if you want this formatted as a full GitHub `README.md` file or need badges, screenshots, or install instructions added!

