**GLOBAL LAYOFFS DATA ANALYSIS USING SQL**
____________________________________________________________________________________________________________________________________________________________________________________________________________________

1. **Project Overview**
   
This project provides a data-driven examination of global workforce reductions through systematic analysis of layoff patterns. The methodology comprises two distinct phases:

* Data Preparation: Comprehensive data cleaning and standardization process

* Exploratory Analysis: In-depth investigation of workforce reduction trends

The analysis yields actionable insights into industry vulnerabilities, geographic concentrations, and temporal patterns of corporate downsizing.
____________________________________________________________________________________________________________________________________________________________________________________________________________________


**2. Dataset Specifications**

**Record Count:** 2,362 entries

**Key Fields:**

* Company Attributes: company, location, industry, stage, country

* Layoff Metrics: total_laid_off, percentage_laid_off

* Financial Data: funds_raised_millions

* Temporal Data: date
____________________________________________________________________________________________________________________________________________________________________________________________________________________


**3. Technical Implementation**

**I) Data Cleaning Pipeline (data_cleaning.sql)**

**Implementation Objectives:**

* Establish reliable data quality standards

* Create analysis-ready dataset structure

* Ensure reproducible data transformation processes

**Key Data Operations:**

Identification and elimination of duplicate records using ROW_NUMBER() window functions

**Standardization procedures:**

* Company name normalization

* Industry classification consolidation

* Geographic data cleansing

* Temporal data transformation from text to native DATE format

* Strategic handling of missing values through imputation

* Database schema optimization for analytical efficiency

 **Technical Components:**

* Advanced Common Table Expressions (CTEs) for complex data operations

* String manipulation functions for data standardization

* Self-join implementations for intelligent missing value resolution

* Schema modification operations for performance optimization

**II) Analytical Exploration (exploratory_data_analysis.sql)**

**Investigation Framework:**

**a. Sector Impact Analysis:**

* Industry-specific vulnerability assessment

* Comparative reduction magnitude across sectors

**b. Geospatial Analysis:**

* Regional distribution patterns

* Country-level impact comparisons

**c. Organizational Maturity Correlation:**

* Reduction patterns by company stage

* Funding-to-layoff relationships

**d. Temporal Analysis:**

* Quarterly/yearly trend identification

* Event-driven spike analysis
__________________________________________________________________________________________________________________________________________________________________________________________________________________

**4. Key Findings**

* The tech and crypto industries accounted for 40% of global layoffs.

* United States had the highest layoffs (60% of total).

* Layoffs peaked in 2023, correlating with economic downturns.

