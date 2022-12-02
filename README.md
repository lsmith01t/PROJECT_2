#Project 2
The project goal is to predict if someone is making more than 50k or not based on a set of features related to education, race, age, as well as other features. 

The data set contains 48842 unique humans with 13 different features. 

From review of the data 3 of the data features were duplicates or did not serve any predicitive classficiation value so they were dropped. 

Additionally, some adjustments to the data were necessary including binning age into two groups. 

A review of the data allowed the ability to compare hours worked to occupation, age, and race: 

![image](https://user-images.githubusercontent.com/111142792/205345582-31195ee0-a994-40e0-b643-e2fbfbbd4dac.png)

From this visual representation of the data you can see that the averages hours worked is signficantly different amoung occupation, slightly different between males and females, and almost non-existent amoung races. 

The data was skewed towards people making equal to or less than 50k with 76% of the 48842 representing this class. 

To predict the category 3 seperate models were deployed. KNN, Gradient Boosting, and XG Boosting. These models were hypertuned and further optimized to maximize the predictive performance. 

From this analysis the model that performed the best was the base KNN model without any PCA or hypertuning features added. 


