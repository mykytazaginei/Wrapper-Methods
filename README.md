# Wrapper-Methods
In this project, I'll analyze data from a survey conducted by Fabio Mendoza Palechor and Alexis de la Hoz Manotas that asked people about their eating habits and weight. The data was obtained from the [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Estimation+of+obesity+levels+based+on+eating+habits+and+physical+condition+). Categorical variables were changed to numerical ones in order to facilitate analysis.

First, I'll fit a logistic regression model to try to predict whether survey respondents are obese based on their answers to questions in the survey. After that, I'll use three different wrapper methods to choose a smaller feature subset.

I'll use sequential forward selection, sequential backward floating selection, and recursive feature elimination. After implementing each wrapper method, I'll evaluate the model accuracy on the resulting smaller feature subsets and compare that with the model accuracy using all available features
