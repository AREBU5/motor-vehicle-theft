# 🚗 Motor Vehicle Theft Analysis - New Zealand

A comprehensive data analysis project examining **4,538 stolen vehicles** across New Zealand to identify temporal patterns, vehicle characteristics, and regional theft variations.

---

## 📊 Project Overview

This project analyzes motor vehicle theft data to answer critical business questions for law enforcement, insurance companies, and vehicle security providers. The analysis combines SQL queries with Python visualizations to uncover actionable insights.

---

## 🎯 Key Findings

### Temporal Patterns
- **Peak Theft Day:** Monday (767 thefts - 33% higher than Saturday)
- **Lowest Theft Day:** Saturday (577 thefts)
- **Insight:** Weekday parking patterns create more theft opportunities

### Vehicle Types Targeted
**Most Stolen:**
1. Stationwagon - 944 thefts (20.8%)
2. Saloon - 854 thefts (18.8%)
3. Hatchback - 645 thefts (14.2%)
4. Trailer - 582 thefts (12.8%)
5. Utility - 468 thefts (10.3%)

**Least Stolen:**
- Specialized vehicles (Articulated Trucks, Trail Bikes, Tractors) - <5 thefts each

### Vehicle Age Profile
- **Average Age of Stolen Vehicles:** 16 years
- **High-Risk Range:** 15-20 year old vehicles (weaker security systems)
- **Most Targeted:** Older Stationwagons, Saloons, and Hatchbacks

### Regional Analysis

**By Total Thefts:**
1. Auckland - 1,630 thefts (35.9%)
2. Canterbury - 660 thefts (14.5%)
3. Bay of Plenty - 445 thefts (9.8%)

**By Per Capita Rate (per 1,000 people):**
1. Gisborne - 3.36 per 1,000 (Highest Risk)
2. Nelson - 1.69 per 1,000
3. Bay of Plenty - 1.28 per 1,000
4. Southland - 0.25 per 1,000 (Lowest Risk)

---

## 📈 Visualizations

The analysis includes 5 comprehensive visualizations:

1. **Day of Week Theft Pattern** - Bar chart comparing Monday vs Saturday thefts
2. **Most & Least Stolen Vehicle Types** - Dual horizontal bar charts showing top 5 in each category
3. **Regional Vehicle Type Analysis** - Grouped bar chart showing top 3 stolen types by region
4. **Average Vehicle Age by Type** - Color-coded horizontal bars with overall average reference line
5. **Regional Analysis** - Dual-axis chart combining total thefts and per capita rates

---

## 🛠️ Technologies Used

- **SQL (Databricks SQL)** - Data querying and aggregation
- **Python** - Data analysis and visualization
  - `pandas` - Data manipulation
  - `matplotlib` - Chart creation
  - `PySpark` - Distributed data processing
- **Jupyter Notebook** - Interactive analysis environment
- **Databricks** - Cloud analytics platform

---

## 📁 Project Structure

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

---

## 💡 Business Recommendations

### For Law Enforcement
- Increase Monday patrols in business districts and commuter parking areas
- Focus resources on urban centers (Auckland, Canterbury) for volume
- Prioritize Gisborne for per capita intervention

### For Vehicle Owners
- Owners of 15-20 year old Stationwagons, Saloons, and Hatchbacks should upgrade security
- Install aftermarket immobilizers and GPS tracking on older vehicles
- Exercise extra caution on Monday mornings

### For Insurance Providers
- Adjust premiums based on vehicle age (15-20 years = higher risk)
- Regional risk tiers: Gisborne (highest) → Southland (lowest)
- Vehicle type risk profiles: Stationwagons > Saloons > Hatchbacks

---

## 📊 Dataset Summary

- **Total Vehicles Analyzed:** 4,538
- **Regions Covered:** 16 New Zealand regions
- **Vehicle Types:** 22 distinct classifications
- **Date Range:** Multi-year historical data

---

## 🚀 Getting Started

### Prerequisites
- Databricks account or local Jupyter environment
- Python 3.x with pandas, matplotlib
- Access to the motor vehicle theft dataset

### Running the Analysis
1. Clone this repository
2. Open `MOTOR_VEHICLE_THEFT.ipynb` in Databricks or Jupyter
3. Update database connection details (if needed)
4. Run all cells to reproduce analysis and visualizations

---

## 📝 License

This project is licensed under the MIT License - see the LICENSE file for details.

---

## 👤 Author

**Daniel Arebu**
- GitHub: [@AREBU5](https://github.com/AREBU5)

---

## 🙏 Acknowledgments

- New Zealand vehicle theft database
- Databricks community for analytics platform
- Law enforcement agencies for data collection efforts

---

## 📧 Contact

For questions, suggestions, or collaboration opportunities, please open an issue or reach out via GitHub.

---

**Last Updated:** August 2026
