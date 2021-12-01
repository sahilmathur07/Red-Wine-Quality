# Red-Wine-Quality

# Libraries Used

  1. Pandas
  2. Numpy
  3. Scikit-Learn
  4. Seaborn
  5. Matplotlib

I used pandas for reading and manipulating data

I used numpy for using array

I used Scikit-Learn for building machine learning model

I used seaborn for visualizations

I used matplotlib for visualization and because seaborn plots are build using matplotlib

# Problem Statement

As we know that there are so many red wine brands in the market so need check the quality of red wine before consuming it because if the quality of wine is low then it is harmful for our health. So i created a machine learning model to predict the quality of red wine.

# Approach 

![image](https://user-images.githubusercontent.com/37149683/144063129-3614c564-2540-4320-958c-47c520f77c14.png)

Above countplot shows that there are less wines with 3,4,7,8 quality and large number of 5 and 6 quality wines and for our machine learning model it is difficult to correctly predict the class with less data points. So i combined 3,4,5 and 6,7,8 into High and Low Quality
And after dividing in to two classes our target variable looks like below diagram.

![image](https://user-images.githubusercontent.com/37149683/144239399-b90aaeff-209a-45c0-886e-a7954c043b65.png)

Now the target variable is distributed in balanced ratio

#  Machine Learning Algorithms used

I used Logistic Regression, Random Forest Classification, Gradient Boosting Classifier, Voting Classifier and Stacking Classifier

# Results

Achieved a accuracy of 82% using Stacking Classifier
