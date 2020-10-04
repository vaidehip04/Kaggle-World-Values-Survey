# Kaggle-World-Values-Survey

# In this problem we use World Values Survey data. The data is free to be downloaded from the webpage. It is a survey, conducted every few years in a number of countries. Here we use wave 6 data, mostly from 2013-2014. Note that not all countries are participating in each wave.

#  The questions revolve around different opinion topics, including trust, work, religion, family, gender equality, and nationalism. In this problem set we focus on what the respondents think about abortion:

# Please tell if abortion can always be justiffed, never be justiffed, or something in between. The responses range between 1  never justiffable, and 10  always justiffable. Besides of the numeric range 1..10, a number of cases have negative codes (this applies to many variables). These are various types of missing information (-5: missing, -4: not asked, -3: not applicable, -2: no answer, -1: don't know). We treat all these as just missing below.

# The version we use here is a little bit simplified, I have removed a large number of variables that are constructed from the other variables and hence highly collinear with the rest of the data.

# The problem set has two parts: first you try to get as good a prediction as you can using k-NN, logistic regression and SVM methods, and thereafter we will learn about reguarization.
