# **Predicting Lung Disease With CV**
![Python 3.6](https://img.shields.io/badge/Python-3.6-brightgreen.svg)

Download Additional Files : https://www.kaggle.com/paultimothymooney/chest-xray-pneumonia

• This repository consists of files required to deploy a Lung Disease Predictor With CV

• Please do ⭐ the repository, if it helped you in anyway.


## Authors

- [@Akash Kumar Jha](https://github.com/Akash1070)


## Deployment
  1. Download the necessary files. #images and videos
  2. Import the following Libraries below mentioned.
  3. Re-size all the images to this.
  4. Import the Vgg 16 library as shown below and add preprocessing layer to the front of VGG.
  5. tell the model what cost and optimization method to use.
  6. Use the Image Data Generator to import the images from the dataset.
  7. Make sure you provide the same target size as initialied for the image size.
  8. fit the model & Run the cell. It will take some time to execute.
  9. plot the loss & Accuracy.
  10. save it as a h5 file
  
## Installation

To install the libraries used in this project. Follow the 
below steps:

```bash
from keras.layers import Input, Lambda, Dense, Flatten
from keras.models import Model
#from keras.applications.resnet50 import ResNet50
from keras.applications.vgg16 import VGG16
from keras.applications.vgg16 import preprocess_input
from keras.preprocessing import image
from keras.preprocessing.image import ImageDataGenerator
from keras.models import Sequential
import numpy as np
from glob import glob
import matplotlib.pyplot as plt
from keras.preprocessing.image import ImageDataGenerator
from keras.applications.vgg19 import VGG19
from keras.applications.inception_v3 import InceptionV3
```
    
## Running Flask Api

To run tests, run the following command

```bash
  python app.py
```

## 🚀 About Me

Data Scientist Enthusiast | Petroleum Engineer Graduate | Solving Problems Using Data 


# Hi, I'm Akash! 👋


## 🔗 Links
[![github](https://img.shields.io/badge/github-000?style=for-the-badge&logo=ko-fi&logoColor=white)](https://github.com/Akash1070)
[![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/akashkumar107/)

## Tech Stack





![Logo](https://businesstoys.in/assets/programs/full-stack-data-science-professional-program/tools.png)
## Other Me
👩‍💻 I’m interested in Petroleum Engineering

🧠 I’m currently learning Data Scientist | Data Analytics | Business Analytics

👯‍♀️ I’m looking to collaborate on Ideas & Data




## 🛠 Skills
1. Data Scientist
2. Data Analyst
3. Business Analyst
4. Machine Learning 


## Future Plans 

⚡️ Looking forward to help drive innovations into your company as a Data Scientist

⚡️ Looking forward to offer more than I take and leave the place better than i found
