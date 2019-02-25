# Dog Classification

## Project Overview

This project builds a pipeline that can be used within a web or mobile app to process real-world, user-supplied images.  Given an image of a dog, the algorithm will identify an estimate of the canine’s breed.  If supplied an image of a human, the code will identify the resembling dog breed.

Along with exploring state-of-the-art CNN models for classification and localisation, important design decisions about the user experience for the app is made.  Each model has its strengths and weaknesses, and engineering a real-world application often involves solving many problems without a perfect answer.  

## Project Instructions

### Instructions
_It is assumed that the relevant Python packages and library are already installed. They are imported within this project._

1. Clone the repository and navigate to the downloaded folder.
2. Download the [dog dataset](https://s3-us-west-1.amazonaws.com/udacity-aind/dog-project/dogImages.zip).  Unzip the folder and place it in the repo, at location `path_to_this_project/dog_images`.  The `dog_images/` folder contains 133 folders, each corresponding to a different dog breed.
3. Download the [human dataset](http://vis-www.cs.umass.edu/lfw/lfw.tgz).  Unzip the folder and place it in the repo, at location `path_to_this_project/lfw`.
4. Open a terminal window and navigate to the project folder. Open the notebook and follow the instructions.
	```
		jupyter notebook dog_app.ipynb
	```
