
# Titanic Exploratory Data Analysis (EDA)

## Student Details
- **Student Name:** Shrey Shah
- **Course:** Data Analysis
- **Project Title:** Titanic Exploratory Data Analysis using Python

## 1. Project Overview
This project performs Exploratory Data Analysis (EDA) on the Titanic passenger dataset. It explores passenger information, missing values, survival patterns, and relationships between variables using Python data-analysis libraries.

## 2. Objectives
- Load and inspect CSV datasets.
- Understand rows, columns, and data types.
- Identify missing values and duplicate records.
- Clean selected data fields.
- Analyze survival by gender, passenger class, age, fare, and embarkation port.
- Perform numerical calculations using NumPy.
- Create visualizations using Matplotlib and Seaborn.
- Practice file handling and exception handling.
- Save charts, cleaned data, and an analysis report.

## 3. Libraries Used
- **NumPy:** Numerical calculations.
- **Pandas:** Data loading, cleaning, grouping, and analysis.
- **Matplotlib:** Creating and saving charts.
- **Seaborn:** Statistical visualizations.
- **OS:** Managing folders and file paths.
- **File handling:** Reading and writing CSV and text files.
- **Exception handling:** Managing common errors.

## 4. Project Structure

```text
Titanic_EDA/
├── train.csv
├── test.csv
├── gender_submission.csv
├── titanic_eda.py
├── README.md
└── outputs/
    ├── cleaned_train.csv
    ├── eda_report.txt
    └── visualization PNG files
```

The `outputs` folder is created automatically when the program runs.

## 5. Installation

Open the VS Code terminal and run:

```bash
python -m pip install numpy pandas matplotlib seaborn
```

## 6. How to Run
1. Keep all three CSV files in the project folder.
2. Save the program as `titanic_eda.py`.
3. Open the terminal in the project folder.
4. Run the program:

```bash
python titanic_eda.py
```

5. Select option 1 to load the CSV files.
6. Use the menu to explore, clean, analyze, and visualize the data.

## 7. Project Features
1. Load CSV files.
2. Explore dataset structure and descriptive statistics.
3. Check missing values and duplicates.
4. Clean selected training-data fields.
5. Analyze survival patterns.
6. Perform NumPy calculations.
7. Generate seven visualizations.
8. Inspect test and submission data.
9. Save a text analysis report.
10. Exit the program.

## 8. Visualizations
The project generates:
- Passenger survival count
- Survival by gender
- Survival rate by passenger class
- Age distribution
- Ticket fare distribution
- Age distribution by survival
- Correlation heatmap

## 9. Important Notes
- `Survived = 0` means the passenger did not survive.
- `Survived = 1` means the passenger survived.
- The test dataset does not contain actual survival outcomes.
- `gender_submission.csv` contains baseline predictions, not verified outcomes.
- Correlation does not prove causation.
- Missing-value treatment should be justified when interpreting results.

## 10. Learning Outcomes
Through this project, I practiced:
- Python programming and object-oriented programming.
- File handling and exception handling.
- Data exploration and cleaning using Pandas.
- Numerical analysis using NumPy.
- Data visualization using Matplotlib and Seaborn.
- Interpreting patterns and limitations in a dataset.

## 11. Conclusion
This project demonstrates a beginner-level EDA workflow, from loading and understanding raw data to cleaning selected fields, calculating statistics, creating visualizations, and exporting results.

**Created by: Shrey Shah**
