Dataset Analysis Report: Task 1

1. Dataset Selection

Chosen Dataset: Titanic Dataset.

Size: 891 rows and 12 columns.
+2

2.Feature Identification
Numerical Features: Age, Fare, SibSp (siblings/spouses), Parch (parents/children).

Categorical Features: Sex, Embarked, Name, Ticket.

Ordinal Features: Pclass (represents 1st, 2nd, and 3rd class levels).

Binary Features: Survived (0 or 1), Sex (Male/Female).

3.Data Understanding & Statistical Summary
Technical Summary: The df.info() command revealed that most columns are integers or objects, while Age and Fare are floats.

Statistical Insights: Using df.describe(), the average age is approximately 29.7 years, and the average fare is 32.20 units.

Distribution: df.value_counts() shows that 61.6% of passengers in this dataset did not survive.

4.Target vs. Input Features
Target Variable: Survived (Predicting if a passenger lived or died).

Input Features: Pclass, Sex, Age, SibSp, Parch, Fare, and Embarked.

5.Data Quality Observations
Missing Values: \* Age: 177 missing entries.

Cabin: 687 missing entries (significant data loss).

Embarked: 2 missing entries.

Imbalance: There is a moderate imbalance as the number of "Not Survived" entries is significantly higher than "Survived" entries.

6.Machine Learning Readiness
Suitability: The dataset is suitable for machine learning because it has a clear target variable and a mix of strong features (like Gender and Class) that historically correlate with survival.

Conclusion: Despite missing values in Age, the dataset size (891) is sufficient for training basic classification models after cleaning.
