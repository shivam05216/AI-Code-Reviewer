# 🤖 AI Code Reviewer

An AI-powered code review application that helps developers analyze their source code and receive intelligent feedback, suggestions, and improvements using Google's Gemini AI.

## 🚀 Overview

AI Code Reviewer is a web application designed to make code review faster and more accessible.

Simply paste your code into the editor, click **Review**, and the application uses Gemini AI to analyze the code and provide useful feedback on:

- Code quality
- Bugs and potential issues
- Best practices
- Performance
- Security
- Readability
- Maintainability
- Code structure
- Reusability
- Possible improvements

The goal is to provide developers with an AI-assisted first-level code review before human review or production deployment.

## ✨ Features

- 🤖 AI-powered code analysis
- 📝 Interactive code editor
- 🔍 Automatic identification of code issues
- 💡 Intelligent improvement suggestions
- ⚡ Performance recommendations
- 🔐 Security-focused suggestions
- ♻️ Maintainability and reusability improvements
- 📚 Code documentation recommendations
- 💻 Clean and simple user interface
- 🎨 Syntax-highlighted code
- 📄 Structured AI-generated review
- 🔑 Secure API-key management using environment variables

## 🛠️ Tech Stack

### Frontend
- React
- Vite
- JavaScript
- Axios
- React Markdown
- PrismJS
- Highlight.js
- CSS

### Backend
- Node.js
- Express.js
- JavaScript
- CORS
- dotenv

### AI
- Google Gemini API

## 🖥️ Application Preview

The application provides a simple two-panel interface:

**Left Panel:**  
Enter or paste the source code you want to review.

**Right Panel:**  
View the AI-generated code review, including identified issues and recommended improvements.

## 🔄 How It Works
--- 

User

  ↓
  
Enter Source Code

  ↓
  
React Frontend

  ↓
  
Send Code to Backend

  ↓
  
Express API

  ↓
  
Gemini AI

  ↓
  
Analyze Source Code

  ↓
  
Generate Review

  ↓
  
Display Review

---

##💡 Example
- Input
function sum() {
    return 1 + 1;
}

AI Review

The application can identify problems such as:

- Hardcoded values
- Missing parameters
- Limited reusability
- Maintainability issues

And suggest an improved implementation such as:
function sum(a, b) {
    return a + b;
}

--- 

#🔮 Future Enhancements

- Support for multiple programming languages
- Code quality scoring
- Security vulnerability detection
- Performance scoring
- AI-generated refactored code
- Review history
- Downloadable review reports
- GitHub repository integration
- GitHub Pull Request code review
- Automated CI/CD code review
- Multiple AI model support
- User authentication
  
---
⚠️ Disclaimer

AI-generated code reviews are suggestions and may not always be completely accurate.

Developers should verify recommendations manually, especially for security-sensitive, performance-critical, and production applications.

---

👨‍💻 Author

Shivam T
GitHub:
https://github.com/shivam05216

⭐ Support
If you find this project useful, consider giving the repository a ⭐ on GitHub.

**Built with React, Node.js, Express, and Google Gemini AI.**
