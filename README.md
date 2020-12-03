# Neural_Network_Charity_Analysis

## PURPOSE
The purpose of this analysis is to see which organizations will be successful if funded by Alphabet Soup. A Neural Network Model was created to determine which organizations will be successful.

## RESULTS

### Data Preprocessing
•	The target for the model is Is_Successful column.

•	The feature for the model: Application Type, Affiliation, Classification, Use Case, Organization, Active Status, Income Amount, Special Considerations, and the Ask Amount.

•	The variables that are not targets or features are EIN and Name columns. 

### Compiling, Training, and Evaluating the Model

•	In the first model, I added two hidden layers. The 1st hidden layer containing 8 neurons, and the 2nd containing 5) were applied along with a sigmoid activation feature. It is ideal for binary classification by using the outlayers used in the sigmoid classification.

•	In my first model, I achieved 65% accuracy, so I was unable to achieve the target model performance of 75% accuracy.
![](https://github.com/jmajma327/Neural_Network_Charity_Analysis/blob/main/Resources/First%20Model.png)

•	 I had three attempts to achieve the target 75% accuracy. In the first attempt, I dropped the SPECIAL_CONSIDERATIONS column and got 49 % accuracy. In the second attempt, I increased the number of neurons in the first and second hidden layers and got 56% accuracy. In the third attempt, I added a third hidden layer, and got 53% accuracy. Unfortunately, all three attempts I got lower accuracy percentages than the first model.

ATTEMPT 1
![](https://github.com/jmajma327/Neural_Network_Charity_Analysis/blob/main/Resources/Attempt%201%20-%20OPT.png)
ATTEMPT 2
![](https://github.com/jmajma327/Neural_Network_Charity_Analysis/blob/main/Resources/Attempt%202%20-%20OPT.png)
ATTEMPT 3
![](https://github.com/jmajma327/Neural_Network_Charity_Analysis/blob/main/Resources/Attempt%203%20-%20OPT.png)

## SUMMARY

Our focus was to create a more accurate model which was not reached with our Neural Network model. A model that would best fit and attain the goal of 75% accuracy or more would be Support Vector Machine Model because it will create less overfitting and focuses binary classification.


