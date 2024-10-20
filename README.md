

# Smart ATS - Resume Matching with Job Description

## Overview
**Smart ATS** is an AI-powered resume evaluation tool designed to help users improve their resumes by matching them with job descriptions. The application leverages **Google Gemini AI** to act like a skilled **Applicant Tracking System (ATS)**, providing feedback on resume-job description compatibility, missing keywords, and profile summary.

## How It Works
1. **Upload Resume**: Users upload their resume in PDF format.
2. **Paste Job Description**: Users paste the job description they want their resume to match.
3. **AI Analysis**: The AI evaluates the resume against the provided job description, acting as a skilled ATS.
4. **Detailed Feedback**: The app provides:
   - Percentage match with the job description.
   - Missing keywords in the resume based on the job description.
   - Profile summary suggestions for improvement.

## Features
- Upload resumes in **PDF format**.
- Analyze job descriptions and resumes using **Google Gemini AI**.
- Get a comprehensive **feedback report** with:
  - Percentage match.
  - Missing keywords.
  - Profile summary enhancement.

## Setup & Installation
1. Clone the repository:
    ```bash
    git clone https://github.com/dineshramv13/ATS-AI-Resume-Matcher

    ```

2. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```

3. Set up environment variables:
    - Create a `.env` file in the root directory.
    - Add your **Google API Key** in the `.env` file:
      ```plaintext
      GOOGLE_API_KEY=<your_google_api_key>
      ```

4. Run the app:
    ```bash
    streamlit run app.py
    ```

## Usage
1. Open the Streamlit web interface.
2. Paste the job description in the text area.
3. Upload your resume in PDF format.
4. Click "Submit" to receive the evaluation results.

## Future Enhancements
- **Extended file type support** for resumes (e.g., DOCX).
- **Enhanced ATS evaluation criteria** for a wider range of industries and roles.
- **Multilingual support** for non-English resumes and job descriptions.


