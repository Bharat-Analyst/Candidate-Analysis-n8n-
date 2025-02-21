# 🤖 HR Expert – Automated Resume Screening System (n8n Workflow)

This **n8n workflow** automates the process of handling job applications by **extracting information from submitted CVs, analyzing candidate qualifications**, and comparing them against job requirements. The processed data is stored in **Google Sheets** for HR review.

---
<img width="1239" alt="Screen Shot 2025-02-20 at 8 21 21 PM" src="https://github.com/user-attachments/assets/e774c521-f014-477d-86ff-eab8cb6b70cb" />


## 🎯 Features
- **Automated Resume Upload & Processing**: Uploads CVs and extracts text.
- **Candidate Data Extraction**: Identifies **Personal Information** and **Qualifications**.
- **AI-Powered Summarization**: Uses **OpenAI** to generate structured insights.
- **Profile Matching & HR Review**: Compares extracted data with job requirements.
- **Google Sheets Integration**: Stores final evaluation results for easy access.

---

## 🔄 Workflow Overview
### **1️⃣ Form Submission**
- A candidate submits their **resume** via an online form.

### **2️⃣ Resume Processing**
- Uploaded **CVs are stored in Google Drive**.
- Extracted using **PDF/Text processing nodes**.

### **3️⃣ Extract Candidate Data**
- **Personal Data** and **Qualifications** are processed using AI.

### **4️⃣ AI Summarization & Profile Matching**
- The **Summarization Chain** compiles relevant information.
- The **HR Expert node** matches the candidate profile against job requirements.

### **5️⃣ Candidate Evaluation & Storage**
- The system generates an **HR review & matching score**.
- Data is **stored in Google Sheets** for final review.
