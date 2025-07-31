# ☕ Coffee Quality Analysis using Python

Explore the factors that influence global coffee quality using real-world cupping data from professional graders. This project focuses on uncovering insights through exploratory data analysis (EDA), visual storytelling, and statistical testing — all powered by Python.

---

## 🔍 Project Overview

This project analyzes a coffee quality dataset with over **1,300 samples and 44 attributes**, including:

- Origin details (country, region, farm)
- Bean characteristics (species, processing method, variety, color)
- Sensory scores (aroma, flavor, aftertaste, acidity, body, balance, sweetness, etc.)
- Defect counts and grading timeline

The objective is to understand which variables contribute to higher coffee quality and how they vary across countries, species, and years.

---

## ⚙️ Tech Stack

| Tool       | Purpose                         |
|------------|---------------------------------|
| Python 3   | Programming language            |
| Jupyter    | Notebook-based development      |
| pandas     | Data cleaning & transformation  |
| seaborn    | Statistical plotting             |
| matplotlib | Visualizations                  |
| Power BI / Excel | Optional dashboarding     |

---

## 📊 Key Features

- ✅ Cleaned and preprocessed 44-column raw data
- 📈 Univariate, bivariate, and multivariate EDA
- 🔍 Correlation matrix & heatmap
- 🧪 Hypothesis testing (T-Test and ANOVA)
- 🌐 Country, species, and processing method insights
- 📉 Time-based trends in cup scores

---

## 📁 Folder Structure

coffee-quality-analysis/
├── Coffee_Data.csv # Original dataset
├── Milestone3.ipynb # Main Jupyter Notebook
├── Coffee_Quality_Report.pdf # Polished report with insights
├── CoffeeDashboard.xlsx # Optional Excel dashboard
├── images/ # Visuals folder (add charts/screenshots here)
├── LICENSE # MIT license
└── README.md # This file

---

## 🧠 Sample Insights

- **Arabica beans** dominate the dataset and outperform **Robusta** in quality.
- **Washed/Wet** processing is the most widely adopted and preferred method.
- **Top countries** by average cup score: Papua New Guinea, Ethiopia, Japan.
- **Bag count ≠ quality** — large farms don’t always produce the best coffee.
- **Aroma, Flavor, Aftertaste** show the strongest positive correlation with cup score.
- Most **high-quality beans** are grown between **1200–2000 meters**.
- **Coffee quality peaked around 2009**, dipped in 2011, and has gradually recovered.

---

## 🧪 Hypothesis Testing Summary

| Test                         | Purpose                                      | Result                            |
|------------------------------|----------------------------------------------|-----------------------------------|
| T-Test (Arabica vs Robusta) | Do species differ in quality?                | ✅ Arabica scores significantly higher |
| ANOVA (Variety vs Defects)  | Do some varieties have more defects?         | ✅ Yes, some vary significantly     |
| ANOVA (Country vs Cup Score)| Does country of origin affect quality?       | ✅ Strong influence confirmed       |

---

## ✅ Conclusion

This project successfully explored global coffee quality using Python, analyzing key factors that influence cup scores such as:

- Bean species, especially Arabica vs Robusta
- Processing methods (Washed/Wet, Natural, Honey)
- Sensory attributes (Aroma, Flavor, Aftertaste, etc.)
- Defect rates and their impact on total scores
- Country of origin, harvest year, and altitude effects

📌 **Key Takeaways:**
- **Arabica** consistently outperforms Robusta in both quality and popularity.
- **Washed/Wet processing** is the most trusted method worldwide.
- **Papua New Guinea, Ethiopia, and Japan** produce some of the highest-scoring coffees.
- **Aroma, Flavor, and Aftertaste** are the strongest indicators of cup quality.
- **Volume doesn’t always mean quality** — small farms often deliver excellent coffee.
- **Coffee quality trends fluctuate over time**, with a noticeable peak in 2009.

🔮 **Future Possibilities:**
- Predictive modeling (e.g., cup score prediction)
- Farm-level performance tracking
- Environmental factor analysis (e.g., rainfall, temperature, soil)
- Real-time dashboards for producers and quality control teams

This project demonstrates how data analysis can bring clarity and actionable insights to even the most aromatic industry: **coffee** ☕.

---

