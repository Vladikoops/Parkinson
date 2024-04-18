# Parkinson Disease Prediction

Parkinson’s disease is a progressive disorder that affects the nervous system and the parts of the body controlled by the nerves. 
Symptoms are also not that sound to be noticeable. Signs of stiffening, tremors, and slowing of movements may be signs of Parkinson’s disease.

But there is no ascertain way to tell whether a person has Parkinson’s disease or not because there are no such diagnostics methods available to diagnose this disorder.
But what if we use machine learning to predict whether a person suffers from Parkinson’s disease or not?

### Pandas – This library helps to load the data frame in a 2D array format and has multiple functions to perform analysis tasks in one go.
### Numpy – Numpy arrays are very fast and can perform large computations in a very short time.
### Matplotlib/Seaborn – This library is used to draw visualizations.
### Sklearn – This module contains multiple libraries having pre-implemented functions to perform tasks from data preprocessing to model development and evaluation.
### XGBoost – This contains the eXtreme Gradient Boosting machine learning algorithm which helps us to achieve high accuracy on predictions.
### Imblearn – This module contains a function that can be used for handling problems related to data imbalance.

### Dataset:
Matrix column entries (attributes):

name - ASCII subject name and recording number

MDVP:Fo(Hz) - Average vocal fundamental frequency

MDVP:Fhi(Hz) - Maximum vocal fundamental frequency

MDVP:Flo(Hz) - Minimum vocal fundamental frequency

MDVP:Jitter(%),MDVP:Jitter(Abs),MDVP:RAP,MDVP:PPQ,Jitter:DDP - Several

measures of variation in fundamental frequency

MDVP:Shimmer,MDVP:Shimmer(dB),Shimmer:APQ3,Shimmer:APQ5,MDVP:APQ,Shimmer:DDA - Several measures of variation in amplitude

NHR,HNR - Two measures of ratio of noise to tonal components in the voice

status - Health status of the subject (one) - Parkinson's, (zero) - healthy

RPDE,D2 - Two nonlinear dynamical complexity measures

DFA - Signal fractal scaling exponent

spread1,spread2,PPE - Three nonlinear measures of fundamental frequency variation
