If the field of ML was Doc Brown, this introduction to machine learning tutorial is Marty McFly. 

You'll not be able to invent time travel, but you'll be able to stumble and fall all the way to saving the day. 

## References:

- This [http://ciml.info/dl/v0_9/ciml-v0_9-all.pdf], 
- This [https://www.ics.uci.edu/~welling/teaching/ICS273Afall11/IntroMLBook.pdf], 
-  and this [http://learnds.com/]

## ML vs AI

_Admittedly this is the kinda sh*t your 'manager' will spout._ 
_If you really are one of those who want to get to work, ignore this._

- Machine Learning is a 'subset' of AI
	- deals with extant algorithms and their implemetation
- AI is all the research going on around Intelligent Machines

## Learning?

- Ability to *generalize* from specific examples
	- Incorrect to ask questions about a pottery course in a Machine Learning Course
	- Incorrect to ask the _same_ question that was taught - even if with different data
	- Expected to extrapolate or *infer* answers from the questions that were studied

## Is there a Glossary?

- Helpful: http://alumni.media.mit.edu/~tpminka/statlearn/glossary/
- Another: https://www.analyticsvidhya.com/glossary-of-common-statistics-and-machine-learning-terms/
- Yet another: https://martin-thoma.com/ml-glossary/

## Common Problems we try to solve

- *Binary Classification*: put an example into one of 2 available classes, for e.g. Object of Type A or B, Student is proficient or not, Yes or Not
- *Multi-class Classification*: put an example into one of many available classes, for e.g. each 'digit' in a set of handwritten numbers can be a class, now we need to predict which of the images belong to which class (and hence represents which number)
- *Prediction or Regression*: Try and predict a value
- *Ranking*: Rank courses, movies, web pages in order of relevance
- ...others
When we break machine learning problems this way, we give ourselves a method for measuring the error

## Types

Personally, you may not care about this _eventually_, but we humans learn by classifying, so here's a common way to bucket the problems of machine learning:

- Supervised learning: Input a *vector*, find out what *class*/*lable* the vector belongs to using a *model*. Learn using existing *labelled* data where a variety of vectors have already been assigned labels.
- Unsupervised learning: Input a vector, output a *transformed value* (or a vector) that solves a practical problem (for e.g. *clustering, outlier detection, dimensionality reduction* etc.). Learn using data that has no labels.
- Semi-supervised learning: Just like supervised learning, input a vector, find out what class/lable the vector belongs to. Learn based on data that has labels, but *a lot of the lables are missing* - you have data that can better inform your probability distributions, so this could improve the classification. 
- Reinforcement learning: 

Here is...

## A visual lay of the land

- A visual introduction to machine learning: http://www.r2d3.us/visual-intro-to-machine-learning-part-1/

Also:
![A Mindmap of the algorithms](images/MachineLearningAlgorithms.png)
(source: https://machinelearningmastery.com/)
