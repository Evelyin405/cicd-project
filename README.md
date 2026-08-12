# Python CI/CD Project

A simple Python project demonstrating Continuous Integration (CI) using GitHub Actions.

## 📌 Project Overview

This project demonstrates how GitHub Actions can automatically test a Python application whenever new code is pushed to the `main` branch.

The CI pipeline installs Python and pytest, then automatically runs the test cases.

## 🛠️ Technologies Used

- Python
- Git
- GitHub
- GitHub Actions
- pytest
- VS Code
- WSL/Linux

## 📂 Project Structure

```text
cicd-project/
│
├── .github/
│   └── workflows/
│       └── ci.yml
│
├── app.py
├── test_app.py
├── .gitignore
└── README.md