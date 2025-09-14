# Airplane Crashes Analysis

Analyzing airplane crashes and fatalities worldwide since 1908 using Python.

## Project Overview

This project explores historical airplane crash data to extract insights about:

- Crashes per decade
- Fatalities vs survivors
- Top airlines and aircraft types involved in crashes
- Survival rate distribution
- Geographic distribution of crashes

The analysis is performed using **Python** libraries including **Pandas**, **Matplotlib**, **Seaborn**, and **Plotly**.

---

## Dataset

The dataset is publicly available and contains information on airplane crashes, including:

- Date and location of the crash
- Airline/operator
- Aircraft type
- Number of people aboard
- Number of fatalities

---

## Project Structure

Airplane-Crashes-Analysis/
│
├─ Airplane_Crashes_Analysis.ipynb # Main Colab/Jupyter notebook
├─ plots/ # Folder containing saved graphs (PNG)
├─ README.md # Project description (this file)
└─ requirements.txt # Required Python libraries


---

## Key Insights

- Aviation safety has improved over the decades, with a visible decline in crashes.
- Certain decades experienced significantly higher fatalities due to large accidents.
- Some operators and aircraft types appear more frequently in crash records.
- Survival rates vary widely depending on the crash circumstances.
- Geographic analysis shows crashes are distributed globally, with higher frequency in certain regions.

---

## Visualizations

**Crashes per Decade**  
![Crashes per Decade](plots/crashes_per_decade.png)

**Fatalities vs Survivors by Decade**  
![Fatalities vs Survivors](plots/fatalities_vs_survivors.png)

**Top Airlines with Most Crashes**  
![Top Operators](plots/top_operators.png)

**Top Aircraft Types in Crashes**  
![Top Aircraft Types](plots/top_aircraft_types.png)

**Survival Rate Distribution**  
![Survival Rate Distribution](plots/survival_rate_distribution.png)

**Interactive Global Distribution Map**  
*Displayed in the notebook using Plotly*

---

## Libraries Required

- pandas  
- matplotlib  
- seaborn  
- plotly  

Install them using:

```bash
pip install pandas matplotlib seaborn plotly


