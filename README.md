
# 🐔Poultry Disease Detection System

Welcome to PoultryVision™, where we’re turning chickens into data points, one cluck at a time! If you're here, you're either worried about your chickens' well-being or you just love AI (Artificial Ingredients? Just kidding!).

 This project is a game-changer in poultry farming, using the power of semi-supervised learning, deep learning, and reinforcement learning to diagnose chicken diseases with stunning accuracy—because why not give your chickens the cutting-edge treatment they deserve?




## Table of Contents

### Introduction
### Features
### Installation
### How it works ?
### Usage
### The Secret Sauce
### Contributing
### License

## 🐔 Introduction

Imagine you're a chicken farmer with thousands of birds. You can't spend all day checking each feather for signs of illness, can you?

That's where PoultryVision™ comes in. This project leverages AI to detect and classify diseases in chickens from images, letting farmers relax while their virtual vet does the hard work.

Not only is it smart, but it learns as it goes—making it smarter with every bird it checks!
## 💡 Features

1 - Semi-Supervised Learning: Your AI model learns from limited labeled data and a whole lot of unlabeled data, just like your chickens learn to peck at the right feed.

2 - Reinforcement Learning: The AI improves over time, like a chicken gradually perfecting its egg-laying routine.

3 - Deep Learning: Harnessing convolutional neural networks (CNNs), because who wouldn’t want layers? Chickens love layers. 🥚

4 - CI/CD Pipeline: Automated testing and deployment so that your classifier is always clucking smoothly.

5 - Disease Database Integration: Real-time updates to keep your model current with the latest poultry-related ailments. Think of it as the CDC for chickens.
## 🚀 Installation and Usage

Clone the Repository using these steps :

Step 1 : Open terminal ( windows ) or konsole ( linux )

Step 2 : Type or paste the following command in it - 

 < git clone https://github.com/Stonebanks-js/Avian-Ailment-Analyzer.git >

 Step 3 : locate the cloned repo in your local system and open it in IDE ( VS Code ( recommended))

 Step 4 : Activate the virtual environment (If you're not sure, just follow the instructions you find when you get stuck) - 

#1  .\venv\Scripts\Activate.ps1  ( for windows )

#2   source venv/bin/activate  ( For mac/linux )

Step 5 : Install dependencies -

pip install -r requirements.txt

Step 6 : Configure your project with the config.yaml file (because no project is complete without a good config file):

Customize dataset paths, hyperparameters, and model settings by tweaking the config.yaml

Step 7 Run the magic -

python application.py

( Dont forget to download the resources folder from the images of healthy chicken and diseased chicken from above folders in "CODE" section.)

## 🎛️ How It Works ?

### The Dataset: 
A treasure trove of chicken images, curated and labeled for your training pleasure. The data is sourced from diverse farms (and maybe a few backyard coops). You can find the dataset. 

you can find the dataset from :

https://www.kaggle.com/datasets/vrajp3301/chicken-fecal-images-dataset

### Mechanism of the Project

We use a blend of CNNs with semi-supervised learning techniques to classify chicken diseases. The model is trained on a labeled subset of the dataset, while reinforcement learning helps it improve with real-world feedback.

### Output and Results

Your model outputs predictions on what disease (if any) the chicken has. It even provides a probability score, so you know how confident it is.





## 🐤 Usage

Let’s diagnose some chickens! Once your model is trained, run it on new chicken images.

Just launch the application.py with a virtual environmet 

Upload the image and click "Predict"


## Streamlined Workflow

1 : Update config.yaml

2 : Update secrets.yaml [Optional]

3 : Update params.yaml

4 : Update the entity

5 : Update the configuration manager in src config

6 : Update the components

7 : Update the pipeline

8 : Update the main.py

9 : Update the dvc.yaml


## 🤝 Contributing Guide

We welcome all contributions, whether you’re a chicken lover, AI enthusiast, or just someone looking to dive into an innovative project. Feel free to submit a pull request, and remember: Great chicken minds think alike. 🧠🐔

Step 1 : Fork the repository to your profile

Step 2 : Click on the green button "Code" and copy the HTTPs link you can also copy it from here - 

" git clone https://github.com/Stonebanks-js/Avian-Ailment-Analyzer.git "

Note - Do not copy the quotes. 

Step 3 : Locate the path to your VS Code and open it. 

Step 4 : Make the changes ---> Push them ---> Create a pull request.




# Thanks You | YOUR CONTRIBUTIONS ARE WELCOMED !
