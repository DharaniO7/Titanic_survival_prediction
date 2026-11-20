# Titanic Survival Analysis 🚢

## Project Overview
This project analyzes the Titanic dataset to understand passenger survival patterns using Python. It explores how gender, passenger class, and age were associated with survival chances through data analysis and visualization.

## Objectives
- Load and explore the Titanic dataset.
- Handle missing values and clean the data.
- Analyze survival rates based on gender.
- Examine survival rates across passenger classes.
- Study survival rates across different age groups.
- Create visualizations to identify patterns.

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Jupyter Notebook

## Dataset
The dataset is obtained from the Kaggle Titanic competition.

**Dataset:** [Titanic - Machine Learning from Disaster](https://www.kaggle.com/competitions/titanic/data)

## Data Cleaning
- Checked missing values.
- Filled missing Age values using the median.
- Filled missing Embarked values using the mode.
- Removed the Cabin column due to a large number of missing values.
- Verified missing values after cleaning.

## Analysis and Key Findings

### 1. Survival by Gender
- Female survival rate: 74.20%
- Male survival rate: 18.89%

Female passengers had a significantly higher survival rate.

### 2. Survival by Passenger Class
- First Class: 62.96%
- Second Class: 47.28%
- Third Class: 24.24%

First-class passengers had the highest survival rate.

### 3. Survival by Age Group
- Children (0–12): 57.97%
- Teenagers (13–18): 42.86%
- Adults (19–35): 35.33%
- Middle-aged (36–60): 40.00%
- Seniors (61+): 22.73%

Children had the highest survival rate among the age groups.

## Visualizations
The project includes:
1. Bar chart showing survival rate by gender.
2. Bar chart showing survival rate by passenger class.
3. Histogram showing the distribution of passenger ages.

## Conclusion
The analysis revealed that gender, passenger class, and age were associated with survival chances. Female passengers, first-class passengers, and children had higher survival rates in the dataset.

## How to Run the Project
1. Clone this repository.
2. Install the required libraries:
   ```bash
   pip install pandas numpy matplotlib seaborn jupyter
   ```
3. Open Jupyter Notebook:
   ```bash
   jupyter notebook
   ```
4. Open the Titanic Survival Analysis notebook and run the cells.

## Author
Created as part of a Data Science Internship Task.
