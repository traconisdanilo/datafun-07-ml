# datafun-07-ml

Predictive Machine Learning Project
Foundations of Data Analytics – Module 7

Author: Danilo Traconis
Date: February 2026

---

## Project Overview

This project initializes a professional predictive machine learning workflow using:

- Python 3.14
- JupyterLab
- pandas
- numpy
- matplotlib
- seaborn
- scipy

The goal of this module is to begin building a structured ML project using professional development practices including Git, GitHub, virtual environments, and reproducible dependency management.

---

## Project Setup

This project uses `uv` to manage the virtual environment and dependencies.

### Commands Used

```powershell
cd C:\Repos
git clone https://github.com/traconisdanilo/datafun-07-ml
cd datafun-07-ml
code .

uv python pin 3.14
uv sync

.\.venv\Scripts\Activate

python -c "import numpy, pandas, pyarrow, matplotlib, seaborn, scipy; print('all imports ok')"

git add .
git commit -m "Initialize ML project"
git push


Save it.

Then run:

```powershell
git add README.md
git commit -m "Clean ML README"
git push
