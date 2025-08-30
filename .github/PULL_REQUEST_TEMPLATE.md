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
