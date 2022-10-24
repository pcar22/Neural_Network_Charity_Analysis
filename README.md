# Neural_Network_Charity_Analysis

## Overview of the analysis

The purpose of this challenge is to use the features in the provided dataset to help Beks create a binary classifier that is capable of predicting whether applicants will be successful if funded by Alphabet Soup.

From Alphabet Soup’s business team, Beks received a CSV containing more than 34,000 organizations that have received funding from Alphabet Soup over the years. Within this dataset are a number of columns that capture metadata about each organization.

## Results

- Data Preprocessing
    - I am using the 'Is_Successful' as the target for our model.
    - After dropping 'EIN', 'NAME' AND 'IS_SUCCESSFUL', the remaining columns will be our features

    ![drop_ein_name.png]()

- Compiling, Training, and Evaluating the Model
    - The first attempt I used 2 hidden layers, 30 neurons in the 1st layer and 10 in the 2nd layer. The activations were 'relu' for the inputs and 'sigmoid' for the output.
    - The second attempt I used 2 hidden layers, 6 neurons in the 1st layer and 2 in the 2nd layer. The activations were 'relu' for the inpusts and 'sigmoid' for the output.
    - The third attempt I used 3 hidden layers, 20 neurons in the 1st layer, 30 neurons in the 2nd layer, and 30 neurons in the 3rd layer. The activations were 'tanh' for the inputs and 'sigmoid' for the output.

I did not achieve the target model performance. 

The steps taken to try and increase performance are listed above.

![first_attempt.png]()

![second_attempt.png]()

![third_attempt.png]()


## Summary
Increasing the layers and adjusting the neurons had some affect, however I was not able to achieve the target accuracy. Adding a third hidden layer, I was able to get close to the target of 75%. Changing the neurons with only 2 hidden layers achieved 73%, that was done as a fourth attempt. The Gradient Boosting Classifier model was used to try and achieve increased predictive accuracy and the result was about the same as the other models.

I recommend we review the dataset and with some more cleaning we may be able to achieve better accuracy results.





