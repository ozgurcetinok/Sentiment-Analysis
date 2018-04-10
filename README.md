# Sentiment-Analysis
Classifying Amazon Customer Reviews using Linear Regression, Logistic Regression and Artificial Neural Networks

This project includes a Jupyter Notebook File and a datafile in JSON format.

project.ipynb

Cell_Phones_and_Accessories_5.json

Data File can be downloaded from http://jmcauley.ucsd.edu/data/amazon/ . Thanks to Professor Julian McAuley, I was able to access to the Amazon Customer Reviews about Cell Phones and Accessories between May 1996 - July 2014.

This dataset includes reviews (ratings, text, helpfulness votes), product metadata (descriptions, category information, price, brand, and image features), and links (also viewed/also bought graphs).

If you're using this data for a class project (or similar) , you can use the dataset in the website.

To run the program:

Open the Jupyter Notebook and ipynb file. Keep the data file (JSON) in the same directory with the ipynb file. Start running from the first cell till the end respectively.

External libraries such as pandas, re, numpy, sk learn and nltk are used. All are publicly available. 

If you have trouble importing these, type “!pip install libraryname” in a notebook cell o install it. If you have UTF-8 error, you have to fix your bash profile by adding following
commands to it.

--export LC_ALL=en_US.UTF-8

--export LANG=en_US.UTF-8

Step by step explanation about the code is provided in the Jupyter Notebook.
