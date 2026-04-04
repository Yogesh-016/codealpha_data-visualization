# 📊 Data Visualization

A Python notebook that explores **Student Performance** data through a rich set of charts and plots using `matplotlib` and `seaborn`.

---

## 📁 Dataset

| File | Description |
|------|-------------|
| `StudentPerformance.csv` | Contains student-level records including study hours, sleep hours, previous scores, extracurricular activity participation, sample papers practiced, and a performance index. |

---

## 📦 Dependencies

```bash
pip install pandas matplotlib seaborn
```

| Library | Purpose |
|---------|---------|
| `pandas` | Loading and handling the dataset |
| `matplotlib` | Base plotting library |
| `seaborn` | High-level statistical visualizations |

---

## 📈 Visualizations

| # | Chart Type | X-axis | Y-axis | Insight |
|---|-----------|--------|--------|---------|
| 1 | Bar Chart | Extracurricular Activities | Performance Index | Impact of activities on performance |
| 2 | Line Chart | Student Index | Performance Index | Overall performance trend |
| 3 | Histogram | Performance Index | Frequency | Distribution of scores (with KDE) |
| 4 | Scatter Plot | Sleep Hours | Performance Index | Sleep vs performance relationship |
| 5 | Scatter Plot | Sample Question Papers Practiced | Performance Index | Practice vs performance relationship |
| 6 | Box Plot | — | Previous Scores | Spread and outliers in previous scores |
| 7 | Heatmap | — | — | Correlation between numerical features |

---

## 🚀 How to Run

1. Place `StudentPerformance.csv` in the same directory as the notebook.
2. Launch Jupyter:
   ```bash
   jupyter notebook Data_Visualization.ipynb
   ```
3. Run all cells (`Kernel → Restart & Run All`).

---

## 📂 File Structure

```
├── Data_Visualization.ipynb
└── StudentPerformance.csv
```

Author: Yogesh S
