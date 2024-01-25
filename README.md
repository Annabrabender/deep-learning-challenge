# deep-learning-challenge

The nonprofit foundation Alphabet Soup wants a tool that can help it select the applicants for funding with the best chance of success in their ventures. With your knowledge of machine learning and neural networks, you’ll use the features in the provided dataset to create a binary classifier that can predict whether applicants will be successful if funded by Alphabet Soup.

The optimization models can be found in the folder model and the preprocessing first code is in the seperate notebook.


REPORT

Overview of the analysis: This analysis was to use machine learning and neural networks to create a binary classifier to predict whether applications will be successful in achieving funding.


Data Preprocessing
What variable(s) are the target(s) for your model?
* The target variable was the IS_SUCCESSFUL variable as that is what we are looking for.
What variable(s) are the features for your model?
* The variables that are features are application type, affiliation, classification, use case, organization, status, income amount, special considerations, and their ask amount.
  
What variable(s) should be removed from the input data because they are neither targets nor features?
* The features that should be removed are the identification columns which are EIM and NAME as that should not have any affect on whether an application receives funding.



Compiling, Training, and Evaluating the Model
How many neurons, layers, and activation functions did you select for your neural network model, and why?
* The final neural network had three hidden layers and one output layer. The first hidden layer has the activation function of relu and the other layers were sigmoid. There were 20 hidden nodes in the first layer, 27 hidden nodes in the second layer, and 3 hidden nodes in the third layer. I used trial and error and also looked at Tensor Flow.

Were you able to achieve the target model performance?
* No following the intrusctions I was only able ot get to 73% but I did try three optimization trials.
  
What steps did you take in your attempts to increase model performance?
* I tried adding more hidden layers
* I added more nodes in the hidden layers
* I changed the activations to include more sigmoids 



Summary: Summarize the overall results of the deep learning model. Include a recommendation for how a different model could solve this classification problem, and then explain your recommendation.
* I was only able to get to 73% accuracy after three optimization trials
* Due to not being able get past 75% it would be good to look into Random Forest and SVM.
* It would be interesting to see if the identification columns may make a difference, although that really shouldn't factor into the model since it is not something that should indicate funding.
