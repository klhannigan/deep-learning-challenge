# deep-learning-challenge

Overview:
The purpose of this analysis is to create a model that will help Alphabet Soup with selecting the applicants for funding with the best chance of success in their ventures.

Results:
Data Preprocessing
- The target variable is the "IS_SUCCESSFUL" column from the csv file.
- The feature variables are the other columns except "IS_SUCCESSFUL."
- The "EIN" and "NAME" variables were dropped as they were neither targets or features.

Compiling, Training, and Evaluating the Model
- In the first attempt I used 8 hidden nodes for layer 1, and 5 hidden nodes for layer 2.
- I was not able to achieve the target model performance of 75%.
- To increase the model performance, I dropped more columns, added more hidden nodes, and increased the number of epochs.

Summary:
The model has an accuracy of around 73% overall. To increase the prediction accuracy, we could use a model with greater correlation between input and output. This could be achieved by doing additional data cleaning, or using a model with different activation functions.