# Neural_Network_Charity_Analysis

## Overview

## Results

* Target Variables
IS_SUCCESSFUL Column

* Variable Features
Every column except IS_SUCCESSFUL column

* Variables that are neither targets or features
EIN, NAME because these two will not have much impact on our results

### Compiling, Training, and Evaluating our Model
* Neural network had 2 hidden layer, 80 neurons in the first layer and 30 neurons in the second layer. Output layer also hes a "relu"  activation function which is sigmoid.
* The target was to achieve 75% accuracy, however an accuracy of score of 52% was achieved.

* Deliverable 1:
![Del1](https://raw.githubusercontent.com/damansandhu/Neural_Network_Charity_Analysis/main/Resources/Del1.png)

* Deliverable 2:
![Del2](https://raw.githubusercontent.com/damansandhu/Neural_Network_Charity_Analysis/main/Resources/Del2.png)

* Deliverable 3:
* Attempt 1: Remove "USE_CASE" column. Accuracy - 56%
![Del31](https://raw.githubusercontent.com/damansandhu/Neural_Network_Charity_Analysis/main/Resources/Del3_1.png)
![Del32](https://raw.githubusercontent.com/damansandhu/Neural_Network_Charity_Analysis/main/Resources/Del3_1_2.png)
* Attempt 2: Adding additional neurons to hidden layers. Accuracy - 59%
![Del33](https://raw.githubusercontent.com/damansandhu/Neural_Network_Charity_Analysis/main/Resources/Del3_2_1.png)
![Del34](https://raw.githubusercontent.com/damansandhu/Neural_Network_Charity_Analysis/main/Resources/Del3_2_2.png)
* Attempt 3: Changing Activation Function. Accuracy - 51%
![Del35](https://raw.githubusercontent.com/damansandhu/Neural_Network_Charity_Analysis/main/Resources/Del3_3_1.png)
![Del36](https://raw.githubusercontent.com/damansandhu/Neural_Network_Charity_Analysis/main/Resources/Del3_3_2.png)

## Summary
After optimization the model ended with an accuracy score of 59%. Before optimization the accuracy score was 52%. An accuracy score of 75% was not achieved, however accuracy did improve to 59% when adding additional neurons. We could increase our accuracy by adding more data into our dataset or by perhaps increasing more neurons. Also, a random forest classifier could be used to further increase our accuracy.
