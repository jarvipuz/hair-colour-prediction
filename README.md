# Hair Colour Prediction
COMP8220 Machine Learning
 
## Introduction

This project works on a dataset from the image domain. The dataset was explored and several statistical learning approaches, both conventional machine learning and deep learning, were used to build high-performing systems that execute a classification task. The systems created were evaluated using a public test set, to see how well the systems are performing, and a private test, to see how well the systems generalize to an unseen dataset.

## Image Dataset and Task

The CelebA dataset is used for this task, a widely used dataset of celebrity faces. The task is to predict the hair colour of the celebrity, which will be one of black, brown, blond or gray. The solution was developed in Google Colaboratory. The original dataset was reduced to a smaller version of the images to prevent any problems with Google Colaboratory's memory limits. It was cut down both in terms of image size, and number of items in the dataset. Images were also removed that are labelled with more than one colour. 

For testing, there was a public test set and a private test set. The public test set is the standard one used for CelebA. The private test set was hosted in Kaggle.

### Dataset Format

* The labels have been set for the task in this assignment
* It contains a subset of the original images
* The images have been reduced in dimension, 48x48, but still with 3 colours (48 x 48 x 3 overall)
* The preprocessed dataset has been split into train, val and (public) test data that is consistent with the standard splits used for CelebA

### Jupyter Notebook

The Jupyter notebooks contain all the code used to train model(s) and make predictions on the test set, for both the conventional machine learning approach and the deep learning approach. The final report contains the code for the final models submitted to Kaggle for evaluation (i.e. there are codes for two models, one for the conventional ML and one for deep learning). The final report contains text blocks with comments explaining what each segment of code does. The discussion should also include some reflection about the implementation and relative performance of your conventional machine learning and deep learning approaches.

## Results (Kaggle Submission)

The project is hosted at [Kaggle InClass](https://www.kaggle.com/c/celeba-guess-hair) where the predictions were evaluated. For the public test set, the best-performing model achieved an accuracy of 93.11% (with rank 10/56) and for the private test set, the model achieved 62.81 (rank 16/50). The discussion for all the models and their performance are in the final report.
