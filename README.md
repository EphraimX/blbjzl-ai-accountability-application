# AI Accountability Application (GitHub Actions CI/CD)

This repository contains a simple full-stack web application designed for DevOps projects and demonstrations. It showcases CI/CD best practices using **GitHub Actions** for pipeline automation.

## 🛠 Project Structure

```
blbjzl-ai-accountability-application/
├── backend/           # FastAPI service
├── frontend/          # React app
├── .github/
│   └── workflows/     # GitHub Actions workflows
├── gitpod.yml         # Gitpod environment configuration
├── README.md
```

## 🚀 GitHub Actions CI/CD
This project utilizes GitHub Actions to automate the build, test, and deployment processes.
The workflows are defined in the `.github/workflows/` directory and include steps such as:

- Installing backend and frontend dependencies.
- Building and deploying both services

These workflows enable automation of the full build-test-deploy lifecycle.

## 🧪 Tech Stack

- **Frontend:** React (TypeScript)
- **Backend:** FastAPI (Python)
- **CI/CD:** GitHub Actions
- **Dev Environment:** Gitpod

## 📦 Setup
1. Clone the repository:
   ```bash
   git clone https://github.com/EphraimX/blbjzl-ai-accountability-application-github-actions.git
   ```

2. Navigate to `backend/` and install Python dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Navigate to `frontend/` and install Node packages:
   ```bash
   npm install
   ```

4. You can run both services locally or rely on GitHub Actions for automated deployment.

## 📌 Note

This project serves as a base for testing and deploying AI-related applications with accountability measures using GitHub Actions.
