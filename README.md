## SONAR()

<p align="center">
  <img src="https://media.giphy.com/media/4xGCaTMCO59le/giphy.gif" alt="animated" />
</p>

Sonar (sound navigation ranging) is a technique that uses sound propagation (usually underwater, as in submarine navigation) to navigate, communicate with or detect objects on or under the surface of the water, such as other vessels.

more about SONAR at [wikipedia](https://en.wikipedia.org/wiki/Sonar)

## OBJECTIVE
--------------------------

**Detecting a Rock or a Mine:** The data set contains the response metrics for 60 separate sonar frequencies sent out against a known mine field (and known rocks). These frequencies are then labeled with the known object they were beaming the sound at (either a rock or a mine).

So here Our main goal is to create a machine learning model capable of detecting the difference between a rock or a mine based on the response of the 60 separate sonar frequencies.

![mine](https://user-images.githubusercontent.com/86251750/138562678-c8b20413-26f2-45db-9b4c-9b42e8300f96.jpg)


**Dataset**
---------------------------

This datset has been taken from [UCI](https://archive.ics.uci.edu/ml/datasets/Connectionist+Bench+(Sonar,+Mines+vs.+Rocks)

**About the Dataset**
--------------------------

The Dataset contains 60 different Frequencies(from Freq1,.....Freq60 with a Label which contains two class that is M(Mine) or R(Rock) hence It is a Binary class Classification Problem.

**Model Accuracies:**
-------------------------
I have used Various models for this classification task-

| Model        | Accuracy       | Model after Standardiztion |
| ------------- |:-------------:|:----------:
| Logistic Regression | 0.769485       |  0.740441 |
| KNeighborsClassifier |  0.808088       |  0.825735
|DecisionTreeClassifier         | 0.740441       |  0.705515
|GaussianNB  |0.648897 |0.648897
|SVM |0.776471| 0.836397
|AdaBoostClassifier|0.813971| - 
|GradientBoostingClassifier| 0.835662 | - 
|RandomForestClassifier|0.818382|-

## Conclusion :

From all above models we can see that **SVM** performs best so let's select it as our final model

***language used***
--------------------------
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)

**Tools**
-----------------------
[![Made withJupyter](https://img.shields.io/badge/Made%20with-Jupyter-orange?style=for-the-badge&logo=Jupyter)](https://jupyter.org/try)    ![NumPy](https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white)   ![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white)   ![scikit-learn](https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=for-the-badge&logo=scikit-learn&logoColor=white)  ![Made with matplotlib](https://user-images.githubusercontent.com/86251750/132984208-76ce70c7-816d-4f72-9c9f-90073a70310f.png)  ![seaborn](https://user-images.githubusercontent.com/86251750/132984253-32c04192-989f-4ebd-8c46-8ad1a194a492.png)

