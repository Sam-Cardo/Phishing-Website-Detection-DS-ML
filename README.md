# Phishing Website Detection
  * Samuel Cardo C00328718
  * 2026-09-29 – 2026-11-27
  * Data Science and Machine Learning Sem 1 Year 4

### Linkedin
* https://www.linkedin.com/in/sam-cardo-82a71b279/



## Topic
Phishing website detection

## Overview
This portfolio will be focusing on making a system that uses machine learning to be able to determine weather or not its capable of figuring out if a website is legitimate or has a phishing capability or element embedded into its system. I hope that this project will show great data handling skills, and other techniques to answer the questions that I want to find out about. Finally, this portfolio will also include many important and professional aspects like using a linked in profile and GitHub profile/ repository.

##  Dataset
Link: https://www.kaggle.com/datasets/mdsultanulislamovi/phishing-website-detection-datasets?select=dataset1.csv 

## Technologies Used 
*	Python
*	Jupyter Notebook
*	Panadas


## Machine Learning
The type of ML for this project I have choose to do supervised learning of ML and focusing on classification and use three version of it being logistic regression, decision tree and random Forest because of the advantages of them being able to handle larger datasets, easy to implement and interpret for the users, linear separable data and the many more advantages that from this type of classification ML.

## Question
 Can machine learning determine weather a website can be found as legitimate or phishing website.

## Why I choose this topic
I choose this topic when I was doing research for topic, I came across this and it piqued my interest because I was always curious because I have always been aware that website can contain phishing elements that are trying to steal important information about you. Also, I find that this is truly a real-world problem that so many occurrences where people that have less knowledge of what to look for can be a victim of this problem and be totally unaware until it is too late for them and cause a big impact on their lives.


## Project Implementation 
*	Loading and inspecting the datasets that I have found from Kaggle using Jupyter notebook and panadas.
*	Explored those datasets and all the features that were involved inside of this dataset.
*	Prepared the data to be used with machine learning.
* Looked at different models to go over the datasets and see which had the best predictability and accuracy and these models gave me for my final model.
*	Tested the performance of these models using different metrics like accuracy, precision, recall and cross validation.
*	Finally, I saved the Random Forest model once it was trained.

## Dataset Infomation
* Total Rows: 11,056
* Columns: 32
* Features: 32
* Legitimate websites (1): 6,157
* Phishing websites (-1):  4,898

### Explanation:
How I prepared the data for machine learning was that I first loaded the the dataset into the notebook using pandas then I need to check what dimensions that this data set had like all the column names. Also, I needed to clean the column names and make the data into a suitable format for Jupiter notebook to make it usable format that was all done by using pandas and loading the csv that Kaggle provided to me and I noticed that it had 11,055 records inside of it with 32 columns with 32 features. After preparing this data into usable data I then used a function from scikit-learn to divide it into training data and testing too for my model to determine many things about this dataset and this was all done using 80/20 split 80% for the to train the model and then the 20% was for the performance of it. 

## Model Development
For this project, I have chosen three different ways of looking at this data by using three supervised clarification Machine learning: Logistic regression, Decision Tree and Random forest. The reason for these types of machine learning to look at this data was because that in my opinion for this datasets these ways of looking at the data was the most optimal and effective at identifying the phishing websites. Logistic regression was used to see the separation of the data into different categories and it provided a good baseline for this project compared to the more complex models out there.

Decision tree was selected for this project because it is able to make a series of decisions based on the input features that are in the dataset to clarify those records. another thing was that I found that it was able to make a straightforward approach for this project just like the logistic regression it was just easier to understand it.

Finally, Random Forest was used because it can combine multiple of those Decision tress to make a final prediction by using the multiple trees in that way rather than relying on just one decision tree for my model to analyze the data. It can also provide a better performance than the other types of machine learning that I looked at before and it can reduce the chance of error on just one decision tree being used to make prediction. Overall this machine was the best option mainly due to its performance and precision score.



## Results and conclusion: 

Here are a few examples showing the difference of the three models and their accuracy and recall

###  Model                       Test Accuracy (%)       Phishing Recall (%) 
* 0  Logistic Regression              92.90                90.20
* 1  Decision Tree                    97.11                96.22
* 2  Random Forest                    97.42                96.12

### Another comparison 
* Logistic Regression training accuracy: 92.76345545002262
* Decision Tree training accuracy: 99.01628222523745
* Random Forest training accuracy: 99.01628222523745

### References
* https://scikit-learn.org/stable/index.html
* https://docs.jupyter.org/en/latest/
* https://machine-learning-with-python.readthedocs.io/en/latest/
* https://colab.research.google.com/github/ubc-library-rc/intro-machine-learning/blob/main/Examples/machine-learning-examples.ipynb
* https://www.tutorialspoint.com/machine_learning_with_python/machine_learning_with_python_jupyter_notebook.html
* https://developers.redhat.com/articles/2021/05/21/introduction-machine-learning-jupyter-notebooks#using_a_jupyter_notebook_for_machine_learning
* https://github.com/jxareas/Machine-Learning-Notebooks
* https://github.com/niedzwiedz89/book_ml_ipynb
* https://mljourney.com/building-your-first-machine-learning-model-in-a-jupyter-notebook/
* https://dev.to/thelogicwarlock/from-notebook-to-model-a-practical-guide-to-jupyter-for-machine-learning-3dm5
* https://github.com/ageron/handson-mlp
* https://www.youtube.com/watch?v=5pf0_bpNbkw
* https://github.com/justmarkham/scikit-learn-videos









