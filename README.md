# Web-Information-Extraction-Text-Classification

![Can Machines distinguish between "Loans" & "Credit Cards"](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTK6OPickg91Rkj4IftgkJb95G2wDLGngjjwly9COhEUgFnC3CD)

Saving time is what machines do best. Imagine having the super power to find within seconds material in which you are interested, from among a collection of numerous random posts. This project works towards achieving this ability by using advanced natural language processing tools to correctly identify topics to which a reddit post belongs.

The resultant machine learning model could be adapted for post filtering, post identification, etc. Further analysis could also be done to identify associative keywords for various topics.

Two highly similar topics were chosen for this project("Loans" and "Credit Cards"). This was to build a model which could strongly differentiate , even between similar topics. The NLP techniques first identified most frequent words within posts and their count in each individual post. Following this the Logistic regression ML model, Naïve Bayes model and a neural network model was trained on a random subset of the scraped data.

The Logistic regression model correctly differentiated between posts achieving an accuracy of 95%. Naïve Bayes & neuralnetworks were not far behind with a classification accuracy of close to 93 % . Overall the project was highly successful and it serves as a great starting point to classify texts.

Files in the repository:

Please view these in sequence to undersand the project in its totality

1) Data extraction from Reddit (https://github.com/antonypaulson/Web-Information-Extraction-Text-Classification/blob/master/ML_Models_and_evaluation.ipynb)

2) Exploratory Data Analysis (https://github.com/antonypaulson/Web-Information-Extraction-Text-Classification/blob/master/Reddit_Exporatory_Data_Analysis.ipynb)

3) Machine Learning model application and evaluation (https://github.com/antonypaulson/Web-Information-Extraction-Text-Classification/blob/master/ML_Models_and_evaluation.ipynb)
