If the field of ML was Doc Brown, this introduction to machine learning tutorial is Marty McFly. 

You'll not be able to invent time travel, but you'll be able to stumble and fall all the way to saving the day. 

# References

- This [http://ciml.info/dl/v0_9/ciml-v0_9-all.pdf], 
- This [https://www.ics.uci.edu/~welling/teaching/ICS273Afall11/IntroMLBook.pdf], 
-  and this [http://learnds.com/]

# Learning?

- Ability to **generalize** from specific examples
	- Incorrect to ask questions about a pottery course in a Machine Learning Course
	- Incorrect to ask the _same_ question that was taught - even if with different data
	- Expected to extrapolate or **infer** answers from the questions that were studied

# Is there a Glossary?

- Helpful: http://alumni.media.mit.edu/~tpminka/statlearn/glossary/
- Another: https://www.analyticsvidhya.com/glossary-of-common-statistics-and-machine-learning-terms/
- Yet another: https://martin-thoma.com/ml-glossary/

# 'Paradigms' or Types

You may not care about this *eventually*, but we humans learn by classifying, so here's a common way to bucket the problems of machine learning:

- **Supervised learning**: Input a **vector**, find out what **class**/**lable** the vector belongs to using a **model**. Learn using existing **labelled** data where a variety of vectors have already been assigned labels.
- **Unsupervised learning**: Input a vector, output a **transformed value** (or a vector) that solves a practical problem (for e.g. **clustering, outlier detection, dimensionality reduction** etc.). Learn using data that has no labels.
- **Semi-supervised learning**: Just like supervised learning, input a vector, find out what class/lable the vector belongs to. Learn based on data that has labels, but *a lot of the lables are missing* - you have data that can better inform your probability distributions, so this could improve the classification. 
- **Reinforcement learning**: Pick an action to maximize average/cumulative reward for a given state of the environment. 
- **Ensemble learning**: Improve the performance of your models. Uses tricks from supervised learning.

Here is...

# A visual lay of the land

- A visual introduction to machine learning: http://www.r2d3.us/visual-intro-to-machine-learning-part-1/

Also:
![A Mindmap of the algorithms](images/MachineLearningAlgorithms.png)
(source: https://machinelearningmastery.com/)

# Common Problems we try to solve

- **Binary Classification**: put an example into one of 2 available classes, for e.g. Object of Type A or B, Student is proficient or not, Yes or Not
- **Multi-class Classification**: put an example into one of many available classes, for e.g. each 'digit' in a set of handwritten numbers can be a class, now we need to predict which of the images belong to which class (and hence represents which number)
- **Prediction or Regression**: Try and predict a value
- **Ranking**: Rank courses, movies, web pages in order of relevance
- ...others
When we break machine learning problems this way, we give ourselves a method for measuring the errors.

# How this works
Each bit addressed below will have two or three Jupyter Notebooks associated with them:
1. An empty workbook, where you can add your code.
2. A tutorial workbook.
2. A solution workbook.
You can start with the empty notebook, follow the tutorial and end up with the solution.

## You'll need
A computer with atleast 16 Gb of RAM
Access to the internet
Anaconda installed on your machine: [prefer a 64-bit, Python 3.x download from here](https://www.anaconda.com/download/)
I'll point out datasets that we need for each of the exercises as we go along.

# Topics
Here are all the bits we will cover:
- Decision Trees - CART
- Decision Trees - ID3, C4.5 and C5
- Regression - Linear Regression
- Regression - Logistic Regression
- The Confusion Matrix
- Clustering - K-Means and K-Medians
- Dimensionality Reduction - PCA
- Dimensionality Reduction - LDA

# ML vs AI - a quick rant
I come across this question again and again. 
IMO,
_this is a perfectly useless classification, reserved for sales decks and management retreats._ 
_If you really are one of those who want to get to work, ignore this._

- Machine Learning is a 'subset' of AI
	- deals with extant algorithms and their implemetation
	- when people use this term what they mean is not only implementing cool algorithms, but also doing the dirty work of loading and querying data, cleaning it, figuring out the inconsistencies, the idisyncracies of the data/domain, imputing where necessary and the other tasks that may be thought of as 'drudgery' simply because they are the necessary nuts and bolts of every ML operation. This is not unlike the way engineering is treated - where the people writing the code are at the bottom of the pyramid. 
- AI is all the research going on around Intelligent Machines - all the 'Math' work. 

Ultimately it's upto the practioner to gain expertise and earn respect. ML vs AI - these divisions are largely there for people, who'll never write code or model with their own hands to talk in ways that don't sound completely stupid (to others like them). 