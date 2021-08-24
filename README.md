
# Face Recognition with MTCNN model 

## Table of Content
  * [Demo](#demo)
  * [Overview](#overview)
  * [Motivation](#motivation)
  * [Technical Aspect](#technical-aspect)
  * [Deployment](#deployment)
  * [Execution](#execution-steps)
  * [Technology Used](#technology-used)
  * [Authors](#authors)
  
## Demo

[![](http://img.youtube.com/vi/NCERi4l7A14/0.jpg)](http://www.youtube.com/watch?v=NCERi4l7A14 "Face Recognition")

[![](https://imgur.com/expfifr.png)]


## Overview
This is a proto type for training the application with human faces and then using the trained models to predict 
the known faces and identify the unknown faces/persons. 

## Motivation
This model has several use cases like
    - granting access to authorized persons only based on face identification
    - attendance capture
    - surveillance system to identify unauthorized people and raise alarm
    
## Technical Aspect 
This project uses MTCNN model. 

## Deployment

To use this application, please follow the below steps in the same order 

create environment

```bash
  conda create -n <envname> python=3.6 -y
```

activate the environment

```bash
  conda activate <envname>
```

install the requirements file

```bash
  pip install -r requirements.txt
```

download the .h5 file from below location and keep it as *src/faceEmbeddingModels/my_model.h5*

```http
    https://drive.google.com/drive/folders/1fggRFkiCBBcwSnKtW3CwJDQ6Rvd5MMe-?usp=sharing
```

create a working directory to hold this project and use the below git commands 
to push work directory contents to your git repo

```bash
    git init
    git add . && git commit -m "first commit"
    git remote add origin https://github.com/.......git
    git branch -M main
    git push origin main
```

## Execution Steps:

1. Open the project in an IDE like pycharm 
2. $ *cd src*
3. $ *python app.py*
4. Follow the instructions from the pop up window of the application

## Technology Used
<p align="left">

<a href="https://www.python.org" target="_blank"> 
<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" alt="python" 
width="40" height="40"/> </a>

<a href="https://keras.io/api/" target="_blank"> 
<img src="https://upload.wikimedia.org/wikipedia/commons/thumb/a/ae/Keras_logo.svg/1200px-Keras_logo.svg.png" 
alt="keras" width="40" height="40"/> </a>

<a href="https://www.tensorflow.org" target="_blank"> 
<img src="https://www.vectorlogo.zone/logos/tensorflow/tensorflow-icon.svg" 
alt="tensorflow" width="40" height="40"/> </a>

</p>


## Authors

- [@Mansoor Baig](https://github.com/MansoorAB)

  


  