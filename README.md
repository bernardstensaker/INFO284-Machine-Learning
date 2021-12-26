# INFO284-Machine-Learning
Exam for INFO284 Machine learning course at the University of Bergen spring 2021.

## File information:
[Exam.pdf](https://github.com/bernardstensaker/INFO284-Machine-Learning/blob/main/Exam2021.pdf) is the exam text for this assignment.

[INFO284 Machine Learning Spring 2021](https://github.com/bernardstensaker/INFO284-Machine-Learning/blob/main/INFO284%20Machine%20Learning%20Spring%202021%20students%20245%20and%20213.ipynb) contains all code used in this project.

[nyc-rolling-sales.csv](https://github.com/bernardstensaker/INFO284-Machine-Learning/blob/main/nyc-rolling-sales.csv) is the dataset used for applying machine learning models.

## About the assignment:
This assignment was an exam in the subject INFO284 during the spring semester of 2021 at the University of Bergen. This is a short summary of the assignment, the full version can be read [here](https://github.com/bernardstensaker/INFO284-Machine-Learning/blob/main/Exam2021.pdf).

Using a dataset from [Kaggle](https://www.kaggle.com/new-york-city/nyc-property-sales) about New York City housing sales, build at least five machine learning models from [this](https://github.com/bernardstensaker/INFO284-Machine-Learning/blob/main/nyc-rolling-sales.csv) data, to predict or classify a relevant target. One or two of the five machine learning models has to be a neural network. It has to be delivered as a well-commented Jupyter notebook. In the end the code has to return the results of the experiments as well as explanations on important properties of the data, how you preprocessed it, how you decided parameters for the models and lastly comparing the five models against each other. 

This was a group project for up to 3 people, I was in a group with one student.

For our solution we explored and focused on looking at how different encoding of categorical data work with six different machine learning models: Linear Regression, Ridge Regression, Lasso Regression, Random Forest Regressor, K Neighbor Regressor and lastly Neural Network (MLP Regressor). We discuss how both encoding, preprocessing and parameter tuning all have different effects on the machine learning models and how they perform. The assignment is well-commented and has a summary of our findings at the bottom of the ipynb file.

## How to run:
The reccomended way of running this project is downloading the ipynb file, as well as the csv file containing the data itself, and making sure these two are in the same folder (or else you have to find the file path). There are a few libraries that are required to download withing jupyter, all of these should be listed below under libraries, these can also be found at the top of the ipynb file. 

## Built using:

### Languages:
- Python

### Libraries:  
- Pandas
- NumPy
- Seaborn
- Scikit-learn
- Matplotlib
