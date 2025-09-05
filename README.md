

# Predicting Electricity Generation of the Eastern Mid-Atlantic Region of the U.S.

## Overview

This project develops a predictive model for electricity generation in the Eastern Mid-Atlantic region of the United States, specifically focusing on **Pennsylvania, New Jersey, and Delaware**. Accurate forecasts of electricity generation are crucial for energy planning, sustainability, and grid reliability.

We implemented a **Seasonal Autoregressive Integrated Moving Average with Exogenous Variables (SARIMAX)** model, trained on historical electricity generation data, and evaluated its forecasting accuracy.



## Key Features

* Data collected from the **U.S. Energy Information Administration (EIA) API**.
* Data preprocessing and transformation with **NumPy** and **Pandas**.
* Time-series forecasting using **SARIMAX** (via `statsmodels`).
* Model evaluation with **Mean Squared Error (MSE)**.
* Visualization of historical and predicted electricity generation using **Matplotlib**.
* Handles API schema changes and adapts the pipeline to new data formats.

---

## Tools & Libraries

* **Python 3.x**
* [NumPy](https://numpy.org/)
* [Pandas](https://pandas.pydata.org/)
* [Matplotlib](https://matplotlib.org/)
* [Statsmodels](https://www.statsmodels.org/)
* [itertools](https://docs.python.org/3/library/itertools.html)
* [JSON](https://docs.python.org/3/library/json.html)

---

## Project Structure

```
Predicting_Electricity_Generation_of_the_Eastern_Mid_Atlantic_Region_of_the_US.ipynb   # Main notebook
README.md                                                                              # Project documentation
```

---

## Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/<your-username>/electricity-generation-prediction.git
cd electricity-generation-prediction
```

### 2. Install dependencies

It’s recommended to use a virtual environment:

```bash
pip install -r requirements.txt
```

### 3. Run the Jupyter Notebook

```bash
jupyter notebook Predicting_Electricity_Generation_of_the_Eastern_Mid_Atlantic_Region_of_the_US.ipynb
```

---

## Results

* The SARIMAX model successfully captured seasonal trends in electricity generation.
* Performance was evaluated using **Mean Squared Error (MSE)**.
* Visualizations show close alignment between predicted and actual electricity generation across the region.

---

## Future Improvements

* Incorporating **weather, economic activity, and renewable energy adoption** as exogenous features.
* Experimenting with **LSTM/GRU neural networks** for long-term forecasting.
* Building a **dashboard (e.g., Plotly/Dash or Streamlit)** for interactive visualization.

---

## Authors

* **David Nwadiuko**
* **Elijah Iyamabhor**
