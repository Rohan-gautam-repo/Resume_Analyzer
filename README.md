AI-Powered Resume Analyzer 📝🤖

An AI-powered resume analyzer that helps job seekers improve their resumes by providing insights, skill classification, ATS scoring, and real-time suggestions. Built using Streamlit and Python, with Google Gemini AI for intelligent resume analysis.

🚀 Features ✅ Resume Parsing & Extraction – Extracts text from PDF/DOCX resumes ✅ Skill Extraction & Classification – Identifies and categorizes skills ✅ AI-Powered Resume Insights – Provides feedback on resume structure, wording, and improvements ✅ ATS Compatibility Score – Analyzes resume based on ATS standards ✅ Download Updated Resume – Generates a revised resume based on AI suggestions ✅ Interactive Dashboard – User-friendly UI for uploading, analyzing, and refining resumes

🏗 Tech Stack Frontend: Streamlit Backend: Python AI Integration: Google Gemini API Parsing & Processing: docx, PyMuPDF, SpaCy

🔧 Installation & Setup 1️⃣ Clone the Repository

2️⃣ Install Dependencies pip install streamlit google-generativeai python-dotenv docx2txt spacy pyMuPDF pandas numpy pdfplumber Pillow nltk

3️⃣ Set Up Google Gemini API Key Get your API key from Google AI Studio Create a .env file and add:

GEMINI_API_KEY=your_api_key_here

4️⃣ Run the Application streamlit run app.py

🎯 Usage 1️⃣ Upload your resume (PDF/DOCX) 2️⃣ Analyze the resume for skills, keywords, and ATS compatibility 3️⃣ Get AI-powered suggestions to improve your resume 4️⃣ Download the improved resume with AI-enhanced formatting
