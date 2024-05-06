# Project Description
### Purpose of the Project
- Purpose of this project is to create Binary Classification model that can predict whether a patient was infected with AIDS
  or not based on an array of data about his therapy process
### The Approach Used
- Since this model includes too many attributes, a model that can fit to complex that should be used for this project.
- For this reason, I prefered to use decision-tree-based models that have little differences in their approaches to prevent overfitting
- I experimented on 6 different models I described in my model: CatBoostClassifier, XGBCClassifier, RandomForestClassifier,
  AdaBoostClassifier, MultiLayer Perceptron, Support Vector Machine
- Detailed Descriptions, strengths and weaknesses of each model can be found in the notebook
- Then I used 3 models that performed the best after fitting the data
- After Detailed research, I tuned the hyperparameters for each model I selected
- With these tuned models, I created a VotingClassifier which uses predictions of multiple classifiers to come up with a more robust one

 ### Results
- Even when my models are trained with few data (~2000 entries), they performed well on data
  Specifically, f1-scores:
  - CatBoostClassifier: 0.94
  - XGBC Classifier: 0.93
  - Random Forest Classifier: 0.93
  - Voting Classifier: 0.94

<b>NOTE</b>: For further comments and analysis on models and data, refer to my notebook in which I explained the concepts
and data in more depth 

