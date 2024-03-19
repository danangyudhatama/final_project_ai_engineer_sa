# End-to-End ML Model for Tempe Image Detection

This repository contains code for creating an end-to-end machine learning model to detect tempe images. The process involves collecting images through web scraping from Bing Images, training the model using transfer learning with a pre-trained ResNet50 architecture, and utilizing PyTorch for implementation. Beside that, there are also app folder that contains file and folder to build and lauch the web app with Python.

## Overview

Tempe is a traditional Indonesian food made from fermented soybeans. The goal of this project is to develop a machine learning model capable of identifying tempe images accurately. The model will be trained on a dataset collected from Bing Images and implemented using transfer learning with PyTorch.

## Accesing the web app that served using Code Engine by IBM
 <a href="https://application-ac.1epvqhehpli5.jp-tok.codeengine.appdomain.cloud/" target="_blank">TEMPE DETECTOR WEB APP</a>
## Setup

1. Clone this repository:

   ```bash
   git clone https://github.com/your-username/tempe-image-detection.git

2. Run the model_building.ipynb to create model to detect tempe images that later be used in the web app.

3. Run test_model.ipynb to test the model accuracy

4. Build Web app and locally host:
    1. Open terminal
    2. cd final_project_ai_engineer_sa/app
    3. pip install -r requirements.txt
    4. python -m flask run