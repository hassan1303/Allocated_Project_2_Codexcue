# Titanic Dataset Exploratory Data Analysis (EDA)

This project is a step-by-step Exploratory Data Analysis (EDA) on the Titanic dataset, providing insights into factors affecting passenger survival. Over seven days, this EDA process explores the relationships between socio-demographic factors and survival rates.

## Project Overview

The Titanic dataset, a popular dataset in data science, contains information about passengers on the Titanic, including socio-demographic information, travel details, and survival status. This project aims to uncover patterns and relationships within the data that influenced survival outcomes.

## Dataset Information

The dataset used in this analysis is Seaborn's built-in Titanic dataset. It includes features such as:
- **Passenger Class (pclass)**
- **Gender (sex)**
- **Age (age)**
- **Embarked Port (embarked)**
- **Fare (fare)**
- **Number of Siblings/Spouses Aboard (sibsp)**
- **Number of Parents/Children Aboard (parch)**
- **Survival Status (survived)**

## Installation and Setup

1. **Environment Setup:**
   - Set up your environment using Google Colab, Jupyter Notebook, or Visual Studio Code.
   - Install the required libraries:
     ```python
     !pip install seaborn pandas matplotlib
     ```

2. **Data Loading:**
   - Load the dataset:
     ```python
     import seaborn as sns
     import pandas as pd
     import matplotlib.pyplot as plt
     
     titanic = sns.load_dataset('titanic')
     ```

## Project Outline

This project is broken down into seven days, each with specific goals:

1. **Day 1: Setup and Data Loading**
   - Explore the dataset structure, data types, and missing values.

2. **Day 2: Data Cleaning**
   - Handle missing values and encode categorical variables.
   - Create new features like `FamilySize`.

3. **Day 3: Univariate Analysis**
   - Analyze distributions of individual features like `survived`, `pclass`, `age`, and `fare`.

4. **Day 4: Bivariate Analysis**
   - Examine survival rates across features like `sex`, `pclass`, and `age`.

5. **Day 5: Multivariate Analysis**
   - Analyze interactions between multiple factors, such as class and gender, or family size and survival.

6. **Day 6: Correlations and Key Visualizations**
   - Generate correlation matrices and visualize key relationships.

7. **Day 7: Summary and Documentation**
   - Summarize findings and document insights.

## Key Insights

1. **Gender and Survival:** Female passengers had a higher survival rate compared to males.
2. **Class and Survival:** First-class passengers had the highest survival rates, possibly due to proximity to lifeboats.
3. **Age and Survival:** Younger passengers, particularly children, had better survival rates.
4. **Family Size and Survival:** Passengers with moderate family sizes had higher survival rates than those alone or with large families.

## Running the Analysis

To run this analysis:
1. Clone the repository and navigate to the project folder.
2. Open the Jupyter Notebook file and run each cell in sequence to reproduce the analysis.

## Requirements

- Python 3.x
- Libraries: Pandas, Seaborn, Matplotlib

## Results and Documentation

- The notebook provides markdown cells summarizing each section, as well as clear visualizations highlighting the key findings.
- The analysis concludes with a report summarizing which factors most influenced survival.

## Contributing

Contributions are welcome. If you find any issues or have suggestions, please create a pull request or submit an issue.

## License

This project is open-source and available under the MIT License.
