Download and read the csv.
Studied columns
Age columns have Null values.And also found some wrong entries in age check Min.
Tommorow check survive vs other columns by graphs and clean the data.

#Day 2 – Cleaning

Dropped columns:Name,passengerId,Cabin,ticket

Filled missing Age with median

Filled missing Embarked with mode

No. of missing values after cleaning:0

Note: Age min and Fare min are valid

EDA Observations(graphs)

Females survived more than males 

1st class survived the most 

People embarked at C had higher survival rate 

Most passengers were in 20–40 age range, peak around 30.

Day 3 – Preprocessing

Encoded categorical columns:SexEmbarked

Total features after encoding: 9

X shape: 891,9

y shape: 891,1

Train-test split: 80/20
