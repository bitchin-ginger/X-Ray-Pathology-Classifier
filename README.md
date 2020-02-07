# X-Ray-Pneumonia-Classifier

## Project Goals 

Train a series of classifiers to predict the label, optimize those models (feature engineering), how I can modify these pixels and combine these pixels in order to make my logistic regression more powerful

## Pipeline
DOCKER/SPARK/AWS-- EC2 w/ 1 Terabyte of memory? run 2 hours (figure out pipeline first)

start small, downsize imges to 50x50, answer this question and run pipeline which one performs better? diminishing return for the quality.


Image data → dataframes  where each pixel is a feature, Each value could be the hex code
Regularization*?

Tuning models, learn more about features and feature engineer something that would be  useful. Less emphasis on EDA and dealing with hypothesis testing and still might want to do  EDA to understand data better and understand correlations and if features follow certain distributions.

1. Take images (use only 1000) --> import them and take each pixel and make a feature for each pixel --> make a new variable 
2. import labeled data and only use the ones that correspond to 1000 images that I will use --> 

merge these 2 Join on the image ID

if main components describe well like the age etc. then it will predict well

highest eigenvalues from PCA



## Statistics of Interest/EDA




## Visualizations


Pixel Shading Histograms, with or without Pneumonia distribution of pixels (shading histogram)

Graph the singular values from SVD

## Models

Logistic Regression
Gradient Boosted Classifier
Random Forest Classifier
SVM - Support Vector Machine
CNN


## Considerations/Issues
Images that aren't aligned were not centralized



## Conclusions


## Future Directions
