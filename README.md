# 🏠 Airbnb Multi-City Price Analysis

This project analyzes Airbnb listings from multiple cities, focusing on price differences by room type and geography. The goal is to understand how location and room type affect average prices and to visualize this data effectively.

## 📌 Project Objectives

- Compare Airbnb prices between different cities
- Analyze price variations across room types
- Visualize price distributions and geographic distributions
- Generate insights that could help hosts or travelers

## 📊 Key Features

- **Bar Charts**: Average price per room type per city
- **Box Plots**: Price distributions with outliers removed
- **Geographic Maps**: Latitude vs longitude scatter plots of listings
- **PDF Report**: Visual summary of findings
- **Jupyter Notebook**: Reproducible analysis and data visualizations

## 🧪 Technologies Used

- Python 3.x
- pandas
- numpy
- matplotlib
- seaborn
- Jupyter Notebook

## 📁 Project Structure

```
airbnb-multicity-price-analysis/
│
├── data/                             # Raw and cleaned datasets (CSV)
│   ├── listings_beijing.csv.gz
│   ├── listings_nyc.csv.gz
│   └── listings_sydney.csv.gz
│
├── notebooks/                        # Main analysis notebook
│   ├── testing.ipynb
│   └── analysis.ipynb
│
├── images/                           # Generated visualizations (PNG)
│   ├── Average_Price_by_City.png
│   ├── Average_Price_by_City_and_Room_Type.png
│   ├── Avg_price_Vs_Room_Type.png
│   ├── Geographic_Distribution.png
│   ├── Number_of_Listings_by_City.png
│   └── Price_Distribution_by_City.png
│
├── Airbnb_Analysis_Report.pdf        # Final PDF report with charts
├── LICENSE                           # License file (e.g., MIT)
├── README.md                         # Project documentation (this file)
└── requirements.txt                  # Python dependencies
```


## 🚀 Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/JohnnySiuky/airbnb-multicity-price-analysis.git
cd airbnb-multicity-price-analysis

```
### 2. Install dependencies
```
python -m venv .venv
source .venv/bin/activate    # On Windows: .venv\Scripts\activate
pip install -r requirements.txt

```
### 3. Run the analysis
```
jupyter notebook notebooks/analysis.ipynb

```

---

## 📄 License

This project is licensed under the terms of the [MIT License](./LICENSE).


