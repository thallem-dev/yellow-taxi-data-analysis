# Yellow Taxi Trip Data Analysis

## Project Overview
This project analyzes the **NYC Yellow Taxi January 2025 trip dataset** using Python. It covers data inspection, cleaning, feature engineering, exploratory analysis, statistical analysis, visualization, route analysis, business insights, limitations, and conclusions.

## Key Findings
- Average trip distance: **3.24 miles**
- Median trip distance: **1.62 miles**
- Average trip duration: **15.10 minutes**
- Median trip duration: **11.35 minutes**
- Average speed: **11.67 mph**
- Busiest pickup hour: **5 PM**
- Busiest day: **Thursday**
- Most common passenger count: **1**
- Most common payment type: **1**
- Most common pickup location: **237**
- Most common drop-off location: **236**
- Most frequently travelled route: **237 → 236**
- Final cleaned dataset: **2,871,273 trips**

## Analysis Areas
1. Data Loading & Inspection
2. Data Cleaning
3. Feature Engineering
4. Univariate Analysis
5. Time-Based Analysis
6. Trip Distance & Duration Analysis
7. Passenger Analysis
8. Pickup & Drop-off Analysis
9. Route Analysis
10. Payment Type Analysis
11. Vendor Analysis
12. Rate Code Analysis
13. Store-and-Forward Analysis
14. NumPy Statistical Analysis
15. IQR Outlier Analysis
16. Correlation Analysis
17. Advanced Analysis
18. Business / Operational Insights
19. Limitations
20. Final Conclusion

## Business / Operational Insights
The analysis shows that taxi demand is concentrated around specific hours, locations, and routes. These patterns can support peak-hour vehicle allocation, driver scheduling, high-demand location coverage, route planning, and service availability planning.

## Data Quality
The analysis identified invalid distances, invalid passenger counts, zero-duration trips, drop-off times before pickup times, extreme distances and durations, unusual calculated speeds, and missing or unusual values. Outliers were investigated rather than automatically treating every unusual value as invalid.

## Limitations
The analysis is based on one month of taxi data and does not include detailed traffic, weather, driver availability, or special-event information. Therefore, the findings describe observed patterns in the available data rather than definitive predictions of future demand.

## Tools & Technologies
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook / Google Colab

## Repository Structure
```text
yellow-taxi-data-analysis/
├── yellow_taxi_analysis.ipynb
├── README.md
├── requirements.txt
├── .gitignore
└── data/
    └── README.md
```

## Dataset
The project uses the **NYC Yellow Taxi January 2025** trip dataset. The raw Parquet file is not included because of its large size.

Expected file: `yellow_tripdata_2025-01.parquet`

## How to Run
```bash
pip install -r requirements.txt
```
Then open `yellow_taxi_analysis.ipynb` and run the notebook from top to bottom after placing the dataset at the required path.

## Project Outcome
This project demonstrates practical skills in **data cleaning, feature engineering, exploratory data analysis, statistical analysis, visualization, outlier investigation, and business interpretation** using a large real-world taxi dataset.
