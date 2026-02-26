# DATA6550-Visualization (Group Project 3)

This repository contains our work for **DATA 6550 — Group Project 3: Visualization**.  
We use the **Titanic dataset** to create **2 ethical ("good")** and **2 intentionally misleading ("bad")** visualizations, along with EDA, collaboration summaries, and a final report.

---

## Team Members
- **Ali (Momina)**
- **Yadlapalli**
- **Hallikeri**


---

## Project Objectives
1. Perform **EDA (Exploratory Data Analysis)** on the dataset.
2. Create **2 GOOD visualizations** that are accurate, clear, and ethical.
3. Create **2 BAD visualizations** that are intentionally misleading (and explain why they are misleading).
4. Maintain collaboration evidence (meeting summaries) in the repo.
5. Submit a **final report** and a **presentation** (per course instructions).

---

## Dataset

We used the **Titanic dataset**.

**Files (stored in `Data/titanic/`):**
- `train.csv` — primary dataset used for EDA and visualizations
- `test.csv` — provided for completeness
- `gender_submission.csv` — example submission file from Kaggle

**Key columns used:**
- `Survived` (0/1)
- `Sex`
- `Pclass` (1, 2, 3)
- `Age` (missing values filled with median for EDA/plots)
- `Fare` (skewed distribution)
- `Embarked` (missing values filled with mode)

---

## Repository Structure

```
DATA6550-Visualization/
├── final_report.pdf
├── README.md
├── Code/
│   ├── Ali/
│   ├── Yadlapalli/
│   └── Hallikeri/
├── Data/
│   └── titanic/
│       ├── train.csv
│       ├── test.csv
│       └── gender_submission.csv
├── Collaboration/
│   ├── WeekA.pdf
│   └── WeekB.pdf
└── Analysis/
    └── (saved charts, intermediate outputs)
```

### Folder Notes
- **Code/** — Individual work folders. Each member places their notebook/script here.
- **Data/** — Dataset files used for the project.
- **Collaboration/** — AI-generated meeting summaries (required).
- **Analysis/** — Output figures (PNG) and intermediate artifacts.
- **final_report.pdf** — Final project report (uploaded to GitHub and D2L).
- **README.md** — This file.

---

## How to Run the Code

### Option A — Google Colab (Recommended)
1. Open the notebook from your member folder, e.g. `Code/Ali/<notebook>.ipynb`
2. Upload `train.csv` in Colab, or load from `Data/titanic/train.csv` if you've cloned the repo.
3. Run all cells in order.

### Option B — Local Python (Mac / Linux / Windows)

1. Clone the repository:
```bash
git clone https://github.com/MominaLAli/DATA6550-Visualization.git
cd DATA6550-Visualization
```

2. Create a virtual environment (optional but recommended):
```bash
python -m venv venv
source venv/bin/activate        # Mac/Linux
# venv\Scripts\activate         # Windows
```

3. Install dependencies:
```bash
pip install pandas numpy matplotlib seaborn
```

4. Run scripts or notebooks inside `Code/<Lastname>/`

---

## Dependencies

| Package | Purpose |
|---|---|
| `pandas` | Data loading and manipulation |
| `numpy` | Numerical operations |
| `matplotlib` | Base plotting |
| `seaborn` | Statistical visualizations |

---

## Visualizations Summary

| # | Type | 
|---|---|
| 1 | ✅ Good |
| 2 | ✅ Good | 
| 3 | ❌ Bad (Misleading) | 
| 4 | ❌ Bad (Misleading) | 


---

## Notes
- Most of the code was developed and tested in Google Colab.
- Missing values in `Age` were filled with the **median**; missing values in `Embarked` were filled with the **mode**.
- The bad visualizations are intentionally misleading for academic/educational purposes and include explanations of why they mislead the reader.


