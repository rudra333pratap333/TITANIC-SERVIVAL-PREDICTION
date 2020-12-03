# TITANIC-SERVIVAL-PREDICTION
Titanic Survival Prediction :-The sinking of the RMS Titanic is one of the most infamous shipwrecks in history.On April 15, 1912, during her maiden voyage, the Titanic sank after colliding with an iceberg, killing 1502 out of 2224 passengers and crew. 
This sensational tragedy shocked the international community and led to better safety regulations for ships. One of the reasons that the shipwreck led to such loss of life was that there were not enough lifeboats for the passengers and crew. Although there was some element of luck involved in surviving the sinking, some groups of people were more likely to survive than others,such as women, children, and the upper-class. 

In this challenge, we ask you to complete the analysis of what sorts ofpeople were likely to survive.
In particular, we ask you to apply the tools of machine learning to predict which passengers survived the tragedy.

Overview
The data has been split into two groups:

1) training set (train.csv)   891 Rows
2) test set (test.csv)        418 Rows

The training set should be used to build your machine learning models.
For the training set, we provide the outcome
(also known as the "ground truth")for each passenger.

Your model will be based on "features" like passengers' gender
 and class.
You can also use feature engineering to create new features.

The test set should be used to see how well your model performs on unseen data.
For the test set, we do not provide the ground truth for each passenger.
It is your job to predict these outcomes.
For each passenger in the test set, use the model you trained to
predict whether or not they survived the sinking of the Titanic.

Description about data:-
Below is a brief information about each columns of the dataset:

1)PassengerId: An unique index for passenger rows. It starts from 1 for first row and increments by 1 for every new rows.

2)Survived: Shows if the passenger survived or not. 1 stands for survived and 0 stands for not survived.

3)Pclass: Ticket class. 1 stands for First class ticket. 2 stands for Second class ticket. 3 stands for Third class ticket.

4)Name: Passenger's name. Name also contain title. "Mr" for man. "Mrs" for woman. "Miss" for girl. "Master" for boy.

5)Sex: Passenger's sex. It's either Male or Female.

6)Age: Passenger's age. "NaN" values in this column indicates that the age of that particular passenger has not been recorded.

7)SibSp: Number of siblings or spouses travelling with each passenger.

8)Parch: Number of parents of children travelling with each passenger.

9)Ticket: Ticket number.

10)Fare: How much money the passenger has paid for the travel journey.

11)Cabin: Cabin number of the passenger. "NaN" values in this column indicates that the cabin number of that particular passenger has not been recorded.

12)Embarked: Port from where the particular passenger was embarked/boarded.

Contents:
1)Import Necessary Libraries <br />
2)Read In and Explore the Historic Data <br />
3)Data Analysis <br />
4)Data Visualization <br />
5)Cleaning Data <br />
6)Finally Calclate the Accuracy of the Model <br />
