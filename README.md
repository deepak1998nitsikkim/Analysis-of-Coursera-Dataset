# Coursera Course Data Analysis

## Overview
This project analyzes Coursera course data to identify patterns and trends in student enrollment. The dataset includes various course attributes such as course title, organization, certificate type, rating, difficulty level, and the number of students enrolled.

## Dataset
The dataset consists of the following columns:
- **Unnamed: 0**: Index column.
- **course_title**: Name of the course.
- **course_organization**: Organization offering the course.
- **course_Certificate_type**: Type of certificate provided upon completion.
- **course_rating**: Average rating of the course.
- **course_difficulty**: Difficulty level (Beginner, Intermediate, Advanced).
- **course_students_enrolled**: Number of students enrolled (Target Variable).

## Objective
The main objective of this project is to predict course enrollment based on various attributes. This can help course providers understand which factors influence enrollment and optimize course offerings.

## Approach
1. **Data Cleaning & Preprocessing**:
   - Handling missing values.
   - Removing duplicate entries.
   - Converting data types if necessary.
2. **Exploratory Data Analysis (EDA)**:
   - Understanding distribution of numerical features.
   - Analyzing correlation between different features.
   - Visualizing trends in course enrollment.
3. **Feature Engineering**:
   - Creating new features if needed.
   - Encoding categorical variables.
4. **Model Development**:
   - Building regression or classification models to predict course enrollment.
   - Evaluating model performance using metrics like RMSE, R-squared, or classification accuracy.
5. **Insights & Recommendations**:
   - Identifying key factors influencing enrollment.
   - Providing actionable insights for course providers.

## Requirements
To run the analysis, install the following dependencies:
```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

## How to Use
1. Open the Jupyter Notebook (`coursera_data_analysis.ipynb`).
2. Run the preprocessing and analysis cells step by step.
3. Interpret the visualizations and model outputs.
4. Modify parameters to experiment with different models and features.

## Results
- Insights on how course ratings, difficulty, and organization impact enrollments.
- Predictive models for estimating course popularity.
- Recommendations for optimizing course offerings.

## Future Work
- Incorporating additional features such as course duration and price.
- Applying deep learning techniques for more accurate predictions.
- Developing a web dashboard to visualize course trends dynamically.

## Contact
For questions or contributions, feel free to reach out via GitHub or email.

---
*Happy Coding!* 🚀

