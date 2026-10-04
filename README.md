# 🤖 AI Code Reviewer

AI Code Reviewer is a Python-based application that helps developers analyze and review Python source code automatically. The project uses Abstract Syntax Tree (AST) analysis and Pylint static analysis to identify syntax errors, coding issues, style problems, and other potential improvements.

The application provides an interactive interface using Streamlit, allowing users to enter or submit Python code and view the analysis results in an easy-to-understand format.

## 🚀 Features

- 🔍 Python Code Analysis – Analyze Python source code automatically.
- 🌳 AST-Based Feature Extraction – Extract structural information from Python code using the Abstract Syntax Tree.
- 🐛 Error Detection – Identify syntax and code-quality problems.
- 🧹 Pylint Static Analysis – Detect coding-style violations, warnings, and potential issues.
- 📊 Code Review Results – Display detected issues and analysis results through an interactive interface.
- 💾 Review History – Store code review information using SQLite.
- 🖥️ Streamlit Interface – Simple and interactive web-based interface.
- ⚡ Fast Analysis – Quickly analyze submitted Python code and display results.

## 🛠️ Technologies Used

- Python
- Streamlit
- Python AST
- Pylint
- SQLite
- Git & GitHub

## 🏗️ Project Structure

```text
AI-Code-Reviewer/
│
├── analyzer/
│   ├── features.py
│   └── static_analyzer.py
│
├── database/
│   └── db.py
│
├── app.py
├── requirements.txt
└── README.md
```

## 🔄 How It Works

```text
Python Code
     ↓
Code Input through Streamlit
     ↓
AST Feature Extraction
     ↓
Static Code Analysis
     ↓
Pylint Analysis
     ↓
Issues & Warnings Detection
     ↓
Review Results
     ↓
SQLite Database
```

## ⚙️ Installation

Clone the repository:

```bash
git clone https://github.com/your-username/AI-Code-Reviewer.git
```

Move into the project directory:

```bash
cd AI-Code-Reviewer
```

Install the required dependencies:

```bash
pip install -r requirements.txt
```

## ▶️ Run the Application

Start the Streamlit application using:

```bash
streamlit run app.py
```

The application will open in your web browser.

## 🎯 Project Objective

The main objective of this project is to develop an automated code-review system that helps programmers identify errors and code-quality issues without manually checking every part of their source code.

The project also demonstrates how **AST-based program analysis and static analysis tools such as Pylint** can be combined with a Streamlit interface to create a practical developer tool.

## 🔮 Future Enhancements

- 🤖 Integration with AI/LLM models for intelligent code explanations
- ✨ Automatic code correction
- 🌐 Support for additional programming languages
- 🔐 Advanced security vulnerability detection
- 📈 Code complexity and quality visualization
- 💡 AI-powered optimization suggestions
- 📋 Detailed code-review reports

## 👨‍💻 Project Team

MCA Project
Dr. B. C. Roy Engineering College, Durgapur

### Team Members

- Jit Mandal
- Akash Karmakar
- Ankan Pal

## 📌 Project Status

🚧 Under Development

The current version focuses on Python code analysis using AST and Pylint. Additional AI-powered features and improvements are planned for future versions.

