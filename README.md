# Titanic-Survivor-Analysis
This model is made to predict the survival rate of the passesngers who were on board on Titanic. The survival of the passanger depends on various factors which are used as features for this model.
Analysis is done using classification techniques and algorithms
### Dataset
The Dataset for this model is divided into two groups, training set and test set (train.csv and test.csv)

This dataset is picked from kaggle.com and can be found [here](https://www.kaggle.com/vinaypratap/titanic-survivor-classification)

### Analysis 
The correlation between features was found out by plotting heatmaps and graphs which drew to one conclusion as follows:
   #### Conclusion:
   - Female passengers were prioritized over men.
   - People with high class or rich people have higher survival rate than others.
   - The hierarichy might have been followed while saving the passangers.
   - Passengers travelling with their family have higher survival rate.
   - Passengers who borded the ship at Cherbourg, survived more in proportion then the others.
   
   **TRAINING SET**
  ![titanic correlation(train)](https://user-images.githubusercontent.com/56751947/137724644-634158de-ecd3-497d-b1b7-4a210df516b9.png)

   **TEST SET**
  ![titanic correlation(test)](https://user-images.githubusercontent.com/56751947/137724787-dc7a08fd-22e5-4041-9da6-4bb1f15c3937.png)

   
The features that did not show any correlation with the target variable were dropped from the dataset.

The dataset was then divided into x_train, y_train, x_test, y_test to predict the accuracy of the model.
Different Algorithms have been used here which give different accuracies respectively.

### Machine Learning Algorithms
- `Gaussian Naive Bayes`
- `Decision Tree`
- `Random Forest`
### Accuracies:
- `Gaussian Naive Bayes` = 76.31%
- `Decision Tree` = 77.34%
- `Random Forest` = 80.59%

### Libraries Used:
- `pandas`
- `numpy`
- `Matplotlib`
- `Seaborn`
- `Scikit Learn`


You can also check the code on [GOOGLE COLLAB](https://colab.research.google.com/drive/1vb6n87ScmwBRGzpO6ILZjcmq3sdSGZ4l#scrollTo=l7a9fRibMnda)
