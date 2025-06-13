# LLM-Powered Flashcard Generator

A modern web application that generates interactive flashcards from educational content using Google Gemini AI. The app supports editing, translation, structure detection, and question search—all in a beautiful, user-friendly interface.

## Features

- **AI-Powered Flashcard Generation:**
  - Uses Google Gemini (via the gemini-1.5-flash model) to generate high-quality flashcards from pasted text or uploaded PDF content.
- **Difficulty Levels:**
  - Each flashcard is tagged as Easy, Medium, or Hard.
- **Edit Before Export:**
  - Edit any flashcard (question, answer, difficulty, topic) in a smooth modal before exporting.
- **Multi-language Support:**
  - Instantly translate all flashcards to multiple languages (Hindi, Spanish, French, etc.) using Google Translate (via backend proxy).
- **Structure Detection:**
  - Automatically detects and groups flashcards by chapters, subheadings, or sections in your content.
- **Question Search:**
  - Type any question and get an answer from your pasted text or PDF using Gemini (even if the answer is not in a flashcard).
- **Export Options:**
  - Export flashcards as JSON, CSV, Anki, or TXT.
- **Responsive UI:**
  - Works beautifully on desktop and mobile.

## Demo PDF

A sample PDF file is included in this repository for testing:

- `APznzaZUdlapAFWUKFjr-5SnuYRG6kF2yZKssJDVbSPfPu3DM0l4x72p_yOKHEvc_TN7aMtuLit-RwulHzqllkfWqbdvNB-VxVVmEbEEkLv9orKDSKz_voCV6lmoy1mxCY-BXkTHXsBdVlxssw9uYgF1Mj5nu7vDh3S67AAXU3zSMpQQRtp8FkK07u1bY-0B9GUyPwsmaEYLt.pdf`

You can upload this PDF in the app to test flashcard generation and question search.

## Setup

1. **Clone the repository:**
   ```bash
   git clone <your-github-repo-url>
   cd <repo-directory>
   ```

2. **Install Python dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

3. **Set up your environment:**
   - Create a `.env` file in the root directory and add your Google Gemini API key:
     ```
     GOOGLE_API_KEY=your_google_gemini_api_key_here
     FLASK_ENV=development
     ```

4. **Start the Flask backend:**
   ```bash
   python app.py
   ```

5. **Open the app:**
   - Visit [http://localhost:5000](http://localhost:5000) in your browser.

## Usage

1. **Paste text or upload a PDF** to generate flashcards.
2. **Edit** any flashcard before exporting.
3. **Translate** flashcards to your preferred language.
4. **Search for answers** to your own questions from the content.
5. **Export** your flashcards in your desired format.

## How to Upload to GitHub

1. **Initialize a git repository (if not already):**
   ```bash
   git init
   ```
2. **Add all files:**
   ```bash
   git add .
   ```
3. **Commit your changes:**
   ```bash
   git commit -m "Initial commit: LLM-powered flashcard generator with Gemini, translation, and question search"
   ```
4. **Create a new repository on GitHub** and follow the instructions to push your local repo to GitHub:
   ```bash
   git remote add origin <your-github-repo-url>
   git branch -M main
   git push -u origin main
   ```

## Contributing

Contributions are welcome! Please open an issue or submit a pull request for improvements or new features.

## License

MIT License 