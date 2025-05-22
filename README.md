#  Student Performance Analysis using Python & Data Visualization

This project was completed as part of the **DS & ML Bootcamp by Ai DataYard** and focuses on analyzing student performance data using core Python libraries. The aim is to draw meaningful insights through data analysis and visualization.

---

##  Project Objective

The goal of this project is to analyze student performance data to:

* Extract insights from academic and demographic features
* Identify patterns in student outcomes
* Visualize relationships among variables such as gender, parental education, and subject scores

---

##  Dataset Overview

* **Dataset**: [Students Performance in Exams (Kaggle)](https://www.kaggle.com/datasets/spscientist/students-performance-in-exams)
* **Features**:

  * Gender
  * Race/Ethnicity
  * Parental Level of Education
  * Lunch Type
  * Test Preparation Course
  * Math, Reading, and Writing Scores

---

##  Tools & Libraries Used

* Python (Jupyter Notebook)
* NumPy
* Pandas
* Matplotlib
* Seaborn

---

##  Key Concepts Applied

* Python Basics (Lists, Dictionaries, Loops)
* Data Cleaning & Transformation
* Exploratory Data Analysis (EDA)
* Data Visualization
* Grouping and Aggregation
* Conditional Logic

---

##  Tasks Performed

1. Loaded and explored the dataset
2. Checked column names and data types
3. Generated descriptive statistics
4. Checked for missing values
5. Created new columns:

   * `average_score`: average of math, reading, and writing
   * `performance_level`: High / Medium / Low
   * `pass_math`: Yes / No based on score ≥ 50
6. Used NumPy to compute mean, median, and standard deviation
7. Analyzed scores by gender and parental education using `groupby()`
8. Identified low-scoring students (<40 in any subject)
9. Plotted various charts:

   * Histogram (Math scores)
   * Boxplot (Math scores by gender)
   * Barplot (Reading scores by parental education)
   * Scatterplot (Reading vs. Writing)
   * Countplot (Test preparation course status)

---

##  Key Insights

* Most students fall under the **Medium performance level**
* **Female students** tend to score higher in **reading and writing**
* **Male students** generally perform better in **math**
* **Higher parental education** correlates with better student performance
* **Test preparation** significantly improves scores
* Students receiving **standard lunch** perform better
* There is a **strong correlation between reading and writing scores**
* Students scoring below 40 in any subject may need **additional academic support**


##  Author

**Maira Nawaz**

[LinkedIn](https://www.linkedin.com/in/mairanawaz/) | [Kaggle](https://www.kaggle.com/mairanawaz) | [Github](https://github.com/Maira-Nawaz)



