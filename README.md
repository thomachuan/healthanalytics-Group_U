# Impact of Working Hours on Fertility Analysis

Project Overview This project investigates the relationship between working hours and fertility among women using R statistical analysis while controlling for various socioeconomic factors.

## === Description of Data ===

1. IPUMS series: We use the IPUMS USA dataset, which provides standardized individual-level information from the U.S. Census and American Community Survey. This dataset is well-suited for our analysis of working hours and fertility patterns among American women.

2. Years: We analyze data from the 2023. This recent timeframe allows us to examine current patterns of work-fertility relationships in the post-pandemic era.

3. How to access the data: The data can be accessed from IPUMS USA at the following link:
[https://usa.ipums.org/usa/](https://usa.ipums.org/usa-action/variables/group)

3. Key Variables:

    1. Fertility measure: Number of own children in household (NCHILD)
    2. Working hours: Usual hours worked per week (UHRSWORK)
    3. Control variables: Age (AGE), Education (EDUC), Total income (INCTOT)
    4. Other variables: Sex (SEX), Educational attainment (EDUCD)

![image](https://github.com/user-attachments/assets/db297d36-1d34-472a-97be-44aca2939ee7)



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
