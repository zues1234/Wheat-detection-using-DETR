# Wheat-detection-using-DETR

## Table of Content
  * [Overview](#overview)
  * [About](#About)
  * [Motivation](#motivation)
  * [Technical Aspect](#technical-aspect)
  * [Run](#Run)
  * [To Do](#to-do)
  * [Technologies Used](#technologies-used)
  * [Credits](#credits)

## Overview
The objective of this project was to use DETR a Transformer based deep learning model. You might have used RCNN and its families for object detection and masking. 
But DETR is a totally unique model and performs really well on detecting objects.

## About
Your morning toast or cereal may rely upon this common grain. Its popularity as a food and crop makes wheat widely studied. To get large and accurate data about wheat fields worldwide, plant scientists use image detection of "wheat heads"—spikes atop the plant containing grain. These images are used to estimate the density and size of wheat heads in different varieties. Farmers can use the data to assess health and maturity when making management decisions in their fields.

In this project, the motive was to detect wheat heads for further analysis(analysis nnot included). From the images of the field I can now detect the wheat heads which can be used by scientists or farmer for analysis like spread, size, thickness or each head.

follow on this [DETR(DEtection TRansformer)](https://github.com/facebookresearch/detr)to read more about it.

## Motivation
Wanted to try a new unique SOTA model for object detection.

## Technical Aspect
This project is divided into two part:
1. Training a deep learning model using Pytoch.
      - model: DETR
      - data: 3373
      - evaluation metrics: from their github (Hungarian matcher)

## Run
To make life easier I've compiled everything into a notebook, so If you're interested in running the app simply run the notebook on any GPU provied platforms(kaggle suggested)

## To Do
1. Convert the app to run without any internet connection, i.e. __PWA__.
2. Add a better vizualization chart to display the predictions.
3. deploy the Flask app on heroku with saved_model.pkl

## Bug / Feature Request
If you'd like to request a new function, feel free to do so by opening an issue [here](https://github.com/zues1234/Melanoma-deeplearning/issues/new). Please include sample queries and their corresponding results.

## Technologies used
  Major frameworks & Libraries 
  * [PyTorch](https://pytorch.org/)
  * [Flask](https://flask.palletsprojects.com/en/1.1.x/)
  * [Albumentation](https://albumentations.ai/)
  * [WTFML](https://pypi.org/project/wtfml/)
  * [Numpy | Pandas]
