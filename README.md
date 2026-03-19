# Tech Layoffs 2026 — AI Job Cuts Tracker Analysis

**Author:** Taimoor Ali  
**Dataset:** Tech Layoffs 2026 | AI Job Cuts Tracker — Kaggle (alitaqishah)
**Tools:** Python, Pandas, Matplotlib, Seaborn, Plotly

---

## Overview

The tech industry is undergoing one of its biggest transformations in history.
Companies are cutting thousands of jobs while simultaneously investing billions
in Artificial Intelligence. This project analyses real 2026 layoff data from
28 major tech companies to uncover patterns, causes, and consequences of the
ongoing wave of AI-driven job cuts.

**Key question: Are companies replacing human workers with AI?**

---

## Key Findings

1. **Oracle and Amazon led the cuts** — Oracle eliminated 30,000 jobs and Amazon
   16,000 in early 2026, making them the two largest single layoff events.

2. **50% of layoffs were explicitly AI-driven** — exactly half of the 28 companies
   in the dataset cited AI adoption as a direct reason for reducing their workforce.

3. **Enterprise Software and Telecommunications** sectors suffered the highest
   total job losses across the dataset.

4. **Stock markets rewarded layoffs** — 17 out of 28 companies saw their stock
   price rise after announcing layoffs, showing investors view cuts as a sign
   of cost efficiency and AI investment.

5. **Higher AI investment correlates with more job cuts** — companies spending
   more on AI simultaneously cut more jobs, strongly suggesting AI is replacing
   rather than supplementing human roles.

---

## Charts Produced

| File | Description |
|------|-------------|
| `chart1_top_companies.png` | Top 10 companies by number of jobs cut, colour-coded by AI reason |
| `chart2_ai_vs_nonai.png` | Pie chart — share of total jobs lost to AI-driven vs non-AI layoffs |
| `chart3_jobs_by_sector.png` | Total jobs cut broken down by tech sector |
| `chart4_stock_reaction.png` | How stock markets reacted to each company's layoff announcement |
| `chart5_ai_investment_vs_jobs.png` | Scatter plot — AI investment amount vs jobs cut per company |

---

## How to Run

1. Clone this repository
2. Download the dataset from Kaggle:  
   https://www.kaggle.com/datasets/alitaqishah/tech-layoffs-2026-ai-job-cuts-tracker
3. Place `tech_layoffs_2026_tracker.csv` in the project folder
4. Install dependencies:
   ```bash
   pip install pandas matplotlib seaborn
   ```
5. Run the analysis:
   ```bash
   python analysis.py
   ```
   Or open `tech_layoffs_analysis.ipynb` in Jupyter Notebook.

---

## Dataset

- **Source:** [Tech Layoffs 2026 | AI Job Cuts Tracker — Kaggle](https://www.kaggle.com/datasets/alitaqishah/tech-layoffs-2026-ai-job-cuts-tracker)
- **Companies covered:** 28 major tech firms
- **Columns:** 26 (company, jobs cut, sector, AI cited, stock reaction, AI investment, etc.)
- **Time period:** January–March 2026

---

## Skills Demonstrated

- Loading and cleaning real-world data with **Pandas**
- Boolean filtering and group aggregations
- Multi-chart storytelling with **Matplotlib** and **Seaborn**
- Scatter plot correlation analysis
- Communicating data-driven insights on a current, high-impact topic

---

## Why This Project?

AI and automation are reshaping the global job market right now. As someone
preparing to study Data Science and AI at postgraduate level, I wanted to
analyse this transformation using real data — not just read about it. This
project sits at the intersection of data analysis and one of the most
important technological debates of our time.

---

*This project was built as part of my preparation for an MS in Data Science & AI.*  
*Contact: taimoorali5588@gmail.com*
