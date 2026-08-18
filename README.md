# Motor Vehicle Theft Analysis - New Zealand

A comprehensive data analysis project examining **4,538 stolen vehicles** across New Zealand to identify temporal patterns, vehicle characteristics, and regional theft variations.

---

## Project Overview

This project analyzes motor vehicle theft data to answer critical business questions for law enforcement, insurance companies, and vehicle security providers. The analysis combines SQL queries with Python visualizations to uncover actionable insights.

---

## Technologies Used

- **SQL (Databricks SQL)** - Data querying and aggregation
- **Python** - Data analysis and visualization
  - `pandas` - Data manipulation
  - `matplotlib` - Chart creation
  - `PySpark` - Distributed data processing
- **Jupyter Notebook** - Interactive analysis environment
- **Databricks** - Cloud analytics platform

---

## Project Structure

```
motor-vehicle-theft/
│
├── MOTOR_VEHICLE_THEFT.ipynb    # Main analysis notebook with all queries and visualizations
├── README.md                     # This file
└── LICENSE                       # MIT License
```

---

## 🔍 Analysis Methodology

### Data Sources
The analysis uses three core tables:
- `stolen_vehicles` - Records of stolen vehicles with dates, types, and locations
- `make_details` - Vehicle make and model information
- `locations` - Regional data including population statistics

### Analytical Approach
1. **Data Cleaning** - Standardized vehicle type classifications
2. **Temporal Analysis** - Day-of-week patterns using window functions
3. **Vehicle Profiling** - Type, age, and characteristic analysis
4. **Regional Analysis** - Absolute counts and per capita normalization
5. **Visualization** - Custom matplotlib charts with multiple perspectives

##  Dataset Summary

- **Total Vehicles Analyzed:** 4,538
- **Regions Covered:** 16 New Zealand regions
- **Vehicle Types:** 22 distinct classifications
- **Date Range:** Multi-year historical data

### Running the Analysis
1. Clone this repository
2. Open `MOTOR_VEHICLE_THEFT.ipynb` in Databricks or Jupyter
3. Update database connection details (if needed)
4. Run all cells to reproduce analysis and visualizations

## Contact

For questions, suggestions, or collaboration opportunities, please open an issue or reach out via GitHub.
