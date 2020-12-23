<!-- Add banner here -->
![Banner](/images/header.png)

# Ratings prediction using NLP ⭐

<!-- Add buttons here -->
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/dewith/amazon-ratings.git/HEAD?filepath=P3_amazon.ipynb)
![GitHub last commit](https://img.shields.io/github/last-commit/dewith/amazon-ratings)
![GitHub](https://img.shields.io/github/license/dewith/amazon-ratings)


This project's aim is to predict the ratings using the users reviews in the spanish Amazon Review Corpus. 

**-> Project status:** [ Completed ]

<br>

## Table of contents
- [Table of contents](#table-of-contents)
- [Project description](#project-description)
    - [Methods used](#methods-used)
    - [Technologies](#technologies)
- [Results](#results)
- [Next steps](#next-steps)
- [Contact](#contact)

<br>

# Project description
[(Back to top)](#table-of-contents)

The importance of customer satisfaction is that it helps us to know the likelihood of a customer making a purchase in the future. Asking customers to rate the degree of satisfaction is a good way to see if they will become regular customers or even brand advocates.

**Objective:** Create a model of Machine Learning to analyse and predict the number of stars of any review based only on the text of it.

## Methods used
* Descriptive statistics
* Data visualization
* Corpus preprocessing 
* Feature engineering 
* Sentiment Analysis 
* Machine learning

## Technologies 
* Python
* Numpy, Pandas, Scipy
* NLTK, Spacy 
* Matplotlib, Seaborn 
* Scikit Learn: Naive Bayes, Linear SVC, etc.


<br>

# Results
[(Back to top)](#table-of-contents)

With the modeling part we were able to obtain an accuracy of 0.55 in test, which is not a particularly high performance. The model that had the best performance was Linear SVC for a very short time. With the analysis of the coefficients we noticed that the most important features for this model are the ones related to the polarity and some of the corpus itself: perfect, good, good, great, bad, not good, meet - not meet, return, etc.


![Results](/images/confusion.png)

<br>

# Next steps
[(Back to top)](#table-of-contents)

To improve the current project it would be convenient to reform the problem, since even if other machine learning algorithms are tested the result will not change much.

If you want to classify reviews of people who feel satisfied with a product in contrast to people to whom the product did not meet their expectations, it would be best to simplify the problem to a binary classification. That is, the model should predict whether the comment is positive or negative. And this would provide more information about the overall quality or satisfaction of the product.

<br>


# Contact
[(Back to top)](#table-of-contents)

You can visit my [**Personal Website**](https://dewith.co/), follow me on [**Twitter**](https://twitter.com/DewithMiramon/), connect with me on [**LinkedIn**](https://linkedin.com/in/dewithm/), or check out the rest of my projects on my [**GitHub**](https://github.com/dewith/).

<br>
<br>

![Footer](/images/footer.png)
