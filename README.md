📚 StudyMate++ – AI Learning Assistant
An AI-powered study companion built for the SmartInternz Cognitive Hackathon 2025.

StudyMate++ helps students upload PDFs, summarize content, generate flashcards, quizzes, and even debug code — all in one simple interactive interface powered by IBM Granite AI and Gradio.

🔗 Live Demo: Click here to try StudyMate++

🚀 Features
📂 Upload PDFs – Extracts and processes text directly from academic notes, books, or assignments.
📝 Summarization – Generates concise summaries of uploaded documents.
🎯 Flashcards – Creates Q&A-style flashcards for quick revision.
❓ Quiz Generator – Produces MCQs and short-answer quizzes from study material.
🛠️ Code Debugger – Analyzes and suggests fixes for programming code.
🤖 AI Q&A – Ask any question and get context-aware answers from the uploaded PDF.
🧠 Tech Stack
Language Model: IBM Granite 3.3-2B Instruct

Frameworks:

Transformers – Model inference
Gradio – Interactive UI
PyPDF – PDF text extraction
Environment: Python 3.10+

⚙️ Installation
Clone the repository and install dependencies:

git clone https://github.com/your-username/studymate-plus.git
cd studymate-plus

# Create a virtual environment (optional but recommended)
python -m venv venv
source venv/bin/activate   # For Linux/Mac
venv\Scripts\activate      # For Windows

# Install dependencies
pip install -r requirements.txt
Or manually install core packages:

pip install gradio transformers pypdf
▶️ Usage
Run the app locally:

python studymate.py
This will launch the Gradio interface at:

http://127.0.0.1:7860
Or access the hosted version: 🔗 StudyMate++ Live Demo

🎓 How It Works
Upload a PDF → Extracts text with pypdf.
Model Processing → Sends text prompts to IBM Granite model through Hugging Face’s Transformers pipeline.
Choose a Feature Tab → Summarization, Flashcards, Quizzes, or Debugging.
Get Results → View answers instantly in the Gradio interface.
📸 Screenshot of Interface
Screenshot 2025-09-20 110443
🌟 Future Improvements
✅ Implement RAG (Retrieval Augmented Generation) for better accuracy on large PDFs.
✅ Add support for multi-user sessions (instead of global PDF state).
✅ Enhance quiz generation with answer keys.
✅ Export flashcards/quizzes in CSV/Anki format.
👩‍💻 Team - Page2Podium!
Built with ❤️ for SmartInternz Hackathon 2025.

Priyadarshini R
Maruthiram M
Sriram R
