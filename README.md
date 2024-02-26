# deep-learning-challenge

The purpose of this analysis is to develop a deep learning model using TensorFlow/Keras to predict whether applicants will be successful if funded by Alphabet Soup. The model will be trained on a dataset containing various features about each applicant, such as their application type, affiliation, classification, use case, organization type, and income amount. The target variable for the model is 'IS_SUCCESSFUL', indicating whether an applicant was successful after receiving funding.

Data Preprocessing:
Target Variable(s): The target variable for the model is 'IS_SUCCESSFUL'.
Feature Variable(s): The feature variables for the model include all other columns except for 'EIN' and 'NAME', which are identification columns and are removed from the input data.
Variables Removed: The 'EIN' and 'NAME' columns were removed from the input data as they are neither targets nor features.

Compiling, Training, and Evaluating the Model:

- Attempt 1:
Epochs: 100
Batch Size: 50
Loss: 0.5587
Accuracy: 0.7241
- Attempt 2:
Epochs: 300
Batch Size: 50
Loss: 0.5582
Accuracy: 0.7284
- Attempt 3:
Epochs: 300
Batch Size: 80
Loss: 0.5597
Accuracy: 0.7264

Among the attempts, Attempt 2 with 300 epochs and a batch size of 50 achieved the highest accuracy of 72.84%. This indicates a slight improvement over Attempt 1 (72.41%), which used fewer epochs. However, Attempt 3 with the same number of epochs as Attempt 2 but a larger batch size yielded slightly lower accuracy (72.64%).

While Attempt 2 showed the best performance in terms of accuracy, the differences between the attempts are relatively small.  
In summary, although the deep learning model has potential for predicting the success of applicants, it needs more adjustments and testing to make it more accurate . Also, we can try using decision trees to help with this classification problem.
