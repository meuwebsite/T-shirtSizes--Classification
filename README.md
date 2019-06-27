#### Machine Learning - K-NEAREST NEIGHBORS

# T-shirtSizes--Classification

![x](images/ts4)

## Background

Online clothing business and you would like to develop a new app (or in-store) feature in which customers would enter their own height and weight and the system would predict what T-shirt size should they wear. Features are height and weight and output is either L (Large) or S (Small).


DATA SOURCE: https://www.listendata.com/2017/12/k-nearest-neighbor-step-by-step-tutorial.html


## Goals

* Split the data in Train and Test
* Train and Test the model in the data set
* Visualize data points
* Classify the T-shirts by size


## How to run 

Open Google Colab https://colab.research.google.com/
* File
* Upload Notebook
* Run the Cells


## Proccess

Import the data set and visualize the data

With Scatter plot

![fb](images/fb1.png)

With Box plot
![fb](images/fb2.png)

With Histogram
![fb](images/fb4.png)

Transforming the data and Executing a training Test 
![fb](images/fb5.png)

With Confusion Matrix, checking on the accuracy
![fb](images/fb6.png)

ploting the boundary using the trained classifier
* Run the classifier to predict the outcome on all pixels with resolution of 0.01
* Colouring the pixels with 0 or 1
* If classified as 0 it will be magenta, and if it is classified as 1 it will be shown in blue 

![fb](images/fb7.png)

Ploting all the actual training points

![fb](images/fb8.png)

Visualising the Training set results for Tran and Test

![fb](images/fb9.png)
