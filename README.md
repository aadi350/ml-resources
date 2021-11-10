# Concise List of Machine Learning Resources <!-- omit in toc -->
*This repository does not contain any actual theory, it simply points to online articles, book chapters and courses that I find useful*  
It is broken into three sections:

- [I have an Interview Tomorrow](#i-have-an-interview-tomorrow) 
- [3-6 Weeks](#3-6-weeks)
- [Life Never Ends](#life-never-ends)

If you had to learn the bare-minimum and are in a time-crunch, stick to section one.  
If you have a bit more time, cover section one AND explore section 2 
If you have more time, go through section three, but selectively  

*all books are linked in a folder, copywright infringement not intended*

# I have an Interview Tomorrow  
[Google's FREE Machine Learning Crash-Course](https://developers.google.com/machine-learning/crash-course)  
This is a no-brainer, follow this and get the ins-and-outs of everything ML.   
## Books
[Hands on Machine Learning with Scikit-Learn, Keras and TensorFlow](books/Hands-On-ML.pdf)   
This is still my personal go-to. It covers just enough to get started, and is nicely laid out. It is one of the **only** books I'd ever recommend reading sequentially if you're new to the field. This book should be (and can be) used as a guide regarding what to learn in ML. That being said, it does not really delve into the weeds of what certain things work, or how the math behind each algorithm works. 

A book is by its very nature, monolithic and tedious to digest, I suggest flashcards to remember important concepts, and start a GitHub repository with common patterns from the book that you use. Do not, and I stress **DO NOT** simply fork online implementations for this book specifically, owing to its simple nature, you need to actually go through and implement things to get a feel of code (did I mention you need to know a little bit of Python?). That being said, this book also covers just enough Python to get you started. If you actually have an interview tomorrow (and for some reason have never studied ML before), use [Google Collab](https://colab.research.google.com/). It is an online environment for writing code, and requires ZERO setup

# 3-6 Weeks 
Okay so you have a bit of time, my first recommendation still holds, use the [first book](books/Hands-On-ML.pdf) as a bit of guide. However here's where you can dive into the forest and learn about the trees. This is possibly the most useful section, as it outlines a few concepts and where to go to learn them. Additionally, algorithms resources are listed from the most-essential to least essential, in other terms, for EACH individual algorithm the ordering of resources should be sequential. TThhat being said, you can jump around algorithms 
## Algorithms  
This is where all the hype in ML lay, but is not the full picture. That being said, the following breakdown should assist in pointing you to where to find certain resources.  

[This playlist](https://www.youtube.com/playlist?list=PLoROMvodv4rMiGQp3WXShtMGgzqpfVfbU) is Andrew Ng's 2012 Machine Learning course on Coursera, but updated and using Python instead of MATLAB  
*Please stay away from MATLAB...*

### kNN  
[Develop kNN from Scratch in Python](https://machinelearningmastery.com/tutorial-to-implement-k-nearest-neighbors-in-python-from-scratch/)  
[kNN for Machine Learning](https://machinelearningmastery.com/k-nearest-neighbors-for-machine-learning/)  

### Linear Regression  
Chapter 3  [Pattern Recognition and Machine Learning](books/Pattern-Recognition-And-Machine-Learning-Bishop.pdf)  
Chapter 3  [Elements of Statistical Learning](books/ESL.pdf)

### Linear Classification  
Chapter 4 [Pattern Recognition and Machine Learning](books/Pattern-Recognition-And-Machine-Learning-Bishop.pdf)    
Chapter 4 [An Introduction to Statistical Learning](books/AnIntroduction-to-Statistical-Learning-with-Applications-in-R.pdf) 
Chapter 5 [Hands on Machine Learning with Scikit-Learn, Keras and TensorFlow](books/Hands-On-ML.pdf)   
Chapter 6 [Hands on Machine Learning with Scikit-Learn, Keras and TensorFlow](books/Hands-On-ML.pdf)   

### Tree-Based Methods  
[Classification and Regression Trees in Python](https://machinelearningmastery.com/classification-and-regression-trees-for-machine-learning/)
[Random Forest in Python](https://machinelearningmastery.com/random-forest-ensemble-in-python/)  
Chapter 8 [An Introduction to Statistical Learning](books/AnIntroduction-to-Statistical-Learning-with-Applications-in-R.pdf)

### Anomaly Detection  
Chapter 4 [Hands on Unsupervised Learning Using Python](books/Hands-On-Unsupervised-Learning-Using-Python.pdf)  
Chapter 6, 7, 8 [Anomaly Detection: Principles and Algorithms](books/Anomaly-Detection-Principles-and-Algorithms.pdf)  

### Pattern Mining  
Chapter 6 [Data Mining: Concepts and Techniques](books/Data-Mining-Concepts-and-Techniques.pdf)  

### Clustering  
Chapter 10 [Data Mining: Concepts and Techniques](books/Data-Mining-Concepts-and-Techniques.pdf)  
Chapter 11 [Data Mining: Concepts and Techniques](books/Data-Mining-Concepts-and-Techniques.pdf)  
Chapter 5 [Hands on Unsupervised Learning Using Python](books/Hands-On-Unsupervised-Learning-Using-Python.pdf)

### Dimensionality Reduction  
Chapter 3 [Hands on Unsupervised Learning Using Python](books/Hands-On-Unsupervised-Learning-Using-Python.pdf)
Chapter 8 [Hands on Machine Learning with Scikit-Learn, Keras and TensorFlow](books/Hands-On-ML.pdf)    

## Feature Engineering  
[Feature Engineering for Machine Learning](books/Feature-Engineering-for-Machine-Learning.pdf)

## Model Training   
[Andrew Ng Linear Regression and Gradient Descent](https://www.youtube.com/watch?v=4b4MUYve_U8&list=PLoROMvodv4rMiGQp3WXShtMGgzqpfVfbU&index=2)  
[Gradient Descent by StatQuest](https://www.youtube.com/watch?v=sDv4f4s2SB8)
Chapter 4 [Hands on Machine Learning with Scikit-Learn, Keras and TensorFlow](books/Hands-On-ML.pdf)

## Model Selection and Evaluation  
[Scikit-Learn Tutorial](https://scikit-learn.org/stable/model_selection.html)
Chapter 6 [Elements of Statistical Learning](books/ESL.pdf)  
Chapter 14 [ISL](books/Introduction-to-Statistical-Machine-Learning.pdf)  
Chapter 7 [An Introduction to Statistical Learning](books/AnIntroduction-to-Statistical-Learning-with-Applications-in-R.pdf)

### Boosting, Bagging and Ensemble Methods  
Chapter 10 [Elements of Statistical Learning](books/ESL.pdf)
Chapter 16 [Elements of Statistical Learning](books/ESL.pdf)

## Deep Learning 
*still in-progress, this area is HUGE, may split into sub-areas*  
Chapter 5 [Pattern Recognition and Machine Learning](books/Pattern-Recognition-And-Machine-Learning-Bishop.pdf)  
[Image Classification in TensorFlow](https://www.tensorflow.org/tutorials/keras/classification)
[Text Classification in TensorFlow](https://www.tensorflow.org/tutorials/keras/text_classification)  
[The Official TensorFlow Guide](https://www.tensorflow.org/guide)  <- HIGHLY Recommend  
[Introduction to Neural Networks](https://www.youtube.com/watch?v=MfIjxPh6Pys&list=PLoROMvodv4rMiGQp3WXShtMGgzqpfVfbU&index=11)  
[Training Neural Networks](https://www.youtube.com/watch?v=zUazLXZZA2U&list=PLoROMvodv4rMiGQp3WXShtMGgzqpfVfbU&index=12)  
[Error Analysis for ML](https://www.youtube.com/watch?v=ORrStCArmP4&list=PLoROMvodv4rMiGQp3WXShtMGgzqpfVfbU&index=13) 


## Data  
### Sampling Methods  
[Andrew Ng Models and Cross Validation](https://www.youtube.com/watch?v=rjbkWSTjHzM&list=PLoROMvodv4rMiGQp3WXShtMGgzqpfVfbU&index=8)  
Chapter 5 [An Introduction to Statistical Learning](books/AnIntroduction-to-Statistical-Learning-with-Applications-in-R.pdf)

# Life Never Ends
This is dumb, learning everything makes no sense