# Impact of Working Hours on Fertility Rate Analysis

Project Overview This project investigates the relationship between working hours and fertility rates among women using R statistical analysis while controlling for various socioeconomic factors.

## === Data Source ===

1. IPUMS USA dataset

2. Sample includes women aged 18-49

3. Key variables: number of children, working hours, income, age, and education level

## === Key Features ===

### Data Cleaning and Preprocessing

1. Outlier removal using IQR method

2. Missing value handling

3. Variable transformation (log income)

4. Education level categorization

### Statistical Analysis

1. Three progressive Poisson regression models:

2. Basic model (working hours + controls)

3. Age-squared model (non-linear age effects)

4. Full model (including income)

5. Heterogeneity analysis

6. Robust standard errors

### Visualization

1. Distribution plots for key variables

2. Residual diagnostics

3. Relationship plots between variables

## === Requirements ===

### Required R packages:

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


## === Project Structure ===

1. Data preprocessing

2. Exploratory data analysis

3. Model development and comparison

4. Heterogeneity analysis

5. Results visualization and interpretation

## === How to Run ===
1. Data and code need to be saved in the same file

2. Install required packages

3. Run the R markdown file

## === Results ===

### The analysis includes:

1. Descriptive statistics

2. Model comparisons with R² values Visualization of relationships

3. Residual diagnostics

4. Heterogeneity tests

## === Contact ===

Group_U
