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
### Clone this repository
```https://github.com/kapil-choudhary5/analysis_0f_walmart.git```

### Installation Steps (Windows)
1. Download MySQL Installer

 - Visit the official MySQL download page: https://dev.mysql.com/downloads/installer/
 - Choose the MySQL Installer for Windows (e.g., mysql-installer-web-community-*.msi for the web installer).

2. Run the Installer

 - Double-click the downloaded .msi file.
 - Choose setup type:

 - Developer Default: Installs MySQL Server + tools like Workbench.
 - Server Only: Installs only the MySQL Server.
 - Custom: Select specific components.



3. Install MySQL Server

 - Select MySQL Server (e.g., MySQL Server 8.0.x) from the list.
 - Click Next and follow prompts to install.

4. Configure MySQL Server
 - After installation, the Configuration Wizard will launch:

 - Choose Standalone MySQL Server.
 - Type and Networking:

 - Keep default settings (TCP/IP).

5. Authentication Method:

 - Use Strong Password Encryption (Recommended).

6. Set Root Password:

- Create a secure password for the root user.
Windows Service:

 - Set MySQL to start automatically as a Windows service.
 - Apply Configuration.

5. Test the Installation

Open Command Prompt or MySQL Shell.
  - Connect to MySQL:
  bashCopy
```mysql -u root -p ```

  - Enter the root password when prompted.


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

## License
  - This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments
  - Data sourced from Walmart retail operations

