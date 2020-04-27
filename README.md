# Predicting churn for a music streaming service

### Table of Contents

1. [Installation](#installation)
2. [Project Motivation](#motivation)
3. [File Descriptions](#files)
4. [Results](#results)
5. [Licensing, Authors, and Acknowledgements](#licensing)

## Installation <a name="installation"></a>

The code should run with no issues using the Python versions 3.* and the Anaconda distribution.

The python libraries used are:
- PySpark
- NumPy
- Pandas
- Matplotlib
- Seaborn

## Project Motivation<a name="motivation"></a>
This project is one of the possible capstone projects for the Udacity course on Data Sciense. We are provided usage data for a fictional music streaming serice called "Sparkify". The goal is to predict when users are likely to churn based on the available data. As the whole data set is very large, we use PySpark to engineer the data and create binary classification machine learning models. The optimized results are then evaluated based on appropriate metrics.

The whole process as well as the results are summarized in a medium blog post you can find [here](https://medium.com/@a.hampersberger/)

All details are present in the jupyter notebook included in this repository.

## File Descriptions <a name="files"></a>

sparkify.ipynb > notebook to showcase work. Markdown cells and comments are used to assist in walking through the thought process for individual steps.

## Results<a name="results"></a>
The results show that we can predict churn with pretty good accuracy using logistic regression or gradient boosted tree. For both models the AUC score, used as one evaluation metric, was over 90%. The precision and F1 score also showed robust scores.

As mentioned above, the main findings of the analysis can be found in a medium blog post available [here](https://medium.com/@a.hampersberger/).

## Licensing, Authors, Acknowledgements<a name="licensing"></a>

Credit to Udacity for the data.
