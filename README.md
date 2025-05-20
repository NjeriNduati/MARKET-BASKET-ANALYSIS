# 🛍️ Market Basket Analysis using Apriori Algorithm

This project performs market basket analysis on a retail transactions dataset using the Apriori algorithm. The goal is to uncover patterns and associations between items that are frequently bought together.

## 📂 Project Structure

- `data/` - Contains the dataset (e.g., transactions.csv)
- `apriori_analysis.ipynb` - Jupyter notebook with all steps from data cleaning to rule generation and visualization.
- `Apriori Rules Report.md` - Human-readable interpretation of the strongest rules.
- `Apriori Strategy Recommendations.md` - Analyst-friendly suggestions based on the insights.
- `visualizations/` - Contains generated plots and network graphs.

## 🔧 Tools Used

- Python 🐍
- pandas, matplotlib, seaborn
- apyori (for Apriori implementation)
- NetworkX (for visualizing rules)

## 💡 Key Highlights

- Identified strong item associations using support, confidence, and lift.
- Generated actionable business insights for promotions and shelf placement.
- Visualized rules using bar charts, scatter plots, and network graphs.

## 📈 Sample Rule Interpretation

> **Rule**: If a customer buys bottled water and berries, they’re likely to also buy pork, yogurt, pip fruit, and vegetables.  
> **Lift**: 14.65 → Very strong association.

