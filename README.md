# assignment_2
Data-Driven Stock Analysis

**Stock Market Analysis Dashboard (Project 2)**

**Overview**

This project provides a complete stock market analysis pipeline using Python, MySQL (TiDB), Streamlit, and Power BI. It starts with transforming raw stock data (in YAML format) into structured CSV files, followed by multiple data analysis notebooks covering volatility, returns, sector performance, and more. The insights are then visualized through an interactive Streamlit dashboard and a Power BI report.

The goal is to help understand market trends, compare performance across sectors, and spot top gainers/losers over time.

---

**Steps Involved**

### 1. Data Preparation
- Convert raw stock data from YAML to structured CSV format using Python.

### 2. Data Analysis (Jupyter Notebooks)
- **Volatility Analysis**  
  Calculate standard deviation of daily returns to identify the most volatile stocks.
  
- **Cumulative Return Over Time**  
  Track performance trends of the top 5 performing stocks over time.

- **Sector-wise Performance**  
  Analyze and compare average yearly returns across sectors.

- **Stock Price Correlation**  
  Create a heatmap to understand correlation between different stock prices.

- **Top 5 Gainers and Losers (Month-wise)**  
  Identify monthly top and bottom performers based on return percentage.

### 3. Streamlit Dashboard
- An interactive dashboard (`streamlit.py`) displays:
  - Volatility Analysis
  - Cumulative Returns
  - Sector-wise Performance
  - Price Correlation
  - Top Gainers/Losers (filterable by month)

### 4. Power BI Visualization
- A `.pbix` report summarizes key insights in an easy-to-read format.

---

## Technologies Used

- **Python**, **Pandas**, **Seaborn**, **Matplotlib**
- **Jupyter Notebook**
- **Streamlit**
- **MySQL (TiDB Cloud)**
- **Power BI**

---

## How to Run the Streamlit App

1. Make sure all required Python packages are installed.
2. Set up database access in `streamlit.py` (update credentials and certificate path).
3. Run the app:

```bash
streamlit run streamlit.py

