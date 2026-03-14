# ResumeBoost AI  🚀

A powerful, beginner-friendly hackathon project that uses Gemini AI to analyze resumes against job descriptions, providing actionable feedback and ATS scoring.

## 🌟 Features
- **PDF Text Extraction**: Instantly extracts text from uploaded resume PDFs.
- **AI Analysis**: Uses Gemini 3 Flash to evaluate skills, projects, and keywords.
- **ATS Scoring**: Provides a match score out of 10 based on the job description.
- **Skill Gap Analysis**: Identifies missing skills and keywords.
- **Actionable Tasks**: Generates 3 specific tasks to improve your score to 8+/10.
- **Re-evaluation**: Iteratively improve your resume by pasting updated text.
- **Modern UI**: Built with a clean, technical dashboard aesthetic using Tailwind CSS.

## 🛠️ Tech Stack
- **Frontend**: React 19, TypeScript, Tailwind CSS
- **AI**: Google Gemini API (@google/genai)
- **PDF Parsing**: PDF.js (pdfjs-dist)
- **Icons**: Lucide React
- **Animations**: Framer Motion

## 📁 Folder Structure
```
/
├── src/
│   ├── App.tsx        # Main application logic & UI
│   ├── main.tsx       # Entry point
│   └── index.css      # Global styles & Tailwind
├── public/            # Static assets
├── metadata.json      # App metadata
└── package.json       # Dependencies
```

## 🚀 Installation & Setup

1. **Clone the repository** (or download the project).
2. **Install dependencies**:
   ```bash
   npm install
   ```
3. **Set up Environment Variables**:
   Create a `.env` file (or use the AI Studio Secrets panel) and add:
   ```env
   GEMINI_API_KEY=your_api_key_here
   ```
4. **Run the app**:
   ```bash
   npm run dev
   ```

## 💡 How to Present at a Hackathon
1. **The Hook**: Start by mentioning how hard it is for candidates to know why they aren't getting interviews.
2. **The Demo**: Upload a real resume, paste a challenging job description, and show the "Missing Skills" and "Improvement Tasks".
3. **The Iteration**: Copy a suggestion from the AI, paste it into the "Re-evaluate" section, and show the score increasing.
4. **The Tech**: Highlight the use of Gemini 3 Flash for low-latency, high-accuracy JSON extraction.

## 🔮 Future Improvements
- **Multi-resume Comparison**: Compare multiple resumes for the same role.
- **LinkedIn Integration**: Import profile data directly.
- **Cover Letter Generator**: Automatically generate a tailored cover letter based on the analysis.
