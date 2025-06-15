
# Google Trends Data Visualization

This project explores the relationship between Google search trends and key economic indicators using data visualization and basic data analysis techniques.

## 📊 Overview

The goal of this project is to investigate whether search interest in certain keywords (like "Bitcoin", "Tesla", or "Unemployment Benefits") correlates with real-world economic indicators such as:

- **Bitcoin price movements**
- **Tesla stock interest**
- **U.S. Unemployment rate**

By combining public Google Trends data with economic datasets, we aim to answer questions like:

- Do spikes in search interest predict market trends?
- Can public sentiment (via search behavior) serve as a leading indicator for economic change?

## 🧪 Data Sources

- **Google Trends Data**:
  - Bitcoin search interest
  - Tesla search interest
  - Unemployment Benefits search interest

- **Economic Indicators**:
  - Daily Bitcoin Price (`Daily Bitcoin Price.csv`)
  - Tesla Stock Price (`TESLA Search Trend vs Price.csv`)
  - U.S. Unemployment Rate (`UE Benefits Search vs UE Rate 2004-19.csv`, `UE Benefits Search vs UE Rate 2004-20.csv`)

## 📂 Files Included

| Filename                                | Description                                 |
|----------------------------------------|---------------------------------------------|
| `Google Trends Data Visualisation.ipynb` | Jupyter Notebook with all analyses & charts |
| `Bitcoin Search Trend.csv`              | Weekly Bitcoin search interest              |
| `Daily Bitcoin Price.csv`               | Historical Bitcoin prices                   |
| `TESLA Search Trend vs Price.csv`       | Tesla search trend + stock price            |
| `UE Benefits Search vs UE Rate 2004-19.csv` | Search trends vs UE rate (2004–2019)     |
| `UE Benefits Search vs UE Rate 2004-20.csv` | Search trends vs UE rate (2004–2020)     |

## 📈 Visualizations & Analysis

The notebook includes:

- Trend comparison plots
- Correlation heatmaps
- Time series alignment
- Commentary on patterns & anomalies

## 🛠️ Technologies Used

- Python
- Jupyter Notebook
- pandas, matplotlib, seaborn
- Google Trends data (via manual CSV export)

## 🔍 Key Insights

- Bitcoin search interest often spikes during price surges.
- Tesla's public sentiment (via search) shows some alignment with stock movement.
- During the 2008 crisis and COVID-19 pandemic, spikes in unemployment-related searches preceded official rate increases.

## 🚀 How to Use

1. Clone the repository.
2. Open `Google Trends Data Visualisation.ipynb` in Jupyter.
3. Run all cells to view the analysis.
4. Modify or add datasets to expand the research.

```bash
git clone https://github.com/sahilsable-24/google-trends-viz.git
cd google-trends-viz
jupyter notebook
```

## 📌 Future Work

- Incorporate real-time Google Trends API for live tracking
- Apply machine learning models to forecast trends
- Expand analysis to more economic indicators

## 📄 License

This project is open-source under the MIT License.

