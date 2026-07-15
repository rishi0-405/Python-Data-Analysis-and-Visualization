# Multi-Domain Data Analysis & API Integration Workshop

A comprehensive data analytics and engineering project showcasing data manipulation, live API orchestration, data visualization, and financial market insights using Python.

## 🚀 Key Features

*   **IPL 2023 Final Match Analysis**: Complete retrospective breakdown and visualization of the historic CSK vs GT championship finale.
*   **Live Local Weather Tracker**: Real-time localized weather dashboard interacting directly with external weather engine endpoints.
*   **Pan-India State Capitals Weather Matrix**: Concurrent multi-city API pipeline pulling and organizing atmospheric data across every Indian state capital.
*   **Stock Market Analysis Engine**: Automated financial data retrieval, trend modeling, and OHLCV parsing leveraging the live **Alpha Vantage API**.

---

## 🛠️ Tech Stack & Dependencies

*   **Pandas**: Structured data manipulation, cleaning, and matrix alignment.
*   **Matplotlib & Seaborn**: Multi-variate charting, trend tracking, and exploratory visual analysis.
*   **Requests**: API orchestration, handling HTTP operations, and loading live JSON payloads.
*   **CSV**: Management of local configurations and parsing structural datasets.

---

## 📈 Financial Data Integration (Alpha Vantage)

The financial analysis section connects directly to the [Alpha Vantage Core Stock API](https://www.alphavantage.co/documentation/) to pull real-time or historical data. 
*   **Data Formats**: Ingested live JSON responses directly into structural **Pandas DataFrames**.
*   **Metrics Tracked**: Extracted historical price behaviors including Open, High, Low, Close, and Volume (OHLCV) records.

---

## 📁 Repository Structure

```text
├── 3-days-workshop.ipynb       # Main Python Data Analysis Notebook
├── datasets/                   # Static match-day metrics and cached data
└── README.md                   # Project documentation and setup guide
```

---

## ⚙️ How to Setup & Run

### 1. Clone the Repository
```bash
git clone https://github.com
cd Python-Data-Analysis-and-Visualization
```

### 2. Install Requirements
Ensure you have Python installed, then set up the essential analysis environment:
```bash
pip install pandas matplotlib seaborn requests
```

### 3. Alpha Vantage Configuration
To run the stock market script, request a free token from [Alpha Vantage Support](https://alphavantage.co) and insert it into your local environment:
```python
API_KEY = "YOUR_ALPHA_VANTAGE_KEY"
```

### 4. Execution
Launch Jupyter Notebook or click the **Open in Colab** badge at the top of the notebook file inside GitHub to run the data cells interactively.
