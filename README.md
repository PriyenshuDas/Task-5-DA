# Titanic Survival Prediction

This project is a machine learning analysis of the Titanic dataset. It involves data cleaning, exploration, and building a predictive model to determine the survival chances of passengers.

## Table of Contents
- [About the Project](#about-the-project)
- [Technologies Used](#technologies-used)
- [Project Structure](#project-structure)
- [How to Run the Project](#how-to-run-the-project)
- [Results](#results)
- [License](#license)

## About the Project

The Titanic dataset is one of the most popular beginner datasets for machine learning and data analysis.  
In this project, the goal is to:
- Understand key factors that influenced passenger survival
- Clean and preprocess the data
- Build a machine learning model to predict survival
- Evaluate the model’s performance

The main machine learning algorithm used in this project is **Decision Tree Classifier**.

---

## Technologies Used

- Python 3.x
- Jupyter Notebook
- Libraries:
  - pandas
  - numpy
  - matplotlib
  - seaborn
    

---

## Project Structure

- **Data Loading:** Importing the dataset into a pandas DataFrame.
- **Data Cleaning:**
  - Handling missing values.
  - Dropping irrelevant features.
- **Exploratory Data Analysis (EDA):**
  - Visualizations using Matplotlib and Seaborn.
  - Understanding the relationship between features and survival.
- **Feature Engineering:**
  - Converting categorical variables into numeric formats.
- **Model Building:**
  - Splitting data into training and testing sets.
  - Building a Decision Tree Classifier.
- **Model Evaluation:**
  - Checking model accuracy on the test set.

---

## How to Run the Project

1. Clone the repository:
    ```bash
    git clone https://github.com/your-username/your-repository-name.git
    ```
2. Navigate to the project directory:
    ```bash
    cd your-repository-name
    ```
3. Install required libraries (if not already installed):
    ```bash
    pip install pandas numpy matplotlib seaborn 
    ```
4. Run the Jupyter Notebook:
    ```bash
    jupyter notebook Taitanic.ipynb
    ```

---

## Results

The Decision Tree Classifier achieved a decent accuracy on the test data.  
The EDA revealed several important insights, such as:
- Female passengers had a much higher survival rate.
- Younger passengers had higher survival rates.
- First-class passengers had higher survival rates compared to second- and third-class passengers.

---

