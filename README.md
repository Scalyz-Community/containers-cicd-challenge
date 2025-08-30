# 🧩 Build Containers & CI/CD Pipelines with FastAPI

**Scalyz 30 Days Job-Ready Challenge — Chapter 3: Containers & CI/CD Pipelines**

---

## 📖 About This Assignment

This project is part of the **Scalyz 30 Days Job-Ready Challenge** — a public, community-driven assignment designed to push you beyond tutorials and into **real engineering work**.

All submissions are **public**.

- **Approved solutions** are **tagged** in the repository.
- **Current work** is visible in **open Pull Requests** with active discussions.

**Your role:** behave like a professional engineer — read existing discussions, learn from others, contribute ideas, and deliver your own solution.

---

## 💬 How to Participate

1. **Read ongoing discussions** in existing Pull Requests.
2. **Create issues** if you need help or spot potential improvements.
3. Ask for guidance **directly in the Scalyz community** or by commenting on PRs.
4. Submit your solution via Pull Request for review.

> 💡 This is a **public community assignment**.  
> The goal is for you to **experience the full engineering workflow**: coding, containerizing, automating pipelines, collaborating, and proving — to yourself and to others — that you can do the job.

---

## 📝 Assignment Title

**Mission:** Build and containerize a simple FastAPI backend app with authentication and PostgreSQL, write unit tests, and set up a CI/CD pipeline using GitHub Actions.

---

## 🎯 Problem Statement

Your client is launching a backend service that must be **reliable, testable, and deployable**.  
They want a small **FastAPI application with authentication**, backed by a **PostgreSQL database**, containerized with Docker & Compose, and shipped automatically via a **CI/CD pipeline**.

This is exactly what most of companies expect from engineers in modern projects.

---

## ✅ Requirements

Your solution must:

- Implement a FastAPI app (`/signup` and `/login` routes).
- Write at least **two unit tests** for the app.
- Containerize the app with a `Dockerfile`.
- Use `docker-compose.yml` to run the app with PostgreSQL.
- Store DB connection info via environment variables.
- Add a GitHub Actions workflow (`ci.yml`) that:
  - Installs dependencies.
  - Runs unit tests.
  - Builds the Docker image.
  - Runs containers (FastAPI + Postgres).
- Ensure **secrets are not hardcoded** in the code or workflow.
- Document all steps in `README.md`.

---

## 📦 Structure

You will work inside the provided repo structure:

```

containers-cicd-challenge/
├── app/
│   ├── main.py
│   ├── requirements.txt
│   └── tests/
│       └── test\_app.py
├── docker/
│   ├── Dockerfile
│   └── docker-compose.yml
├── .github/
│   └── workflows/
│       └── ci.yml
├── docs/
│   └── decision-log.md
└── README.md

```

---

## ⚙️ Constraints

- Use Python 3.10+ and FastAPI.
- PostgreSQL via Docker Compose.
- No secrets committed to code (use environment variables).
- Pipeline must run **headless** (no manual prompts).
- A fresh clone + `docker-compose up` must work without extra steps.

---

## 🔍 Evaluation Process

1. Submit a Pull Request to this repository.
2. **GitHub Actions** will:
   - Run lint checks and unit tests.
   - Build the Docker image.
   - Start containers via Compose.
3. **Community Review**:
   - At least 2 peers review your PR.
   - Feedback focuses on code quality, containerization best practices, CI/CD correctness, and security.
4. **Approval & Tagging**:
   - Approved PRs are tagged and merged into the main branch.

---

## 📌 Tips for Success

- Review existing PRs before starting — you’ll learn faster.
- Keep commits small and descriptive.
- Document your design choices in `docs/decision-log.md`.
- Ask questions in the Scalyz community.
- Remember: this is about **building the habit** of shipping professional-grade work.

---

## 🚀 Your Next Step

- Fork the repo:
  ```bash
  git clone https://github.com/scalyz-community/containers-cicd-challenge.git
  ```

* Work on your solution locally.
* Submit your PR when ready.

Let’s see what you can build.
Prove it — to the community, to future employers, and to yourself.

---

**— Scalyz Community**
_Engineer. Collaborate. Deliver._

---

## ✅ Pre-Submission Checklist

Before you open a Pull Request, confirm that you have completed all items below.
**Tip:** Copy this checklist into your PR description and tick each item.

### 🔹 Functional Requirements

- [ ] FastAPI app with `/signup` and `/login` routes implemented.
- [ ] At least 2 unit tests written and passing.
- [ ] Dockerfile builds the app image successfully.
- [ ] docker-compose runs app + Postgres together.
- [ ] GitHub Actions workflow runs tests and builds the image.
- [ ] Secrets stored via environment variables (not hardcoded).

### 🔹 Code Quality & Structure

- [ ] Repo structure matches provided scaffolding.
- [ ] Code is modular and documented.
- [ ] Tests are clear and reproducible.
- [ ] No unused files or dependencies.

### 🔹 Documentation

- [ ] `README.md` includes setup and execution instructions.
- [ ] `docs/decision-log.md` explains tool choices and design decisions.
- [ ] Environment variables and ports are documented.

### 🔹 Git & Collaboration

- [ ] Commits are small and descriptive.
- [ ] Branch name is descriptive (e.g., `feature/fastapi-auth`).
- [ ] I have reviewed at least one existing PR in the repository.
- [ ] I am ready to respond to reviewer feedback in the PR discussion.

---

**Reminder:** This is a public community assignment.
Approved solutions will be tagged and remain visible as part of your **public engineering portfolio**.
