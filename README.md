# tensorflow-problem-sheet-4
*Mindaugas Vainauskas, 4th year software development course, Emerging technologies module, GMIT, 2017*

## Problem sheet description
In this problem sheet we see an example of simple neural network using Iris dataset and using Keras API to process it and then test it by having it to predict the species of Iris flower randomly selected from the dataset by just its 4 types of size variables(Sapal width and length, and Petal width and length). The example is ran from Jupyter notebook as a prefered environment as it allows for rich text as well as code to be assembled in same place.

## What is Keras?
Keras is a high-level neural networks API capable of running on top of Tensorflow, CNTK and Theano software libraries for machine learning. It is used in this example to showcase how much simpler it is to use than standard Tensorflow library.

## Jupyter Notebook installation
As example is saved as a Jupyter notebook file, Jupyter notebook app should be installed first before running the example.
Best way to install Jupyter Notebook is as part of Anaconda package. Anaconda package can be downloaded from [Here](https://conda.io/docs/user-guide/install/download.html) This will install Python v3.6 as well if it is not currently on the machine

If you need/want to install the notebook by itself the installation instructions are available in [Project Jupyter installation page](http://jupyter.org/install.html)

## Keras Installation
Before installing and using Keras, Tensorflow has to be already installed on the machine. Installation instructions are available for all main Operating Systems and are available from [Tensorflow installation page](https://www.tensorflow.org/install/). Once in the installation page you can select installation guide for your prefered OS and follow instructions in there to get it installed on your machine.

Once Tensorflow is successfully installed on the local machine, you can install Keras API from [Keras installation page](https://keras.io/#installation) by following instructions on it.

## Running the example python file
Once downloaded this example can be run from the Jupyter Notebook on the local machine. This is achieved by navigating to repository folder on the machine and running *jupyter notebook* command in it.

## Using Keras in the Python file
Keras API is used in Python file by importing it just like you would do with any other Python library. It uses Tensorflow backend so no explicit Tensorflow installation is needed.

## Rough rundown of how this example works:
 - Libraries are imported(Keras, csv and numpy);
 - Dataset is read from CSV file supplied with this example;
 - Dataset is split into training and testing sets;
 - Training model is created;
 - Training is ran for selected number of training runs(epochs) with selected sample size per run;
 - Trained model is tested by selecting random value from species array and guessing the species by just it's size variables;
 - Model is saved for possible future use (Saved model file is included in this repository)
