<div style="font-family:'Times New Roman', Times, serif;">

# **Market Volatility Modeling: Copula-GARCH Framework**

## **Overview**

This project, presented at the **National Science Exhibition 2025 (_1st Place_)**, showcases advanced statistical modeling for financial markets.  
I implemented a **Copula-GARCH framework** to forecast market volatility using **Nifty Fifty ROC**, **global GPRD**, and **Baltic Dry Index** data, improving forecast accuracy by **15.8%** compared to baseline models.

---

## **Objectives**
- **Model market volatility** with multivariate dependencies.
- **Enhance forecasting accuracy** for financial risk analysis.

---

## **Methodology**

- **Data Collection**: Aggregated 24 years of **Nifty Fifty ROC**, **global GPRD**, and **Baltic Dry Index** data from reliable and correct sources.

- **Copula-GARCH Model**: Applied **GARCH** to model individual asset volatilities and **Copula functions** to capture dependencies, reducing forecast error by **15.8%**.

- **Evaluation**: Compared predictions against actuals using **RMSE** and **MAE** metrics.

---

## **Repository Structure**

- `code/copula_garch.py`: Data preprocessing, Copula-GARCH implementation, and evaluation.
- `data/`: Sample market data (e.g., *Nifty Fifty daily returns*).
- `results/`: Visualizations (e.g., *forecasted vs. actual volatility, Copula dependence plots*).
- `requirements.txt`: Dependencies (e.g., `numpy`, `arch`, `pandas`, `matplotlib`).

---

## **Results**

- Improved forecast accuracy by **15.8%** over traditional GARCH models across 5 years of market data.
- Secured **1st Place** among **10+ teams** at the *National Science Exhibition 2025*.

---

## **Usage**

**Install dependencies:**
```bash
pip install -r requirements.txt

python code/copula_garch.py



