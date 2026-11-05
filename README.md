# 🚀 Full Stack Development – Learning Repository

A collection of my coding exercises, experiments, and mini-projects as I learn **Full Stack Development**.

The goal of this repository is to build practical skills, understand how different technologies work together, and create projects along the way.

## 🛠️ Technologies I'm Learning

| Category | Technologies |
|---|---|
| Backend | Python, FastAPI |
| Frontend | HTML, CSS, JavaScript |
| Full-Stack Frameworks | React, Next.js |
| Database | PostgreSQL, SQL |
| Caching | Redis |
| Tools | Git, GitHub, VS Code, WSL |

## 📂 Repository Structure

```text
Full-Stack-Learning/
│
├── Python/
├── FastAPI/
├── HTML-CSS-JS/
├── React/
├── NextJS/
│
├── .gitignore
└── README.md
```

*Each folder contains practice exercises, experiments, and mini-projects related to that technology.*

## 🎯 Learning Goals

- [ ] Strengthen Python fundamentals
- [ ] Build REST APIs using FastAPI
- [ ] Work with SQL and PostgreSQL
- [ ] Understand Redis and caching
- [ ] Master HTML, CSS and JavaScript fundamentals
- [ ] Build interactive applications using React
- [ ] Learn full-stack development with Next.js
- [ ] Integrate frontend and backend applications
- [ ] Build and deploy real-world projects

## 💡 Projects

This section will be updated as I build and complete new projects.

| Project | Technologies | Status |
|---|---|---|
| Coming soon... | — | 🔄 In Progress |

## 📈 Progress

Learning by building, experimenting, breaking things, and fixing things.

Every project is an opportunity to understand something new and improve my development skills.

---

## ⚙️ Getting Started

Follow these steps to clone the repository and run the projects locally.

### 1. Prerequisites

Install the following tools:

- [Git](https://git-scm.com/downloads)
- [Python 3.12+](https://www.python.org/downloads/)
- [uv – Python package manager](https://docs.astral.sh/uv/)
- [Node.js (LTS)](https://nodejs.org/)
- [PostgreSQL](https://www.postgresql.org/download/)
- [Redis](https://redis.io/downloads/)

You only need the tools required by the particular project you want to run.

### 2. Clone the repository

```bash
git clone https://github.com/YOUR-USERNAME/Full-Stack-Learning.git

cd Full-Stack-Learning
```

### 3. Run Python projects

Navigate to the Python project you want to run.

```bash
cd Python/your-project
```

Create and activate a virtual environment:

```bash
uv venv
```

Install dependencies:

```bash
uv sync
```

If the project doesn't have a `pyproject.toml` yet, initialize it with `uv init` and add its dependencies using `uv add`.

### 4. Run FastAPI projects

Navigate to the FastAPI project:

```bash
cd FastAPI/your-project
```

Install dependencies:

```bash
uv sync
```

Start the development server:

```bash
uv run uvicorn app.main:app --reload
```

Open the API documentation:

```text
http://127.0.0.1:8000/docs
```

The entry point may differ between projects; check their individual instructions.

### 5. Run React projects

Navigate to the React project:

```bash
cd React/your-project
```

Install dependencies:

```bash
npm install
```

Start the development server:

```bash
npm run dev
```

Open the local URL displayed in your terminal.

### 6. Run Next.js projects

Navigate to the Next.js project:

```bash
cd NextJS/your-project
```

Install dependencies:

```bash
npm install
```

Start the development server:

```bash
npm run dev
```

Open:

```text
http://localhost:3000
```

### 7. Run HTML, CSS and JavaScript projects

Navigate to the project folder and open `index.html` in your browser.

Alternatively, use the VS Code Live Server extension for automatic browser refresh.

### 📝 Important Notes

- Each project may have its own dependencies and setup instructions.
- Check the individual project folder for its `README.md` and configuration files.
- Create your own `.env` file using the provided `.env.example`, if available.
- Never commit API keys, passwords or other sensitive information.
- PostgreSQL and Redis must be running if a project requires them.

---

⭐ **Learning one concept at a time. Building one project at a time.**
