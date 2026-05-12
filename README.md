# SGS Systems & Ops Hiring Dashboard

**Hiring Funnel Analytics Dashboard** for the Systems & Infrastructure role at **Sigma Growth Specialists**.

![Dashboard Preview](screenshot.png) <!-- Add a screenshot later for better impact -->

## 📋 Project Overview

This project analyzes the full hiring cycle for a Systems & Operations role. It processes candidate data from LinkedIn and Slack, visualizes the hiring funnel, and delivers clear insights on source effectiveness and assessment performance.

### Key Insights
- **39 candidates** analyzed (March 30 – April 28, 2026)
- **LinkedIn** performed better for **volume** and **Top Choice** candidates
- **Slack** delivered significantly higher **conversion rate** and **faster time-to-hire**
- **Trial Tasks** and **Interviews** were the strongest predictors of final offers

---

## 📊 Dashboard Highlights

- **Hiring Funnel** visualization
- Quality tier breakdown by source (Top Choice, Strong, Good)
- Assessment score comparison (Application → Trial Task → Interview)
- Source performance comparison (Volume vs Conversion vs Speed)
- Applications over time trend

---

## 📁 Files Included

| File | Description |
|------|-------------|
| `SGS_Hiring_Dashboard.pptx` | Final stakeholder-ready PowerPoint presentation |
| `SGS_Hiring_Dashboard.ipynb` | Complete Python analysis notebook (Colab) |
| `hiring_data.csv` | Raw candidate dataset |
| `README.md` | This file |

---

## 🛠️ Tools & Technologies

- **Python** (Pandas, Plotly)
- **Visualization**: Plotly Express + Graph Objects
- **Presentation**: Automated PowerPoint generation (`python-pptx`)
- **Environment**: Google Colab

---

## 🚀 How to Use

### Option 1: View the Presentation (Recommended)
1. Download `SGS_Hiring_Dashboard.pptx`
2. Open with Microsoft PowerPoint or Google Slides

### Option 2: Run the Analysis Yourself
1. Open the notebook in Google Colab
2. Upload the CSV file when prompted
3. Run all cells to regenerate charts and PowerPoint

### Option 3: Explore the Data
```python
import pandas as pd
df = pd.read_csv('hiring_data.csv')
df.head()
