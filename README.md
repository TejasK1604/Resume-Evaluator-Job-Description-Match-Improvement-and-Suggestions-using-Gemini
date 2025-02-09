# Resume-Evaluator-Job-Description-Match-Improvement-Suggestions-using-Gemini


## Overview  

The **Resume Evaluator & ATS Score Analyzer** is a **Streamlit-powered** web application designed to assess resumes against job descriptions.  
Using **Google’s Gemini-1.5-Pro model**, the tool evaluates how well a resume aligns with a specific job posting and highlights areas for improvement.  
Additionally, it computes an **ATS (Applicant Tracking System) score**, helping users gauge how effectively their resumes would pass through automated screening systems.  

## Features  

✅ **Smart Resume Analysis** – Uses **Gemini-1.5-Pro** to assess resume relevance and alignment with job descriptions.  
✅ **ATS Compatibility Check** – Calculates a **matching score** and identifies missing or extra skills.  
✅ **Seamless PDF Upload** – Supports **PDF format** for resume submission and processing.  
✅ **Resume Enhancement Suggestions** – Provides actionable feedback to improve resumes based on job-specific requirements.  
✅ **Intuitive Web Interface** – Developed with **Streamlit** for a smooth and interactive user experience.  




## Tech Stack

- **Python** – Backend logic
- **Streamlit** – Web-based user interface
- **Google Gemini-1.5-Pro API** – AI-based resume analysis and ATS scoring
- **PyMuPDF (fitz)** – For extracting text from PDF resumes
- **dotenv** – Secure API key management

## Installation & Setup

### 1. Clone the repository:

```bash
git clone https://github.com/TejasK1604/Resume-Evaluator-Job-Description-Match-Improvement-Suggestions-using-Gemini.git
cd Resume-Evaluator-Job-Description-Match-Improvement-Suggestions-using-Gemini
```

### 2. Create and Activate a Virtual Environment:

```bash
python3 -m venv venv
source venv/bin/activate  # On Windows, use venv\Scripts\activate
```

### 3. Install dependencies:

```bash
pip install -r requirements.txt
```

### 4. Set up Gemini API key:

Create a `.streamlit/secrets.toml` file and add your Gemini API key:

```bash
[secrets]
API_KEY = "your_api_key_here"
```

Alternatively, you can create a `.env` file in the project root and add your Gemini API key:

```bash
API_KEY=your_api_key_here
```

### 5. Run the application:

```bash
streamlit run app.py
```

## Usage

- Open the web interface.
- Enter the Job Description in the provided text area.
- Upload your resume (PDF format) using the uploader.
- Click "Tell Me About the Resume" to get a detailed resume evaluation.
- Click "Get ATS Score" to calculate the ATS score and match percentage.

## Project Structure

```bash
📂 Resume-Evaluator-and-ATS-Score-Analyzer
│── app.py                # Main Streamlit app
│── requirements.txt      # Dependencies
│── .streamlit/secrets.toml  # API key storage (ignored in .gitignore)
│── README.md             # Documentation
```

## Example Output

### Input:

```bash
Job Description: We are looking for a Data Scientist with expertise in Python, machine learning, and NLP.
Resume: (Uploaded as PDF)
```

### Output:

Resume Analysis:

```bash
- The candidate demonstrates strong Python and machine learning skills but lacks experience in NLP-related projects.
- The resume could benefit from showcasing more specific NLP expertise.
```

ATS Score:

```bash
- The candidate demonstrates strong Python and machine learning skills but lacks experience in NLP-related projects.
- The resume could benefit from showcasing more specific NLP expertise.
```

## Conclusion

The Resume Evaluator and ATS Score Analyzer helps job seekers tailor their resumes to match job descriptions, providing valuable insights for both human and automated screening. By leveraging Google's Gemini-1.5-Pro model, this tool helps users optimize their resumes for higher chances of success.

With an intuitive Streamlit interface and secure API key management via dotenv, the application is easy to use and deploy. Future enhancements could include multi-language support, deeper integration with job boards, and automated resume formatting tips.

## Contributing

Contributing

Contributions are welcome! To contribute:

1. Fork the repository.

2. Create a new branch:

```bash
git checkout -b feature-branch-name
```

3. Make your changes and commit them:

```bash
git commit -m "Add new feature"
```

4. Push to the branch:

```bash
git push origin feature-branch-name
```

5. Submit a pull request detailing your changes.

## License

This project is licensed under the MIT License - see the [LICENSE](https://github.com/TejasK1604/Resume-Evaluator-Job-Description-Match-Improvement-and-Suggestions-using-Gemini/blob/main/LICENSE) file for details.


## Author

- Tejas Kajale
