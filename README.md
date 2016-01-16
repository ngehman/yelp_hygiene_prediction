# Yelp Hygiene Prediction
Prediction competition capstone project code from data mining certification from the University of Illinois at Urbana-Champaign on Coursera.

##Overview
This respositry contains the Python code and data for the capstone compeition project where I placed 3rd out of 186 students.

##Project Objective
Predict whether a set of restaurants will pass the public health inspection tests given the corresponding Yelp text reviews along with some additional information such as the locations and cuisines offered in these restaurants.

##Project Files
####data_mining_specialization_project_project6.pdf
This file contains a brief description and comparison of all the methods used in the model. It includes a summary of the text processing techniques, feature representation and selection, and learning algorithms that were explored in my model.

####Hygiene.tar.gz
The training dataset composed of 546 restaurants, in addition to a testing subset of 12753 restaurants used for evaluating the performance of the classifier. There are three files comtained in this file.
######hygiene.dat
Each line contains the concatenated text reviews of one restaurant.
######hygiene.dat.labels
For the first 546 lines, a binary label (0 or 1) is used where a 0 indicates that the restaurant has passed the latest public health inspection test, while a 1 means that the restaurant has failed the test. The rest of the lines have "[None]" in their label field implying that they are part of the testing subset.
######hygiene.dat.additional
It is a CSV (Comma-Separated Values) file where the first value is a list containing the cuisines offered, the second value is the zip code, which gives an idea about the location, the third is the number of reviews, and the fourth is the average rating, which can vary between 0 and 5 (5 being the best).

####leaderboard.txt
Contains the final leaderboard results from the project where you will see my final standing in 3rd place under the name "ngehman".

####yelp_project6-capstone.ipynb
Contains the Python code used for the predictive model.
