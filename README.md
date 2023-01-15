# Neural_Network_Charity_Analysis

## Analysis

### Overview

With machine learning and neural networks, we’re using the features in the provided dataset to help create a binary classifier that can predict where to make investments and whether applicants will be successful if funded. 

### Results

- My attempts were not very successful attempt with 50%

![model3accuracy](https://user-images.githubusercontent.com/110438612/212504664-fd6e7ab5-7a86-4633-a3e4-cfcd0f506231.png)

1. Data Preprocessing

	‘IS_SUCCESSFUL’ is the target for the model.
	'APPLICATION_TYPE', & 'CLASSIFICATION', 'USE_CASE', 'ORGANIZATION', 'INCOME_AMT', &'SPECIAL_CONSIDERATIONS' are all considered to be features for the model.
	‘EIN’ & ‘NAME’ neither targets nor features and should be removed from the input data.

2. Compiling, Training, and Evaluating the Model

	70 Neurons & 40 Neurons with 2 hidden layers and 1 outer layer using relu, relu and sigmoid respectively.
	I was unable to achieve the target model performance.
	I thought I was on the right path until I realized I was switching my loss numbers with my accuracy.

### Summary

- With more practice and resources using machine learning and neural networks, we’ll find the right model and hidden layer combination to increase accuracy. 



