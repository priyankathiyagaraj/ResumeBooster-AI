# ResumeBoosterAI Resume Analyzer
Project Overview

AI Resume Analyzer is a web application that helps users evaluate and improve their resumes using Artificial Intelligence. The system analyzes a resume PDF, compares it with a target job description, and provides suggestions to improve the resume score.

This project was developed as part of a Hackathon project to demonstrate how AI can help job seekers optimize their resumes for better job opportunities.

Problem Statement

Many students and job seekers struggle to create resumes that match job requirements. They often miss important skills, keywords, and professional summaries that are necessary for passing ATS (Applicant Tracking Systems).

This project helps users analyze their resumes and improve them with AI-based suggestions.

Features

• Upload Resume in PDF format
• Extract text from resume automatically
• Enter target Job Title and Job Description
• AI analyzes resume using Gemini AI
• Resume Score out of 10
• Extracted Skills from resume
• Missing Skills detection
• Professional 2-line summary generation
• Suggestions for improving resume
• Iterative improvement (Re-analyze after editing)

Technologies Used

Frontend
• React
• TypeScript
• Tailwind CSS

AI Integration
• Google Gemini API

Other Libraries
• pdfjs-dist (PDF text extraction)
• Lucide Icons
• Framer Motion

Project Structure
AI-Resume-Analyzer
│
├── src
│   ├── App.tsx
│   ├── main.tsx
│   ├── index.css
│
├── index.html
├── package.json
├── README.md
├── .env
How to Run the Project

1️⃣ Clone the repository

git clone https://github.com/yourusername/ai-resume-analyzer.git

2️⃣ Go to project folder

cd ai-resume-analyzer

3️⃣ Install dependencies

npm install

4️⃣ Add your Gemini API key in .env

VITE_GEMINI_API_KEY=your_api_key

5️⃣ Start the development server

npm run dev

6️⃣ Open in browser

http://localhost:5173
Demo Workflow

Upload Resume PDF

Enter Job Title and Job Description

Click Analyze Resume

AI extracts skills and analyzes resume

View Resume Score and suggestions

Improve resume and re-analyze-AI
This is my first hackthon projecti done my full effect on it
