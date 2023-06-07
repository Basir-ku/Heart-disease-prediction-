# Heart-disease-prediction-
Heart disease prediction  with multiple algorithms.

### Dataset Description: 
The original dataset of nearly 300 variables was reduced to just about 18 variables. The dataset contains 18 variables (9 booleans, 5 strings and 4 decimals). In machine learning projects, "HeartDisease" can be used as the explonatory variable, but note that the classes are heavily unbalanced but with Fixing the weights/undersampling should yield significantly betters results. I treat the variable "HeartDisease" as a binary class ("Yes" - respondent had heart disease; "No" - respondent had no heart disease).

### Work flow:
1. Importing, examing and cleaning the data
2. Encoding, scaling
3. Balancing the dataset with RandomOverSampler
4. Perform ExtraTreesClassifier and observe the accuracy
5. Then perform other algorithm such Random forest, KNN, Decesion tree
6. Evaluate the model: precision, recall, confusion matrix etc
7.Perfom principle component analysis, tuning the model and evaluate the model again

### Result:
I find that ExtraTreesClassifier gives better accuracy where 82734 cases when the model correctly predicted the absence of heart isease and 87769 cases when it correctly predicted heart disease. On the other hand, in 109 cases the model failed to predict heart disease and in 4842 cases it predicted heart disease which did not happen.
