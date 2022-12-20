# OrchidsAIden

---

## Table of contents
* [General info](#general-info)
* [Getting the data](#getting-the-data)
* [Preparing the Data](#preparing-the-data)
* [Training the Model](#training-the-model)
* [Technologies](#technologies)
* [Architecture](#architecture)
* [Setup](#setup)
* [The Team](#the-team)

---

## General info

Orchids are one of the two more

OrchidsAIden is a data science project, which, given an Orchid Image as an input, identifies the orchid species that is presented . The project intends to demonstrate numerous facets of data science, from data preparation to model selection and training.



---

## Getting the data
The images were obtained by scraping the web for good


---

## Preparing the Data

1. Data Cleaning

2. Resizing

3. Grayscaling/Normalizing


4. Augmentation (mirrroing & rotating)


## Training the Model

### Model constructed using a pre-trained network
A pre-trained a Convolutional Neural Network (Densenet169) is used after adding a few extra layers.

The model is trained in two sequences.
<ul><li>On the first step, the pre-trained network layers are frozen and just the layers that were added are trained. </li>
    <li>On a second step, after the model has converged, it is finetuned by unfreezing a few layers from the pre-trained CNN, using very small steps.</li></ul>



## Technologies
The app has been developed in Python (version: 3.10.6), served as a Flask application.
It uses the following libraries:

* numpy 1.23.5
* requests 2.28.1
* tensorflow 2.11.0
* fastapi 0.88.0
* uvicorn 0.20.0
* jinja2 3.1.2
* flask 2.2.2
* scikit-image 0.19.3
* gunicorn 20.1.0
* ...

---

## Architecture

....



---

## Setup

....

---

## The Team

### Alba Gutierrez Pedemonte
Alba has a background in Physics, worked as a consultant and is an entrepreneur</br>
<a href="https://www.linkedin.com/in/albagutierrezpedemonte/">LinkedIn</a><br>
<a href="mailto: albaguti@gmail.com">E-mail</a><br>
<a href ="https://github.com/albaguti">
