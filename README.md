# Machine_Learning

This data set is looking at the demographics of weekday, underaged drinkers, to try to predict risk factors. 
This data is sourced from Kaggle: https://www.kaggle.com/datasets/uciml/student-alcohol-consumption?select=student-mat.csv

This file has 334 rows and 33 features. In the features, this is demogrpahic and education infromation about the survey taker, along with information about their parents educational and professonal carrier. 


![image](https://github.com/kassiedancer92/Machine_Learning/assets/133593433/bc43e567-bcf5-4f1b-91d8-ca411fab8a11)

This image shows the correaltion of all the features in the dataset. There is a strong correaltion amoung grades and parents education. Pertaining to our target, there is the strongest coreelation between week day drinking, going out, and weekend drinking. There are smaller, positive, correlations between weekday drinking, age and travel time to school

![image](https://github.com/kassiedancer92/Machine_Learning/assets/133593433/d9beb0f6-8a04-4ca9-a803-cf684a758cc6)

This graph shows that thought who go out the most, also partake in week day drinking the most. Those that go out moderatly, also drink moderatly. Most kids rarely go

<img width="373" alt="PNG image" src="https://github.com/kassiedancer92/Underage_Drinking-/assets/133593433/dcd913f2-84e8-4c04-b332-3aa68929a76e">

The largest group is 16 and 17 year olds who rarely drink during the week. However, those that drink the most during the week are also 16 and 17 year olds.

The model that would be best used for this data set would be the Regression Tree with PCA as it has the highest testing accuracy out of the regression trees tired. The R^2s of the random forrest models are low in the testing data even though they are higher in the training data, which shows an overfit model. 

This model this fairly solve the business problem.

It would be reccomendened to narrow down the amount of features to have a less over fitted model. This would help us have more accurate predictions of risk factors for youth who drink during the week. Secondly, there seems to be weak correlations overall with weekday drinking, according to the heatmap. Explanding the population and narrowing the varitiy of numerical choices may help increase correlations.
