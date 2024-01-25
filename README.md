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
Were you able to achieve the target model performance?
* No following the intrusctions I was only able ot get to 73% but I did try three optimization trials.
  
What steps did you take in your attempts to increase model performance?
*

Summary: Summarize the overall results of the deep learning model. Include a recommendation for how a different model could solve this classification problem, and then explain your recommendation.
* I was only able to get to 73% accuracy after three optimization trials
* Due to not being able get past 75% it would be good to look into Random Forest and SVM.
