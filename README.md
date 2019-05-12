Necessary Installation

The problem is coded in python 3.7 version. You can download python from the link https://www.python.org/downloads/. 

I also used jupyter notebook from anaconda suite which  also contains python internally. You can download anaconda form here https://www.anaconda.com/distribution/

Motivation:

This project is my capestone project  from TERM two of the udacity datascience nanodegree program. I would like to thank udacity for providing me an opportunity to work on this problem and helped me put my gained skills in implementation.


This is the project on spam classification on the top trending videos in youtube. The Data scourse is from the UCI repo.(link below). 

The dataset consists of five CSV files and one python notebook.The soultion of the problem can found in the python notebook. 

Source: https://archive.ics.uci.edu/ml/datasets/YouTube+Spam+Collection#

This corpus has been collected using the YouTube Data API v3.

Data Set Information:

The table below lists the datasets, the YouTube video ID, the amount of samples in each class and the total number of samples per dataset. 

Dataset --- YouTube ID -- # Spam - # Ham - Total 

Psy ------- 9bZkp7q19f0 --- 175 --- 175 --- 350 

KatyPerry - CevxZvSJLk8 --- 175 --- 175 --- 350 

LMFAO ----- KQ6zr6kCPj8 --- 236 --- 202 --- 438 

Eminem ---- uelHwf8o7_U --- 245 --- 203 --- 448 

Shakira --- pRpeEdMmmQ0 --- 174 --- 196 --- 370 

Note: the chronological order of the comments were kept. 


Attribute Information:

The collection is composed by one CSV file per dataset, where each line has the following attributes: 

COMMENT_ID,AUTHOR,DATE,CONTENT,TAG 


Description of the files 

The names of the dataset in the CSV format are 

Youtube01-Psy

Youtube02-KatyPerry

Youtube03-LMFAO

Youtube04-Eminem

Youtube05-Shakira


The Name of the python notebook is youtube_spam_classfier.ipynb


After running the model the model acheived the F1 score of 95 % . I used logistic regression in this case.

Improvements:

If youtube implement this kind of spam classification for their comments, the users could enjoy a better user experience on the user side and on the company end there will not be a necessary for additional hardware for their storage and by classifying the spam comments they cal also stop abusive content in their systems.



