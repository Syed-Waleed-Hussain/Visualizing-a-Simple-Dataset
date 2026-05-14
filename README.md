# Exploring and Visualizing the Iris Dataset

This project focuses on the fundamental steps of Exploratory Data Analysis (EDA). Using the classic **Iris Dataset**, we demonstrate how to load data, perform initial inspections, and create meaningful visualizations to uncover patterns and distributions.

---

## 🎯 Objective
The primary goal is to learn how to:
* Load and inspect datasets using `pandas`.
* Generate summary statistics.
* Visualize data trends and distributions using `matplotlib` and `seaborn`.

---

## 🛠️ Skills & Tools
* **Language:** Python
* **Libraries:** * `pandas`: For data manipulation and inspection.
    * `matplotlib`: For basic plotting.
    * `seaborn`: For advanced statistical visualizations.
* **Concepts:** Data Loading, Descriptive Statistics, Scatter Plots, Histograms, and Box Plots.

---

## 📊 Dataset Overview
The **Iris Dataset** consists of 150 samples from three species of Iris flowers (*Iris setosa*, *Iris virginica*, and *Iris versicolor*). Four features were measured from each sample:
1.  Sepal Length (cm)
2.  Sepal Width (cm)
3.  Petal Length (cm)
4.  Petal Width (cm)

---

## 🚀 Key Steps in the Project

### 1. Data Inspection
We use `pandas` to understand the structure of our data:
* `df.shape`: To see the dimensions.
* `df.head()`: To view the first few rows.
* `df.info()`: To check for data types and missing values.
* `df.describe()`: To get statistical summaries like mean, median, and standard deviation.

### 2. Data Visualization
To better understand the relationships between features, we generated:
* **Scatter Plots:** To visualize the relationship between features (e.g., Sepal Length vs. Sepal Width).
* **Histograms:** To observe the distribution of values for each feature.
* **Box Plots:** To identify outliers and understand the spread of data across species.

---

## 📂 How to Run
1.  Clone this repository.
2.  Install the required libraries:
    ```
    pip install pandas matplotlib seaborn
    ```
3.  Run the Jupyter Notebook or Python script:
    ```
    python iris_analysis.py
    ```
