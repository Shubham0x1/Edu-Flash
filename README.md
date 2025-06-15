# 📚 Edu-Flash: AI-Powered Flashcard Generator

Edu-Flash is a smart flashcard generator built with Python and Flask that uses Natural Language Processing (NLP) and Google's Gemini API to convert PDF files into intelligent flashcards for learning and revision.

---

## 🚀 Features

- 📄 Upload PDF files directly
- 🧠 Extracts and summarizes key content
- ✨ Generates flashcards using AI (Google Gemini API)
- 🔁 Flip cards for interactive review
- 🌐 Simple UI powered by Flask
- 🔍 Tokenizes text using NLTK

---

## 🛠️ Tech Stack

- **Frontend**: HTML, CSS, JavaScript
- **Backend**: Python 3.11+, Flask
- **Libraries**: NLTK, PyPDF2, Google Generative AI, python-dotenv

---

## 🖥️ Installation & Setup

### ✅ Clone the Repository

```bash
git clone https://github.com/Shubham0x1/Edu-Flash.git
cd Edu-Flash

### 🐍 Create and Activate Virtual Environment
python -m venv venv
venv\Scripts\activate   # Windows
# source venv/bin/activate   # macOS/Linux
📦 Install Required Packages
pip install -r requirements.txt
🔑 Set Up Environment Variables
Create a .env file in the project root and add your Gemini API key:
GOOGLE_API_KEY=your_gemini_api_key_here

🚦 Running the App
Once setup is complete, run the app using:
python app.py
Then open your browser and navigate to:
http://127.0.0.1:5000

📂 .gitignore
Create a .gitignore file and add the following to avoid committing unnecessary files:

markdown
Copy
Edit
venv/
__pycache__/
*.pyc
.env
.DS_Store
*.log
*.sqlite3
*.db
.idea/
.vscode/
node_modules/
*.pkl
📦 requirements.txt
Make sure this file is included to install dependencies. Here's the content:

ini
Copy
Edit
Flask==3.1.1
Flask-Cors==6.0.1
PyPDF2==3.0.1
nltk==3.9.1
google-generativeai==0.8.5
python-dotenv==1.1.0
requests==2.32.4
To generate this automatically:

bash
Copy
Edit
pip freeze > requirements.txt
🤝 Contributing
Pull requests are welcome. For major changes, open an issue first to discuss proposed updates.

📄 License
This project is licensed under the MIT License.

✨ Author
Made with ❤️ by Shubham Gusain
Let me know if you'd like a downloadable `.md` file or want to auto-generate this inside your repo using a scr
