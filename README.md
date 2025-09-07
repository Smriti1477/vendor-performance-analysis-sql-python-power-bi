# Vendor Performance Analysis with SQL, Python & Power BI

## Project Overview

This project demonstrates a comprehensive approach to vendor performance analysis using SQL, Python, and Power BI. The objective is to evaluate vendor efficiency, identify quality issues, and provide actionable insights for procurement and supply chain optimization.

## Technologies Used

* **SQL**: Data extraction and transformation from relational databases.
* **Python**: Data cleaning, analysis, and report generation.
* **Power BI**: Interactive dashboards and visualizations for data presentation.

##  Project Structure

```
/vendor-performance-analysis-sql-python-power-bi
│
├── ingestion_db.py              # Script for database connection and data ingestion
├── get_vendor_summary.py        # Python script for vendor performance analysis
├── Exploratory Data Analysis.ipynb  # Jupyter notebook for initial data exploration
├── Vendor Performance Report.pdf     # PDF report summarizing findings
├── vendor_performance.pbix      # Power BI dashboard file
└── Dashboard Image.png          # Screenshot of the Power BI dashboard
```

##  Getting Started

### Prerequisites

* **Python 3.x**: Ensure Python is installed on your system.

* **Required Libraries**: Install necessary Python libraries using pip:

  ```bash
  pip install pandas matplotlib seaborn
  ```

* **Power BI Desktop**: Required to open and interact with the `.pbix` file.

### Setup

1. Clone the repository:

   ```bash
   git clone https://github.com/Smriti1477/vendor-performance-analysis-sql-python-power-bi.git
   cd vendor-performance-analysis-sql-python-power-bi
   ```

2. Run the Python scripts to analyze vendor data:

   ```bash
   python get_vendor_summary.py
   ```

3. Open the Power BI dashboard:

   * Launch Power BI Desktop.
   * Open the `vendor_performance.pbix` file.

##  Project Highlights

* **SQL**: Efficient data extraction and transformation from relational databases.
* **Python**: Utilized libraries like Pandas for data manipulation and Matplotlib/Seaborn for visualizations.
* **Power BI**: Created interactive dashboards featuring:

  * Vendor performance metrics
  * Quality issue identification
  * Delivery timelines
  * Cost analysis

##  Sample Visuals

!\[Dashboard Preview]\(Dashboard Image.png)

*Note: Replace this image with an actual screenshot of your Power BI dashboard.*

##  Report Summary

The `Vendor Performance Report.pdf` provides an in-depth analysis of vendor performance, including:

* Identification of top-performing and underperforming vendors.
* Analysis of quality issues and their impact on operations.
* Recommendations for procurement strategy improvements.

##  Conclusion

This project showcases the integration of SQL, Python, and Power BI to perform comprehensive vendor performance analysis. The insights derived can aid in making informed decisions to enhance supply chain efficiency and vendor relationships.
