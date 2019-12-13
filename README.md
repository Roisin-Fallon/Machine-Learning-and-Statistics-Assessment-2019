# Machine-Learning-and-Statistics-Assessment-2019

<p align ="center"><img src="images/house.jpg" alt="Boston Housing " width="300" height="300" title="Boston Housing"/></p>

## Introduction

This assessment concerns the well-known Boston Housing dataset and the Python packages seaborn and jupyter notebook. This project can be brokedn into 3 distinct sections: 

1. <b><i>Describe: </i></b>Use descriptive statistics and plots to describe the Boston House Prices dataset.
2. <b><i>Infer:</i></b>Use inferential statistics to analyse whether there is a signiﬁcant diﬀerence in median house prices between houses that are along the Charles river and those that aren’t. 
3. <b><i>Predict:</i></b> Use keras to create a neural network that can predictthe median house price based on the other variables in the dataset.

Please find the full breakdown of the project in PDF form <a href=https://github.com/Roisin-Fallon/Machine-Learning-and-Statistics-Assessment-2019/blob/master/project.pdf> here </a>


## How to download the repository:
1. Download the repository from the following link <a href=https://github.com/Roisin-Fallon/Machine-Learning-and-Statistics-Assessment-2019/blob/master/Project.ipynb> here</a>
2. Click the clone or download button towards the right of your screen
3. Download and unzip this file. Save the unziped file to a location on your desktop where it is easily accessible
4. Open the command line and navigate to the location of your downloaded file using a series of cd commands 
5. Type Jupyter notebook into the command line which will open a web server where you can now see the files you have downloaded. 
6. Open the Tips Project.ipynb by clicking  on it now you will be able to view the tips project

## Conclusion: 

Throughout the project I have explained what the code is telling us about the dataset. In this conclusion I will summarise the interesting things that I have noticed from each of the 3 section.

Section 1: There are 506 houses and there are 13 features to which MEDV was added making it 14. I learned how to calculate the percent of missing values and learned that if more than 70% of data is missing this sould be excluded as it would impact results. Correlation allowed us to see what variables are strongly correlated. Interestingly MEDV has a strong positive correlation with RM at 0.7; MEDV has a strong negative correlation with LSAT -0.74. As stated earlier the full findings are explained under each of the plots or lines of code

Section 2: We can reject the null hypothesis as the t value is significantly less than the critical value. At a level of 0.05, there is a one in twenty chance that we incorrectly reject the null hypoothesis. Thus we can say that thie is significant difference in the mean house prices for houses along the Charles River and those that are not along the Charles River.

Section 3: This part of the project was extremely time consuming and involved alot of trial and error. Testing different combinations to get the best neural network model possibel. It is important to understand that the model presented here may not be the best representation of the dataset. One of the possible issues is the size of this dataset in general is small. Another option for this section was to use the statsmodel and select the columns that have strong reltionship with house price but do not show multicollinearity (relationship between the variables themselves). However, I feel with this project I have gained a great deal of understanding on how to critically analysis a dataset and create neural networks using keras which was the overall goal of this project