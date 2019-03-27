# Dog-Breed-Classifier

Udacity DSND Project on creating a dog breed image classifier with keras.

## Overview

This project is part of Udacity's Data Science Nanodegree. The aim of the project is to create a web application that is able to identify a breed of dog if given a photo or image as input. If the photo or image contains a human face, then the application will return the breed of dog that most resembles this person. The final trained model was then deployed into an application which could be fed photos (web application in Flask still under development).

Summary of the results - final model for identifying dog breeds achieved an **85%** accuracy level on the testing dataset.

## Repository Contents

The main file in the repository is the dog_app.ipynb, which is the Jupyter notebook containing the process used to create our algorithm and model used to predict the dog breed. A copy of this file is also in dog_app.html format.

haarcascades folder holds the xml file for use with the OpenCv face detector class that is used in the notebook.

## Dependencies
   - opencv-python==3.2.0.6
   - h5py==2.6.0
   - matplotlib==2.0.0
   - numpy==1.12.0
   - scipy==0.18.1
   - tqdm==4.11.2
   - keras==2.0.2
   - scikit-learn==0.18.1
   - pillow==4.0.0
   - ipykernel==4.6.1
   - tensorflow==1.0.0

## Instructions

The flask web application for this project is still under development.

## Acknowledgements

Many of my ideas for this project have been taken from the lessons on the Udacity website and supporting github repositories. I would like to thank the amazing professors, teachers and mentors working with Udacity, who are supporting me on this journey of DSND.
