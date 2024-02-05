# Titanic Dataset Analysis Project

## Overview

This project aims to analyze the famous Titanic dataset, exploring patterns and insights related to the passengers' survival. The analysis includes preprocessing steps, exploratory data analysis, and the development of predictive models.

## Dataset

The Titanic dataset is obtained from the Kaggle competition [Titanic: Machine Learning from Disaster](https://www.kaggle.com/c/titanic/data). It contains information about passengers, such as their age, class, gender, and whether they survived or not.

### Dataset Source

The dataset is sourced from the Kaggle competition [Titanic: Machine Learning from Disaster](https://www.kaggle.com/c/titanic/data).

### Dataset Contents

The dataset includes the following key features:

- `PassengerId`: Unique identifier for each passenger
- `Pclass`: Ticket class (1st, 2nd, or 3rd)
- `Name`: Passenger's name
- `Sex`: Passenger's gender
- `Age`: Passenger's age
- `SibSp`: Number of siblings/spouses aboard
- `Parch`: Number of parents/children aboard
- `Ticket`: Ticket number
- `Fare`: Passenger's fare
- `Cabin`: Cabin number
- `Embarked`: Port of embarkation (C = Cherbourg, Q = Queenstown, S = Southampton)
- `Survived`: Survival status (0 = No, 1 = Yes)
  
## Requirements
- Python 3.6+
- Scikit-learn
- Pandas
- Numpy
- Matplotlib

## Results
Random Forest us the the best model achieved an accuracy of 93.26% on the test set. The ROC curve and other evaluation metrics are included in the Jupyter notebook. According to the model, "Sex" is most predictive.

## License
This project is licensed under the MIT License.

## Contact
If you have any questions, feel free to open an issue or send me a message at ehsan.sepahsalari@gmail.com.
