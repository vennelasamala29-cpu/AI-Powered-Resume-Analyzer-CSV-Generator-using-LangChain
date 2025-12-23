AI-Powered Resume Analyzer & CSV Generator using LangChain
📌 Project Overview

Recruiters and HR teams often receive resumes in bulk, typically as ZIP files containing multiple PDF or DOCX documents. Manually reviewing and extracting key candidate information is time-consuming and error-prone.

AI-Powered Resume Analyzer & CSV Generator automates resume parsing and information extraction using LangChain and LLMs, converting unstructured resume data into a structured CSV file for easy analysis and shortlisting.

🚀 Features

Upload ZIP files containing multiple resumes

Supports PDF and DOCX resume formats

AI-based extraction of key candidate details

Structured output generation in CSV format

Clean and simple Streamlit UI

Scalable design for bulk resume processing

🧠 Extracted Information

The system can extract:

Candidate Name

Email Address

Phone Number

Skills

Education

Work Experience

Years of Experience (if available)

(Fields can be customized based on requirements.)

🛠️ Technology Stack
Component	Technology
Frontend	Streamlit
AI Orchestration	LangChain
LLM	Google Gemini / API-based LLM
Resume Parsing	pdfplumber, python-docx
Data Handling	Pandas
Output Format	CSV
🧩 Architecture

User uploads a ZIP file containing resumes

Files are extracted and parsed (PDF/DOCX)

Resume text is sent to the LLM via LangChain

Structured information is extracted using prompt templates

Output is compiled into a CSV file

User downloads the generated CSV

📂 Project Structure
├── project/
│   ├── main.py
│   ├── utils/
│   ├── prompts/
│   ├── requirements.txt
│   └── .env

⚙️ Setup Instructions
1. Clone the Repository
git clone https://github.com/your-username/ai-resume-analyzer.git
cd ai-resume-analyzer

2. Install Dependencies
pip install -r requirements.txt

3. Configure Environment Variables

Create a .env file and add:

GOOGLE_API_KEY=your_api_key_here

4. Run the Application
streamlit run main.py

📈 Learning Outcomes

Through this project, you will learn:

How to process bulk documents using Python

Resume parsing using PDFs and DOCX files

Prompt engineering for structured output

Using LangChain for real-world AI applications

Automating HR workflows with AI

✅ Use Cases

Resume screening and shortlisting

HR analytics

Recruitment automation

Data preparation for ATS systems

📌 Future Enhancements

ATS scoring and ranking system

Skill-matching against job descriptions

Database integration

UI improvements and filters

🙏 Acknowledgement

Grateful to Innomatics Research Labs for the learning ecosystem, and special thanks to SAXON K SHA Sir and Lakshmi Vangapandu Mam for their guidance and mentorship.

📄 License

This project is for educational purposes.

If you want, I can also provide:

✅ Short README version

✅ Resume bullet points

✅ LinkedIn project description

✅ ATS-friendly project summary

Just tell me 👍

short

Here is a short, clean, and professional README.md for GitHub:

AI-Powered Resume Analyzer & CSV Generator using LangChain
Overview

An AI-driven application that automates resume screening by extracting structured information from bulk PDF and DOCX resumes and exporting the results to a CSV file. Built using Streamlit and LangChain, this project simplifies resume analysis for recruiters and HR teams.

Features

Bulk resume upload via ZIP file

PDF and DOCX support

AI-based resume information extraction

Structured CSV output

Simple Streamlit interface

Tech Stack

Streamlit | LangChain | LLM (API-based) | Pandas | pdfplumber | python-docx

Use Case

Automated resume screening and data preparation for recruitment workflows.

