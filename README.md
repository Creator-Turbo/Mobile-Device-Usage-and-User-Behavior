## Mobile Device Usage Behavior Classification


## Table of Content
  * [Demo](#demo)
  * [Overview](#overview)
  * [Motivation](#motivation)
  * [Technical Aspect](#technical-aspect)
  * [Installation](#installation)
  * [Run](#run)
  * [Directory Tree](#directory-tree)
  * [To Do](#to-do)
  * [Bug / Feature Request](#bug---feature-request)
  * [Technologies Used](#technologies-used)
  * [Team](#team)
  * [License](#license)
  * [Credits](#credits)


## Demo :
The image should be download(save images) on your device to used project<br>
Link: [Demo project](#)



<!-- <!-- [![](https://imgur.com/s4FWb9b)](https://ipcc.rohitswami.com) -->
## Cats vs. Dogs Image Classification
![Mobile Device Usage Behavior](https://i.imgur.com/1CZb4eR.png)

## Overview
This project leverages machine learning to classify mobile device usage behaviors into five distinct categories: Light, Moderate, Heavy, Very Heavy, and Extreme Usage. By analyzing metrics such as app usage time, screen-on time, battery drain, and data consumption, the project demonstrates the practical application of machine learning in user behavior analysis.


## Motivation
Understanding mobile device usage is critical for improving user experience and building intelligent applications.

Key Objectives:
 - Behavior Classification: Categorize users based on device usage metrics to enhance personalization.
 - Actionable Insights: Use patterns to optimize battery life, improve app performance, and recommend usage guidelines.
 - Exploring ML Techniques: Gain practical experience in designing, training, and deploying machine learning models.

## Technical Aspect

The project involves the following key machine learning processes:

  - Data Preparation: Preprocessing raw user behavior data to create features suitable for modeling.
  - Modeling: Training a deep learning classification model to achieve high accuracy in user behavior predictions.
  - Deployment: Developing a Flask-based web application for real-time predictions


## Installation
The Code is written in Python 3.10. If you don't have Python installed you can find it [here](https://www.python.org/downloads/). If you are using a lower version of Python you can upgrade using the pip package, ensuring you have the latest version of pip. To install the required packages and libraries, run this command in the project directory after [cloning](https://www.howtogeek.com/451360/how-to-clone-a-github-repository/) the repository:

# To clone the repository

```bash

gh gh repo clone Creator-Turbo/Mobile-Device-Usage-and-User-Behavior

```
# Install dependencies: (all lib)
```bash
pip install -r requirements.txt
```



## Run
To train the Deep leaning models:
 To run the Flask web app locally
```bash
python app.py

```

## Directory Tree 
```
.
├── notebook/                     # Directory for Jupyter notebooks or similar resources
├── .gitignore                    # File to specify files/folders to exclude from Git tracking
├── model.pkl                     # Serialized trained model file
├── README.md                     # Project documentation file
├── requirements.txt              # Python dependencies file
└── user_behavior_dataset.csv     # Dataset file for user behavior analysis

```

## To Do
- Create the Flask app.
- Deploy the project to a cloud platform.
- Set up monitoring using different MLOps tools.
- Develop an end-to-end solution for the project.


## Bug / Feature Request
If you encounter any bugs or want to request a new feature, please open an issue on GitHub. We welcome contributions!




## Technologies Used
Python 3.10<br> 
scikit-learn<br>
pandas (for data manipulation) <br>
numpy (for numerical operations)  <br>
matplotlib (for visualizations) <br>



![](https://forthebadge.com/images/badges/made-with-python.svg)


[<img target="_blank" src="https://upload.wikimedia.org/wikipedia/commons/thumb/0/05/Scikit_learn_logo_small.svg/260px-Scikit_learn_logo_small.svg.png" width=170>](https://pandas.pydata.org/docs/)
[<img target="_blank" src="https://miro.medium.com/v2/resize:fit:720/format:webp/0*RWkQ0Fziw792xa0S" width=170>](https://pandas.pydata.org/docs/)
  [<img target="_blank" src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSDzf1RMK1iHKjAswDiqbFB8f3by6mLO89eir-Q4LJioPuq9yOrhvpw2d3Ms1u8NLlzsMQ&usqp=CAU" width=280>](https://matplotlib.org/stable/index.html) 

 [<img target="_blank" src="https://upload.wikimedia.org/wikipedia/commons/thumb/3/31/NumPy_logo_2020.svg/512px-NumPy_logo_2020.svg.png" width=200>](https://aws.amazon.com/s3/) 


## Team
This project was developed by:
[![Bablu kumar pandey](https://github.com/Creator-Turbo/images-/blob/main/resized_image.png?raw=true)](ressume_link) |
-|


**Bablu Kumar Pandey**


- [GitHub](https://github.com/Creator-Turbo)  
- [LinkedIn](https://www.linkedin.com/in/bablu-kumar-pandey-313764286/)
* **Personal Website**: [My Portfolio](https://creator-turbo.github.io/Creator-Turbo-Portfolio-website/)





## Credits

Special thanks to the contributors of the scikit-learn library for their fantastic machine learning tools.


