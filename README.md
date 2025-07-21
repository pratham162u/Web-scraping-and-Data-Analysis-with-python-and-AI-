# 🧠 Web scraping and Data Analysis With AI and Python

An AI-powered tool that extracts, analyzes, and summarizes text from uploaded files or websites using Machine Learning and NLP.

---

## 🔍 Features

- 📄 Summarize large documents using BART Transformer
- 😊 Sentiment & subjectivity analysis using TextBlob
- 🔑 Extract keywords
- 🌐 Analyze any website with web scraping
- 🖼️ OCR from image files using Tesseract
- 📊 Visual word cloud + sentiment graph
- 💡 Supports:
  - PDF, DOCX, Excel, CSV, TXT
  - PNG, JPG, JPEG (image text)
  - URLs of any website

---

## 🚀 Getting Started

### 🔧 Prerequisites

- Python 3.10 or newer
- Install [Tesseract OCR](https://github.com/tesseract-ocr/tesseract)
  - Set its path in `file_handler.py` if needed.
    
---

**🚀 How to Run This Project :-**

**🔹 Step 1 : Clone this Repository :-**

git clone https://github.com/YOUR_USERNAME/ai-data-analyzer.git

cd ai-data-analyzer

**🔹 Step 2 : Install Required Libraries :-**

pip install -r requirements.txt

**⚠️ Make sure Python 3.10+ is installed and Tesseract OCR is properly configured in your system. :-**

**🔹 Step 3 : Run the App :-**

streamlit run app.py

---

**🔹 Technologies Used :-**

**🐍 Python 3.10**

**🌐 Streamlit –** for UI

**🤖 Transformers (BART) –** for summarization

**💬 TextBlob –** for sentiment analysis & keyword extraction

**📄 PyMuPDF –** PDF parsing

**🧠 pytesseract –** OCR for images

**🖼️ Pillow (PIL) –** Image processing

**🌍 BeautifulSoup4 –** Web scraping

**📊 Matplotlib & WordCloud –** Visualization

---

**📁 Project Structure**

**Web scraping and Data Analysis/**

├── **app.py**                       # Main Streamlit app

├── **requirements.txt**             # Dependencies

├── **README.md**                    # Documentation

├── **modules/**                     # Core logic

│   ├── **ai_analyzer.py**           # AI summarizer & sentiment analyzer

│   ├── **file_handler.py**          # Extracts data from different file types

│   ├── **visualizer.py**            # Graphs & wordcloud

│   └── **web_scraper.py**           # Scrapes text from websites

└── **assets/**                      # Screenshots (optional)


