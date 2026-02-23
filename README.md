# datafun-07-ml

Predictive Machine Learning Project
Foundations of Data Analytics — Module 7

**Author:** Danilo Traconis
**Date:** February 2026

---

## Project Overview

This repo is a starter setup for a predictive machine learning project using a professional workflow (Git/GitHub + reproducible Python environment + Jupyter).

**Tools / packages used:**
- Python 3.14
- JupyterLab
- numpy
- pandas
- pyarrow
- matplotlib
- seaborn
- scipy

---

## Repo Structure (what’s in here)

- `README.md` — setup + workflow notes (this file)
- `pyproject.toml` — project dependencies (managed by `uv`)
- `uv.lock` — exact dependency lock file (commit this)
- `.gitignore` — keeps `.venv/` and other local files out of GitHub
- `.venv/` — local virtual environment (should NOT be pushed)

---

## Quickstart (Windows / PowerShell)

### 1) Clone the repo + open in VS Code

```powershell
cd C:\Repos
git clone https://github.com/traconisdanilo/datafun-07-ml
cd datafun-07-ml
code .
2) Create the environment + install dependencies (uv)
uv python pin 3.14
uv sync
3) Activate the environment
.\.venv\Scripts\Activate
4) Quick dependency check
python -c "import numpy, pandas, pyarrow, matplotlib, seaborn, scipy; print('all imports ok')"
5) Start JupyterLab
jupyter lab
Repeatable Daily Workflow (do this every work session)
1) Pull latest changes
git pull
2) Activate the virtual environment
.\.venv\Scripts\Activate
3) Sync dependencies (only if something changed)
uv sync
4) Work (edit notebooks / files)

Open VS Code

Run Jupyter cells

Save your changes

5) Save progress to GitHub
git add -A
git commit -m "Update project work"
git push
Notes / Common Fixes
If Jupyter won’t run (missing kernel / ipykernel)

Run:

uv add ipykernel
uv sync

Then restart VS Code and re-select the kernel.

If you opened a new terminal and Python commands fail

You probably forgot to activate .venv:

.\.venv\Scripts\Activate
Commands I Used (project setup log)
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
