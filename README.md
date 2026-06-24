# Developer Salary Prediction Project

## Motivation
The goal of this porject is to analyze what factors influence developer salaries. 

Using data from the StackOverflow Developer Survey, I explore how experience, education and work experience affect salary outcomes. Additionally, I train a machine learning model to predict salaries based on these features.



## Data source
The dataset comes from the StackOverflow Developer Survey 2025
It is too large to be included in this repository. It can be downloaded here:
https://survey.stackoverflow.co/

The dataset contains information about developers, including salary, education level and experience.

## Buisness Questions
The project focuses on the following questions:
1. What features influence salary the most?
2. Are there surprising patterns in the data?
3. How accurate is a machine learning model in predicting salary?
4. WHat happes in a predictive scenario using the model?


## Libraries used
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn


## Files in the repository
- `notebook.ipynb` -> main analysis (data cleaning, visualization, modeling)
- `README.md` -> Project description
- `blog.md` -> Blog post summarizing the finidings
- `salary_plot.png` - Visualization used in the blog


## Summary of results
The analysis showed that experience has some influence on salary, but the relationship is not very strong. The scatterplot revealed a high variation in salary across all experience levels, indicating that other fators play in important role.

The machine learing model achieved an R2 score of around 0.15, meaning it explains only a small portion of salary variation. This suggests that salary is influenced by many other variables not included in the dataset.

A prediction scenario demonstrated how the model estiamtes salary based on experience and other features.


## Key insights
- Experience alone does not strongly determine salary
- Salaries vary widely even within the same experince range
- Many other factors (e.g., location, technology, company) likely influence salary


## Limitations
- The dataset contains noisy and self-reported data
- Imprtant variables (e.g., location, skills) were not included
- The model is simple and cannot capture complex relationships


## Acknowledgements
- StackOverflow Deleveloper Survey
- Udacity Data Scientist Program