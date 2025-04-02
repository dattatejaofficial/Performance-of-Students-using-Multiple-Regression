# Performance of Students using Multiple Regression

This project aims to develop a multiple linear regression model to predict the Student Performance Index based on various academic factors. The analysis utilizes a dataset containing information such as hours studied, previous scores, sleep hours, and the number of practice papers completed.

## Table of Contents

- [Overview](#overview)
- [Project Structure](#project-structure)
- [Setup Instructions](#setup-instructions)
- [Usage](#usage)
- [Extracted Insights](#extracted-insights)
- [Dependencies](#dependencies)
- [License](#license)

## Overview

The objective of this project is to develop a multiple regression model that predicts the Student Performance Index based on several key factors:

- **Hours Studied**: Total hours spent studying.
- **Previous Scores**: Scores obtained in previous assessments.
- **Extracurricular Activities**: Student participated in Extracurricular Activities.
- **Sleep Hours**: Average number of hours slept.
- **Number of Practice Papers**: Count of practice papers completed.

By analyzing these variables, the model aims to identify significant predictors of student performance and provide insights into effective study habits.

## Project Structure

The repository contains the following files:

- `student-performance-by-multiple-regression.ipynb`: A Jupyter Notebook that performs data loading, cleaning, analysis, and model development.
- `Student_Performance.csv`: A CSV file containing the dataset with columns for hours studied, previous scores, sleep hours, number of practice papers, and performance index.

## Setup Instructions

To set up and run the project locally, follow these steps:

1. **Clone the Repository**: Use the following command to clone the repository to your local machine:

   ```bash
   git clone https://github.com/dattatejaofficial/Performance-of-Students-using-Multiple-Regression.git
   ```

2. **Navigate to the Project Directory**: Move into the project directory:

   ```bash
   cd Performance-of-Students-using-Multiple-Regression
   ```

3. **Create a Virtual Environment** (optional but recommended): Set up a virtual environment to manage project dependencies:

   ```bash
   python3 -m venv env
   ```

   Activate the virtual environment:

   - On Windows:
     ```bash
     .\env\Scripts\activate
     ```
   - On macOS/Linux:
     ```bash
     source env/bin/activate
     ```

4. **Install Dependencies**: Install the required Python packages using pip. The necessary packages are listed in the `requirements.txt` file. If `requirements.txt` is not present, you can manually install the following packages:

   ```bash
   pip install pandas numpy scikit-learn matplotlib seaborn
   ```

## Usage

To run the analysis:

1. **Ensure the Virtual Environment is Activated**: Make sure your virtual environment is active (refer to the setup instructions above).

2. **Open the Jupyter Notebook**: Launch Jupyter Notebook:

   ```bash
   jupyter notebook
   ```

3. **Run the Notebook**: Open `student-performance-by-multiple-regression.ipynb` in the Jupyter interface and execute the cells sequentially to perform the analysis and model development.

## Extracted Insights

The multiple regression analysis provides the following insights:

- **Significant Predictors**: Hours studied and previous scores are strong positive predictors of student performance.
- **Negative Correlation**: An increase in sleep hours is associated with a slight decrease in performance, suggesting diminishing returns beyond optimal rest.
- **Practice Papers**: Completing more practice papers is linked to higher performance, highlighting the importance of practice.

These findings suggest that students should focus on increasing study hours and completing practice papers to enhance academic performance.

## Dependencies

The project requires the following Python packages:

- `pandas`
- `numpy`
- `scikit-learn`
- `matplotlib`
- `seaborn`

These dependencies are essential for data manipulation, modeling, and visualization tasks.
