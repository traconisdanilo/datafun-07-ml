# datafun-07-ml

Predictive Machine Learning Project
Foundations of Data Analytics — Module 7

Author: Danilo Traconis
Date: February 2026

---

## Project Overview

This repository initializes a professional predictive machine learning workflow using:

- Python 3.14
- JupyterLab
- numpy
- pandas
- pyarrow
- matplotlib
- seaborn
- scipy

The purpose of this module is to build a structured ML project using:

- Git + GitHub version control
- A reproducible Python virtual environment
- Professional project organization
- A repeatable daily development workflow

---

## Repository Structure

```
datafun-07-ml/
│
├── README.md
├── pyproject.toml
├── uv.lock
├── .gitignore
├── .python-version
├── .venv/   (local only — not pushed to GitHub)
└── danilotraconis_ml.ipynb
```

---

## Quickstart (Windows / PowerShell)

### 1) Clone the repository and open in VS Code

```powershell
cd C:\Repos
git clone https://github.com/traconisdanilo/datafun-07-ml
cd datafun-07-ml
code .
```

### 2) Create the virtual environment and install dependencies (uv)

```powershell
uv python pin 3.14
uv sync
```

### 3) Activate the virtual environment

```powershell
.\.venv\Scripts\Activate
```

You should now see `(datafun-07-ml)` in your terminal.

### 4) Verify dependencies

```powershell
python -c "import numpy, pandas, pyarrow, matplotlib, seaborn, scipy; print('all imports ok')"
```

Expected output:

```
all imports ok
```

### 5) Start JupyterLab

```powershell
jupyter lab
```

Open:

```
danilotraconis_ml.ipynb
```

---

## Repeatable Daily Workflow

Use this every time you work on the project.

### Step 1 — Pull latest changes

```powershell
git pull
```

### Step 2 — Activate virtual environment

```powershell
.\.venv\Scripts\Activate
```

### Step 3 — Sync dependencies (if needed)

```powershell
uv sync
```

### Step 4 — Work

- Edit notebooks
- Run Jupyter cells
- Save files

### Step 5 — Save progress to GitHub

```powershell
git add -A
git commit -m "Update project work"
git push
```

---

## Commands Used (Project Setup Log)

```powershell
cd C:\Repos
git clone https://github.com/traconisdanilo/datafun-07-ml
cd datafun-07-ml
code .

uv python pin 3.14
uv sync

.\.venv\Scripts\Activate
python -c "import numpy, pandas, pyarrow, matplotlib, seaborn, scipy; print('all imports ok')"

git add -A
git commit -m "Initialize ML project"
git push
```

---

## Common Fixes

### If Jupyter does not detect the kernel

```powershell
uv add ipykernel
uv sync
```

Restart VS Code and re-select the `.venv` kernel.

### If Python commands fail in a new terminal

You probably forgot to activate the environment:

```powershell
.\.venv\Scripts\Activate
```

---

## Module 7 Goals

This repository will be used to:

- Build predictive machine learning models
- Explore datasets using pandas
- Visualize data using seaborn and matplotlib
- Evaluate model performance
- Document insights clearly using Jupyter notebooks
- Follow professional development workflow practices

---

## License

This project is for educational use as part of Foundations of Data Analytics.
