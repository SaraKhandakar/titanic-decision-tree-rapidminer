# Titanic Decision Tree Classification using RapidMiner

## Student Name:
Shara Khandakar

## Objective:
The objective of this lab is to build a Decision Tree classification model using RapidMiner to predict whether Titanic passengers survived or not.

## Steps Performed:

1. Loaded the Titanic dataset using the Retrieve operator.
2. Selected relevant attributes such as Age, Fare, Pclass, Sex, Embarked, SibSp, Parch, and Survived.
3. Replaced missing values to ensure proper model training.
4. Generated new attributes:
   - Age_Group using binning (Child, Teen, Adult, Senior)
   - Fare_Group using binning (Low, Medium, High, Very High)
   - Relatives using SibSp + Parch categorized as None, Few, Many
5. Removed unnecessary attributes and kept only important features.
6. Set Survived as the label using Set Role.
7. Used Split Validation (70% training, 30% testing).
8. Applied Decision Tree model.
9. Evaluated model performance.

## Result:
Model accuracy achieved: 83.52%

## File Included:
- Shara Khandakar_Titanic Decision tree_Assignment.rmp
