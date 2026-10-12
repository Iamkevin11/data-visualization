# Python Data Visualization – Taxis Dataset

## Project Overview

This project focuses on data cleaning, exploratory data analysis, and visualization using Python. The Seaborn Taxis dataset is analyzed to explore taxi fares, trip distances, payment methods, and pickup boroughs through different visualization techniques.

## Objectives

- Load and explore the Taxis dataset using Seaborn.
- Identify and handle missing values.
- Perform data preprocessing using Pandas.
- Create visualizations using Matplotlib and Seaborn.
- Understand patterns and relationships within taxi trip data.

## Technologies Used

- Python
- Pandas
- Matplotlib
- Seaborn

## Data Cleaning

- Checked for missing values in the dataset.
- Converted pickup and dropoff timestamps into datetime format.
- Removed rows with missing critical values.
- Handled missing numerical values using the median.
- Handled missing categorical values using the mode.

## Data Visualizations

The project includes the following 10 visualizations:

### Matplotlib and Pandas

1. **Line Chart:** Average taxi fare over time.
2. **Bar Chart:** Total fare by pickup borough.
3. **Pie Chart:** Distribution of trips by payment method.
4. **Histogram:** Distribution of taxi trip distances.
5. **Box Plot:** Distribution of tip amounts by pickup borough.

### Seaborn

6. **Count Plot:** Number of trips by pickup borough.
7. **Scatter Plot:** Relationship between trip distance and fare.
8. **Heatmap:** Correlation between distance, fare, tip, tolls, and total.
9. **Pair Plot:** Pairwise relationships between distance, fare, tip, and total by pickup zone.
10. **Violin Plot:** Fare distribution by payment method.

## Dataset

The project uses the built-in Seaborn Taxis dataset.

```python
import seaborn as sns

df = sns.load_dataset("taxis")
```

An internet connection may be required to download the dataset when it is first loaded.

## Installation and Setup

### 1. Install the required libraries

```bash
pip install pandas matplotlib seaborn
```

### 2. Run the Python script

```bash
python python_da_assignment_2.py
```

The script displays the dataset information, missing-value analysis, and the visualizations.

## Key Learning Outcomes

- Understanding data cleaning and missing-value handling.
- Applying Pandas for data manipulation and aggregation.
- Creating different types of visualizations.
- Exploring relationships and correlations between numerical variables.
- Improving practical Python data analytics skills.

## Author

Data Analytics Learner
