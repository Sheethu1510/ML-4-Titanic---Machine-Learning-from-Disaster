# Titanic Survival Prediction

## Objective

This project aims to build a predictive model to determine which types of passengers were more likely to survive the Titanic disaster. Using a variety of passenger attributes, the model seeks to provide insights into the key factors that influenced survival outcomes.

## Dataset Information

The dataset includes detailed information about the passengers aboard the Titanic during its maiden voyage. It contains a mix of numerical, categorical, and textual data related to each individual's demographic profile and travel conditions. The dataset is commonly used as an introductory machine learning problem and serves as a strong case for classification-based tasks.

## Data Dictionary

| Variable | Description                       | Notes                                          |
| -------- | --------------------------------- | ---------------------------------------------- |
| survival | Survival status                   | 0 = No, 1 = Yes                                |
| pclass   | Ticket class                      | 1 = 1st, 2 = 2nd, 3 = 3rd                      |
| sex      | Sex of the passenger              | Male / Female                                  |
| age      | Age in years                      | May contain missing values                     |
| sibsp    | Number of siblings/spouses aboard | Integer                                        |
| parch    | Number of parents/children aboard | Integer                                        |
| ticket   | Ticket number                     | Categorical/text                               |
| fare     | Fare paid                         | Float                                          |
| cabin    | Cabin number                      | Many missing values                            |
| embarked | Port of Embarkation               | C = Cherbourg, Q = Queenstown, S = Southampton |

## Approach

The project workflow includes the following steps:

* **Data preprocessing**: Handle missing values, clean data, and convert categorical variables
* **Exploratory Data Analysis (EDA)**: Visualize distributions and identify key patterns
* **Feature engineering**: Extract and transform relevant features such as family size or title
* **Modeling**: Train and compare various machine learning algorithms
* **Evaluation**: Assess model performance using accuracy score.

## Outcome

By analyzing passenger attributes, the model identifies which factors—such as class, gender, age, or family connections—had the most impact on survival rates. The findings can offer historical insight and serve as a foundation for more complex classification tasks in data science.
