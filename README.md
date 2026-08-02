# AI-Case-Summary-Generator
AI-powered legal case summarizer using Google Gemini API and Streamlit.
# ⚖️ AI Case Summary Generator

An AI-powered web application that transforms lengthy legal case documents into structured and easy-to-understand summaries using Google's Gemini AI.

Built with **Python**, **Streamlit**, and **Google Gemini API**, this tool helps lawyers, law students, researchers, and legal professionals quickly understand legal judgments.

---

## ✨ Features

- 📄 Generate AI-powered legal case summaries
- 📌 Extract important facts
- ⚖️ Identify legal issues
- 💬 Summarize arguments
- 👨‍⚖️ Display final court decision
- 🏷️ Extract keywords automatically
- 📥 Download summary as Markdown (.md)
- 🎨 Modern Streamlit interface

---

## 🛠️ Tech Stack

- Python
- Streamlit
- Google Gemini API
- python-dotenv

---

## 📂 Project Structure

```
AI-Case-Summary-Generator/
│
├── app.py
├── ai.py
├── prompts.py
├── requirements.txt
├── .env
├── README.md
└── assets/
```

---

## 🚀 Installation

### 1. Clone the repository

```bash
git clone https://github.com/yourusername/AI-Case-Summary-Generator.git

cd AI-Case-Summary-Generator
```

### 2. Create Virtual Environment

Windows

```bash
python -m venv venv
venv\Scripts\activate
```

Linux/Mac

```bash
python3 -m venv venv
source venv/bin/activate
```

### 3. Install Dependencies

```bash
pip install -r requirements.txt
```

---

## 🔑 Configure API Key

Create a `.env` file.

```env
GEMINI_API_KEY=YOUR_API_KEY
```

Get your API key from

https://aistudio.google.com/

---

## ▶️ Run the Project

```bash
streamlit run app.py
```

The application will open in your browser.

---

## 📋 How to Use

1. Paste the legal case or judgment text.
2. Enter your Gemini API key (or use the `.env` file).
3. Click **Generate Summary**.
4. Review the generated legal analysis.
5. Download the summary as a Markdown file.

---

## 📸 Output Includes

- Case Summary
- Important Facts
- Legal Issues
- Arguments
- Final Decision
- Keywords

---

## 🎯 Target Users

- Lawyers
- Law Students
- Legal Researchers
- Judiciary Aspirants
- Legal Professionals

---

## 📦 Future Improvements

- PDF Upload
- DOCX Upload
- OCR Support
- Indian IPC/BNS Section Detection
- Case Outcome Prediction
- Multi-language Support
- Export to PDF
- Citation Extraction

---

## 🤝 Contributing

Contributions are welcome!

Fork the repository and submit a pull request.

---

## 📄 License

This project is licensed under the MIT License.

---

## ⭐ Support

If you found this project helpful, please consider giving it a ⭐ on GitHub.
