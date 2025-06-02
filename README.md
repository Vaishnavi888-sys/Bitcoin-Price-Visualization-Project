# Bitcoin-Price-Visualization-Project
📊 A Python-based visual analysis of Bitcoin’s price trends using pandas, matplotlib, and seaborn. Includes line plots, box plots, heatmaps, and more to uncover price patterns, volatility, and correlations in crypto data.

This project explores **Bitcoin’s historical price data** using Python. It focuses on uncovering patterns, volatility, and relationships between key financial metrics like Opening Price, Closing Price, High, Low, and Volume.  
Visualizations are built using **Matplotlib** and **Seaborn**, with clean explanations and interpretations.

## 📌 Objective

To perform an **exploratory data analysis (EDA)** and visualize trends in Bitcoin’s price over time.  
The goal is to:
- Understand price behavior and volatility
- Analyze relationships between price points
- Build compelling, insight-driven visuals

## 📂 Dataset

File: `cryptos.xlsx`  
Used only the **Bitcoin** sheet from the file.  
Columns used:
- `OpenPrice`: Opening price of Bitcoin for the day
- `HighPrice`: Highest price of the day
- `LowPrice`: Lowest price of the day
- `ClosePrice`: Closing price of the day
- `Volume`: Volume of transactions

## 🛠️ Technologies & Libraries

- Python 3.x
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook



## 📊 Visualizations Created

| Plot Type      | Purpose                                                       |
|----------------|---------------------------------------------------------------|
| Line Plot      | Visualize trends in Opening and Closing prices over time      |
| Area Chart     | Show momentum of Closing price visually                       |
| Histogram      | Display distribution of Closing prices                        |
| Box Plot       | Analyze volatility and detect price outliers                  |
| Heatmap        | Understand correlations among Open, High, Low, Close          |
| Scatter Plot   | Compare Opening vs. Closing prices to examine daily change    |


## 📍 Key Insights

- **High correlation** between Opening and Closing prices
- Bitcoin shows **frequent volatility**, as reflected in boxplots
- Volume does not always align with sharp price changes
- Strong **Open–Close alignment** implies intraday consistency


