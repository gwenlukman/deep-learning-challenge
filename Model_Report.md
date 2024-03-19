Report
Data Preprocessing

1. What variable(s) are the target(s) for your model?
It's the 'IS_SUCCESSFUL' column from application_df

2. What variable(s) are the features for your model?
The features variables are every other column that is not 'IS_SUCCESSFUL'

3. What variable(s) should be removed from the input data because they are neither targets nor features?
'EIN' and 'NAME' columns

Compiling, Training, and Evaluating the Model

1. How many neurons, layers, and activation functions did you select for your neural network model, and why?
I used 8 hidden_nodes_layer1 and 5 hidden_nodes_layer 2, I just picked it randomly

2. Were you able to achieve the target model performance?
No I didn't reach 75%

3. What steps did you take in your attempts to increase model performance?
I added more layers, removed more columns

Summary: 
To sum it up, the model was 73% accurate in predicting the classification problem. To achieve higher prediction accuracy, we need to use a model with greater correlation between input and output. This could also be achieved by doing additional data cleanup up front. 