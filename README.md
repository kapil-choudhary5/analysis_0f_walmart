# Walmart Retail Sales Data Analysis: Enterprise Analytics Solution

![Walmart Logo](https://upload.wikimedia.org/wikipedia/commons/thumb/c/ca/Walmart_logo.svg/1280px-Walmart_logo.svg.png)

This project delivers comprehensive analysis of Walmart's retail sales data (2001-2015), focusing particularly on 2012-2015. It combines MySQL database functionality with visualization
to uncover valuable business insights from retail performance metrics.

## Technical Architecture

The solution uses a three-tier approach:
- **Data Preparation Layer**: Handles extraction, transformation, and cleaning
- **Persistence Layer**: Features MySQL database with optimized schema design
- **Analytics Layer**: Provides SQL analytics engine with visualization capabilities

## Key Features

- Clean data pipeline with normalization processes
- Optimized relational database with SQL view enhancements
- Advanced SQL analytics using window functions and aggregations
- Statistical visualizations with customizable parameters
- Time-series analysis for regional performance tracking
- Product category profitability analysis by location

## Repository Organization

```
analysis_of_walmart/
│
├── visualization
│   └── top_profit_by_region.png     # visualization in charts
├── WalmartRetailSales.csv           # dataset
├── walmart_ analysis.py             # analysis of sales
├── LICENSE                          # License information
└── README.md                        # Project documentation
```

## Setup Requirements

### System Specifications
- Windows 10/11
- Python 3.9+ (64-bit)
- MySQL 8.0+
- 8GB RAM minimum (16GB recommended)
- 1GB free storage

### Dependencies
```
pandas==2.0.0+
pymysql==1.1.0+
sqlalchemy==2.0.0+
matplotlib==3.7.0+
seaborn==0.12.0+
openpyxl==3.1.0+
```

### Installation Steps (Windows)

1. **Set Up MySQL Database**
   - Install MySQL Server 8.0+ (Server, Workbench, Connector/Python)
   - Configure development environment with strong authentication
   - Create dedicated database and user

2. **Configure Python Environment**
   - Install Python 3.8+
   - Create virtual environment
   - Install required packages
   - Clone repository and configure environment variables

## Usage Instructions

1. **Initialize Database**
   - Configure database parameters
   - Run setup script

2. **Run Analysis**
   - Launch Jupyter notebook
   - Execute cells sequentially to perform analytics, and visualization

## Analysis Components

- **Temporal Analysis**: Year-over-year performance, order frequency, seasonal patterns
- **Geographic Analysis**: State-level comparisons, regional growth rates
- **Product Analysis**: Category profitability, regional preferences, margin analysis

## Visualization Types
- Regional analysis using bar charts



## Security Notes

- Environment variables manage credentials
- Production deployment requires transport security
- Authentication follows least-privilege principles

License
This project is licensed under the MIT License - see the LICENSE file for details.

Acknowledgments
Data sourced from Walmart retail operations

