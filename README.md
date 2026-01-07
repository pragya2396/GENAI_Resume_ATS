# GENAI_Resume_ATS
**ATS Resume Expert – AI-Powered Resume Screening Tool
Overview**

ATS Resume Expert is an AI-powered web application that evaluates resumes against job descriptions using Google Gemini (Generative AI).
Built with Streamlit, the app simulates how an Applicant Tracking System (ATS) and an experienced HR reviewer analyze resumes for role alignment, keyword relevance, and overall match percentage.

**The tool helps candidates understand:**

* How well their resume matches a job description

* Strengths and weaknesses from an HR perspective

* Missing keywords affecting ATS screening

* Overall resume-job fit score

**Key Features**

* Upload resume in PDF format
* Paste job description
* AI-based resume evaluation using Gemini 2.5 Pro
* ATS-style percentage match scoring
* Identification of missing keywords
* Professional HR-style feedback
* Simple, interactive Streamlit UI
  
**Technologies Used****

* Python
* Streamlit – Web application framework
* Google Generative AI (Gemini 2.5 Pro)
* pdfplumber – PDF text extraction
* python-dotenv – Environment variable management
* PIL (optional image handling)
* Google Generative AI SDK

**How It Works**

* User uploads a resume PDF
* Resume text is extracted using pdfplumber
* User provides a job description
* Gemini AI evaluates the resume using predefined prompts:
 * HR-style resume review
 * ATS-based match percentage analysis
 * Results are displayed directly in the app


**How to Run the Project
Clone the Repository**
git clone https://github.com/your-username/ats-resume-expert.git
cd ats-resume-expert

**Install Dependencies**
pip install -r requirements.txt

**Set Up Environment Variables**

Create a .env file:

GOOGLE_API_KEY=your_google_gemini_api_key

**Run the Streamlit App**
streamlit run app.py

App Functionalities

🔹 **Tell Me About the Resume**

HR-style professional evaluation

Strengths and weaknesses

Alignment with job requirements

🔹 **Percentage Match**

ATS-style resume scoring

Match percentage

Missing keywords

Final improvement suggestions

