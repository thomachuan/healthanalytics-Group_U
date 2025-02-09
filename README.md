## Impact of Working Hours on Fertility Rate Analysis

Project Overview This project investigates the relationship between working hours and fertility rates among women using R statistical analysis while controlling for various socioeconomic factors.

### === Data Source ===

IPUMS USA dataset

Sample includes women aged 18-49

Key variables: number of children, working hours, income, age, and education level

# === Key Features ===

Data Cleaning and Preprocessing

Outlier removal using IQR method

Missing value handling

Variable transformation (log income)

Education level categorization

Statistical Analysis

Three progressive Poisson regression models:

Basic model (working hours + controls)

Age-squared model (non-linear age effects)

Full model (including income)

Heterogeneity analysis

Robust standard errors

Visualization

Distribution plots for key variables

Residual diagnostics

Relationship plots between variables

=== Requirements ===

Required R packages:

{r setup}
packages = c(
    "ipumsr", 
    "dplyr", 
    "ggplot2", 
    "tidyr", 
    "here", 
    "rmdformats", 
    "srvyr",
    "DiagrammeR",
    "gridExtra",
    "haven",
    "gtsummary",
    "pscl",
    "stargazer",
    "sandwich",
    "lmtest",
    "modelsummary",
    "gt",
    "gridExtra",
    "survey",
    "sandwich",
    "Matrix",
    "zoo",
    "here"
)


=== Project Structure ===

Data preprocessing

Exploratory data analysis

Model development and comparison

Heterogeneity analysis

Results visualization and interpretation

=== How to Run ===

Set working directory to data location

Install required packages

Run the R markdown file

=== Results ===

The analysis includes:

Descriptive statistics

Model comparisons with R² values Visualization of relationships

Residual diagnostics

Heterogeneity tests

=== Contact ===

Group_U
