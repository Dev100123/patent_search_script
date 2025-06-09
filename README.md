# 🔎 Patent-Search-App-Using-Streamlit

## Introduction

This is a simple and interactive Patent Search Web Application built using Streamlit and powered by SerpAPI's Google Patents engine. It allows users to search for patents by entering a query, view detailed results, and download a Word report summarizing the findings.

---

## 🚀 Features

- 🔍 Search patents using natural language queries
- 📄 View patent details: title, summary, publication date, inventors, and assignees
- 📊 Summarize top inventors and assignees
- 📥 Download results as a formatted `.docx` report
- ⚡ Fast and user-friendly UI

  LINK TO THE APP: [CLICK HERE](https://patentsearchscript-n4ug3pqdwzas6sqzrme7mp.streamlit.app/)

## 🛠️ How to Run Locally

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/patent-search-app.git
cd patent-search-app
```

### 2. Install Dependencies

```bash
pip install -r requirements.txt
```

### 3. Set Up Environment Variables

Create a `.env` file in the root directory and add your SerpAPI key:

```bash
API=your_serpapi_key_here
```

You can get your free API key at [serpapi.com](https://serpapi.com/)

### 4. 🖥️ Run the Streamlit App

Finally, launch the web interface using Streamlit:

```bash
streamlit run main.py
```

## 📄 Output

You’ll get a Word document (.docx) report that includes:

- ✅ Query summary
- ✅ Top inventors and assignees
- ✅ Full patent details (title, abstract, publication date, etc.)

## 📄 License

This project is licensed under the [MIT License](https://opensource.org/licenses/MIT)
