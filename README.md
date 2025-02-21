# 🚀 HR Expert – Automated Resume Screening System

This workflow automates the process of handling job applications by **extracting relevant information from submitted CVs, analyzing the candidate’s qualifications**, and comparing them against a predefined profile. The final results are stored in **Google Sheets** for further evaluation.

<img width="1239" alt="Screen Shot 2025-02-20 at 8 21 21 PM" src="https://github.com/user-attachments/assets/61a11190-1aee-4753-a7a9-958063fe3d39" />

---


## 🎯 Features
- **Automated CV Upload & Processing**: Uploads resumes and extracts data using OCR.
- **Personal & Qualification Data Extraction**: Identifies relevant details from resumes.
- **AI-Powered Candidate Summarization**: Uses OpenAI to generate structured candidate summaries.
- **Profile Matching & Evaluation**: Compares candidate qualifications with job requirements.
- **Google Sheets Integration**: Stores processed candidate evaluations for HR review.

---

## 🛠️ Workflow Overview
1. **Form Submission**: Candidates submit their resumes through a form.
2. **Resume Processing**:
   - Uploaded to **Google Drive** and converted.
   - Extracted using **OCR (Extract from PDF)**.
   - Processed to extract **Personal Data** and **Qualifications**.
3. **Data Merging**: Consolidates extracted information.
4. **AI Summarization**: OpenAI generates structured candidate insights.
5. **Profile Matching**: Evaluates how well the candidate fits the job profile.
6. **Final HR Evaluation**: HR agent review and scoring.
7. **Results Stored**: Processed data is saved in **Google Sheets**.

---

## 📦 Installation & Setup
To run this project locally, follow these steps:

```bash
# Clone the repository
git clone https://github.com/your-repo/hr-expert-resume-screening.git
cd hr-expert-resume-screening

# Install dependencies
pip install -r requirements.txt

# Run the application
streamlit run app.py
