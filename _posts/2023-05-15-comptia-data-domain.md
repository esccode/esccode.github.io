---
title: CompTIA Data+ Domain
categories:
- data
excerpt: |
## CompTIA Data+ Domain excerpt
feature_text: |  
  ## CompTIA Data+ Domain features
feature_image: "https://picsum.photos/2560/600?image=733"
image: "https://picsum.photos/2560/600?image=733"
aside: true
---

- [Domain 1.0 Data Concepts and Environments](#domain-10-data-concepts-and-environments)
  - [1.1 Identitfy basic concepts of data schemas and dimensions](#11-identitfy-basic-concepts-of-data-schemas-and-dimensions)
  - [1.2 Compare and contrast different data types](#12-compare-and-contrast-different-data-types)
  - [1.3 Compare and contrast common data structures and file formats](#13-compare-and-contrast-common-data-structures-and-file-formats)
- [Domain 2.0 Data Mining](#domain-20-data-mining)
  - [2.1 Explain data acquisition concepts](#21-explain-data-acquisition-concepts)
  - [2.2 Identify common reason for cleansing and profiling datasets](#22-identify-common-reason-for-cleansing-and-profiling-datasets)
  - [2.3 Given a scenario, execute data manipulation techniques](#23-given-a-scenario-execute-data-manipulation-techniques)
  - [2.4 Explain common techniques for data manipulation and query optimization](#24-explain-common-techniques-for-data-manipulation-and-query-optimization)
- [Domain 3.0 Data Analysis](#domain-30-data-analysis)
  - [3.1 Given a scenario, apply the appropriate descriptive statistical methods](#31-given-a-scenario-apply-the-appropriate-descriptive-statistical-methods)
  - [3.2 Explain the purpose of inferential statistical methods](#32-explain-the-purpose-of-inferential-statistical-methods)
  - [3.3 Summarize types of analysis and key analysis techniques](#33-summarize-types-of-analysis-and-key-analysis-techniques)
  - [3.4 Identify common data analytics tools](#34-identify-common-data-analytics-tools)
- [Domain 4.0 Visualization](#domain-40-visualization)
  - [4.1 Given a scenario, translate business requirements to form a report](#41-given-a-scenario-translate-business-requirements-to-form-a-report)
  - [4.2 Given a scenario, use appropriate design components for reports and dashboards](#42-given-a-scenario-use-appropriate-design-components-for-reports-and-dashboards)
  - [4.3 Given a scenario, use appropriate methods for dashboards development](#43-given-a-scenario-use-appropriate-methods-for-dashboards-development)
  - [4.4 Given a scenario, apply the appropriate type of visualization](#44-given-a-scenario-apply-the-appropriate-type-of-visualization)
  - [4.5 Compare and contrast types of reports](#45-compare-and-contrast-types-of-reports)
- [Domain 5.0 Data Governance, Quality, and Controls](#domain-50-data-governance-quality-and-controls)
  - [5.1 Summarize important data governance concepts](#51-summarize-important-data-governance-concepts)
  - [5.2 Given a scenario, apply data quality control concepts](#52-given-a-scenario-apply-data-quality-control-concepts)
  - [5.3 Explain master data management (MDM) concepts](#53-explain-master-data-management-mdm-concepts)
- [CompTIA Data+ (DA0-001) Acronym List](#comptia-data-da0-001-acronym-list)
- [CompTIA Data+ Proposed Hardware and Software List](#comptia-data-proposed-hardware-and-software-list)
  - [Hardware](#hardware)
  - [Software](#software)
- [Reference](#reference)

## Domain 1.0 Data Concepts and Environments

### 1.1 Identitfy basic concepts of data schemas and dimensions

- Databases
  - Relational
  - Non-relational
- Data mart/data warehousing/data lake (**data warehouse** is a technology that is dedicated to the storage of company data from a wide range of sources for reporting and decision-making purposes (DW-Extract, Transform, Load, DL-Extract, Load, Transform),  (**data mart** is a subset of the data warehouse that is dedicated to a specific department or group), (**data lake** is a technology for storing large amounts of structured and unstructured types of information in their original format)
  - Online transactional processing(**OLTP**) (A class of software that allows large numbers of database transactions in real time, typically over the internet)
  - Online analytical processing(**OLAP**)(A class of software that allows complex analysis to be conducted on large databases without negatively affecting transactional systems)
- Schema concepts
  - Snowflake
  - Star
- Slowly changing dimensions
  - Keep current information
  - Keep historical and current information

### 1.2 Compare and contrast different data types

- Data
- Numeric
- Alphanumeric
- Currency
- Text
- Discrete vs. continuous
- Categorical/dimension (**Categorical** data(qualitative))
- Images
- Audio
- Video

### 1.3 Compare and contrast common data structures and file formats

- Structures
  - Structured
    - Defined rows/columns
    - Key value pairs
  - Unstructured
    - Undefined fields
    - Machine data
- Data file formats
  - Text/Flat file
    - Tab delimited
    - Comma delimited
  - JavaScript Object Notation(JSON)
  - Extensible Markup Language(XML)
  - Hypertext Markup Language(HTML)

## Domain 2.0 Data Mining

### 2.1 Explain data acquisition concepts

- Integration
  - Extract, transform, load(ETL)
  - Extract, load, transform(ELT)
  - Delta load(moves only recently changed data from the transactional system to data the data warehouse)
    - Initial load(moves all data from the transactional system to the data warehouse)
    - Data lakes
  - Application programming
  - Interfaces(APIs)
- Data collection methods
  - Web scraping
  - Public databases
  - Application programming
  - Interface(API)/web services
  - Survey
  - Sampling(pobieranie próbek)
  - Observation

### 2.2 Identify common reason for cleansing and profiling datasets

- Duplicate data
- Redundant data
- Missing values(MCAR,MAR,MNAR)
- Invalid data
- Non-parametric data
- Data outliers(odstajacych)
- Specification mismatch
- Data type validation

### 2.3 Given a scenario, execute data manipulation techniques

- Recoding data
  - Numeric
  - Categorical
- Derived variables(pochodne zmienne)
- Data merge(adds columns)
- Data blending(combine dataset from diffrent resources)
- Concatenation(combine two strings)
- Data append(adds rows)
- Imputation(przypisywanie)
- Reduction/aggregation
- Transpose(swap row and columns)
- Normalize data
- Parsing/string manipulation

### 2.4 Explain common techniques for data manipulation and query optimization

- Data manipulation
  - Filtering
  - Sorting
  - Date functions
  - Logical functions
  - Aggregate functions
  - System functions
- Query optimization
  - Parametrization
  - Indexing
  - Temporary table in the query set
  - Subset of records
  - Execution plan

## Domain 3.0 Data Analysis

### 3.1 Given a scenario, apply the appropriate descriptive statistical methods

Descriptive Statistics describes our data by summarizing it and providing us with visible features

- Measures of central tendency
  - **Mean**(math average value)
  - **Median**(the value in the middle of the sorted dataset)
  - **Mode**(most common value in the dataset)
- Measures of dispersion
  - Range
    - Max
    - Min
  - Distribution
  - **Variance**(the average of the squared differences of each value in the dataset from the mean)(symbol σ² used)
  - Standard deviation
- Frequencies/percentages
- Percent change(Normalizes data to be a proportion of 100)
- Percent difference
- Confidence intervals

### 3.2 Explain the purpose of inferential statistical methods

Inferential Statistics draws conclusions from our data by making generalizations and predictions

- t-tests(compare the means of two groups)
- Z-score(Describe how many standard deviations a particular measurement is away from the mean)
- P-values(Probability that test results are not statistically significant)
- Chi-squared(Determines whether categorical variables are associated)
- Hypothesis testing
  - Type I error(accept)
  - Type II error(reject)
- Simple linear regression
- Correlation

### 3.3 Summarize types of analysis and key analysis techniques

- Process to determine type of analysis
  - Review/refine business questions
  - Determine data needs and sources to perform analysis
  - Scoping/gap analysis
- Type of analysis
  - Trend analysis
    - Comparison of data over time
  - Performance analysis
    - Tracking measurements against defined goals
    - Basic projections to achieve goals
  - Exploratory data analysis
    - Use of descriptive statistics to determine observations
  - Link analysis
    - Connections of data points or pathway

### 3.4 Identify common data analytics tools

The intent of this objectives is NOT to test specific vendor feature sets nor the purposes of the tools.

- Structured Query Language(SQL)
- Python
- Microsoft Excel
- R
- Rapid mining
- IBM Cognos
- IBM SPSS Modeler
- IBM SPSS
- SAS
- Tableau
- Power BI
- Qlik
- MicroStrategy
- BusinessObjects
- Apex
- Dataroma
- Domo
- AWS QuickSight
- Stata
- Minitab

## Domain 4.0 Visualization

### 4.1 Given a scenario, translate business requirements to form a report

- Data content
- Filtering
- Views
- Date range
- Frequency
- Audience for report
  - Distribution list

### 4.2 Given a scenario, use appropriate design components for reports and dashboards

- Report cover page
- Design elements
- Documentation elements

### 4.3 Given a scenario, use appropriate methods for dashboards development

- Dashboard considerations
- Development process
- Delivery considerations

### 4.4 Given a scenario, apply the appropriate type of visualization

- Line chart
- Pie chart
- Bubble chart
- Scatter plot
- Bar chart
- Histogram
- Waterfall
- Heat map
- Geographic map
- Tree map
- Stacked chart
- Infographic
- Word cloud

### 4.5 Compare and contrast types of reports

- Static vs. dynamic reports
- Ad-hoc/one-time report
- Self-service/on-demand
- Recuring reports

## Domain 5.0 Data Governance, Quality, and Controls

### 5.1 Summarize important data governance concepts

- Access requirements
  - Role-based
  - User group-based
  - Data use agreements
  - Release approvals
- Security requirements
  - Data encryption
  - Data transmission
  - De-identify data/data masking
- Storage environment requirements
  - Shared drive vs. cloud based vs. local storage
- Use requirements
  - Acceptable use policy
  - Data processing
  - Data deletion
  - Data retention
- Entity relationship requirements
  - Record link restrictions
  - Data constraints
  - Cardinality
- Data classification
  - Personally identifiable information(PII)
  - Personal health information(PHI)
  - Payment card industry(PCI)
- Jurisdiction requirements
  - Impact of industry and governmental regulations
- Data breach reporting
  - Escalate to appropriate authority

### 5.2 Given a scenario, apply data quality control concepts

- Circumstances to check for quality
  - Data acquisition/data source
  - Data transformation/intrahops
    - Pass through
    - Conversion
  - Data manipulation
  - Final product (report/dashboard, etc.)
- Automated validation
  - Data field to data type validation
  - Number of data points
- Data quality dimensions
  - Data consistency
  - Data accuracy
  - completeness
  - Data integrity
  - Data attribute limitations
- Data quality rule and metrics
  - Conformity
  - Non-conformity
  - Rows passed
  - Rows failed
- Methods to validate quality
  - Cross-validation
  - Sample/spot check
  - Reasonable expectations
  - Data proiling
  - Data audits

### 5.3 Explain master data management (MDM) concepts

- Processes
  - Consolidation of multiple data fields
  - Standardization of data field names
  - Data dictionary
- Circumstances for MDM
  - Mergers and acquisitions
  - Compliance with policies and regulations
  - Streamline data access

## CompTIA Data+ (DA0-001) Acronym List

> The following is a list of acronyms that appear on the CompTIA Data+ exam. Candidates are encourage to review the complate list and attain a working knowledge of all listed acronyms as a part of a comprehensive exam preparation program.

|ACRONYM|DEFINITION|
|---|---|
|ANOVA|Analysis of Variance|
|API|Application Programming Interface|
|AWS|Amazon Web Services|
|BI|Business Intelligence|
|CRM|Customer Relationship Management|
|CSV|Comma-separated Values|
|ELT|Extract, Load, Transform|
|ETL|Extract, Transform, Load|
|FAQs|Frequently Asked Question|
|GDPR|General Data Protection Regulation|
|HTML|Hypertext Markup Language|
|JSON|JavaScript Object Notation|
|KPI|Key Performance Indicator|
|MDM|Master Data Management|
|NoSQL| Not Only Structured Query Language|
|OLAP|Online Analytical Processing|
|OLTP|Online Transaction Processing|
|P&L|Profit and Loss|
|PCI|Payment Card Industry|
|PDF|Portable Document Format|
|PHI|Personal Health Information|
|PII|Personally Identifiable Information|
|RDBMS|Relational Database Management System|
|SDLC|Software Development Life Cycle|
|SQL|Structured Query Language|
|XML|Extensible Markup Language|

## CompTIA Data+ Proposed Hardware and Software List

> CompTIA has included this sample list of hardware and software to assist candidates as they prepare for the Data+ exam. This list may also be helpful for training companies that wish to create a lab component for their training offering. The bulleted lists below each each topic are samples and not exhaustive.

### Hardware

### Software

## Reference

[CompTIA](https://comptia.org)

---
