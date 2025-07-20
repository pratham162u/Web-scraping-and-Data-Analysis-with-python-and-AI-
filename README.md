# Web-scraping-and-Data-Analysis-with-python-and-AI-
# 🧠 AI Data Analyzer

An AI-powered tool that extracts, summarizes, and analyzes text from uploaded files and websites using Machine Learning and Natural Language Processing.

---

## ✨ Features

- 📄 Summarize large documents using HuggingFace Transformers
- 😊 Sentiment & subjectivity analysis (TextBlob)
- 🔑 Extract top keywords
- 🌐 Web scraping for any website
- 🖼️ Word cloud + 📊 sentiment graph
- 🔍 Supports:
  - PDF
  - DOCX (Word)
  - Excel (XLSX)
  - CSV
  - TXT
  - Images (via Tesseract OCR)
  - Any Website (via URL input)

---

## 🚀 How to Run Locally
Step 1: Clone this Repository

```bash
git clone https://github.com/YOUR_USERNAME/ai-data-analyzer.git
cd ai-data-analyzer

Step 2: Install Required Libraries

pip install -r requirements.txt
✅ Make sure Tesseract OCR is installed, and path is set in file_handler.py

Step 3: Run the App

streamlit run app.py

Visit: http://localhost:8501

Project Structure:-
ai_data_analyzer/
│
├── app.py
├── requirements.txt
├── modules/
│   ├── ai_analyzer.py
│   ├── file_handler.py
│   ├── visualizer.py
│   └── web_scraper.py
└── README.md


Technologies Used
Streamlit
TextBlob
Transformers
PyMuPDF (PDF reading)
Pytesseract
BeautifulSoup
Matplotlib
WordCloud

