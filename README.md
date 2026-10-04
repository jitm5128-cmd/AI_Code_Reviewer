# 🤖 AI Code Reviewer

**AI Code Reviewer** is a Python-based intelligent code analysis application designed to help developers identify coding errors, code quality issues, security problems, and potential improvements automatically.

The system analyzes source code using **static code analysis, AST-based feature extraction, and Pylint**, and presents the review results through an interactive **Streamlit** interface.

## 🚀 Features

- 🔍 **Automated Code Review** – Analyze source code and identify common issues.
- 🐛 **Error Detection** – Detect syntax errors, coding mistakes, and potential problems.
- 📊 **Code Quality Analysis** – Evaluate code using static analysis techniques.
- 🌳 **AST-Based Analysis** – Extract structural features from Python source code using Abstract Syntax Trees.
- 🧹 **Pylint Integration** – Generate detailed code-quality and style warnings.
- 💡 **Improvement Suggestions** – Help developers understand and improve their code.
- 📈 **Review History** – Store previous code reviews using SQLite.
- 🖥️ **Interactive UI** – Simple and user-friendly interface built with Streamlit.
- ⚡ **Real-Time Analysis** – Review submitted code and display results instantly.

## 🛠️ Technologies Used

- **Python**
- **Streamlit**
- **Python AST**
- **Pylint**
- **SQLite**
- **Pandas**
- **HTML/CSS**
- **Git & GitHub**

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
├── review.db
├── requirements.txt
└── README.md
```

## ⚙️ How It Works

```text
User enters Python Code
        ↓
Code Preprocessing
        ↓
AST Feature Extraction
        ↓
Static Code Analysis
        ↓
Pylint Analysis
        ↓
Error & Quality Detection
        ↓
Review Results & Suggestions
```

## ▶️ Installation

Clone the repository:

```bash
git clone https://github.com/your-username/AI-Code-Reviewer.git
cd AI-Code-Reviewer
```

Install the required dependencies:

```bash
pip install -r requirements.txt
```

Run the application:

```bash
streamlit run app.py
```

The application will open in your browser.

## 🎯 Objective

The main objective of this project is to create an easy-to-use automated code review system that assists students and developers in finding errors, understanding code-quality issues, and writing cleaner and more maintainable Python code.

## 🔮 Future Enhancements

- Integration with advanced AI/LLM models
- Support for multiple programming languages
- Automatic code correction
- Code complexity visualization
- Security vulnerability detection
- AI-generated explanations for detected errors
- Code optimization recommendations
- Developer performance and review analytics

## 👨‍💻 Project Team

**MCA Project — Dr. B. C. Roy Engineering College, Durgapur**

Developed as an academic project to explore **AI-assisted software development and automated code analysis**.
