# Integrating-Visual-and-Textual-Features-for-House-Price-Estimation
In this project, the goal is to build a model that predicts house prices using both image and textual information. 
# House Price Prediction Dataset

This project utilizes a benchmark dataset for predicting house prices, which contains both visual and textual information. Each house in the dataset is represented by four images: a bedroom, a bathroom, a kitchen, and a frontal view of the house. The dataset folder contains a total of 2,140 images, with 4 images per house. Additionally, the dataset includes a text file that provides the corresponding textual metadata for each house. Each row in the text file represents one house in sequential order.

## Number of Attributes

The dataset includes 4 textual attributes in addition to the visual features that can be extracted from the images:

1. **Number of Bedrooms**
2. **Number of Bathrooms**
3. **Area**
4. **Zipcode**
5. **Price**

## Project Overview

In this project, the goal is to build a model that predicts house prices using both image and textual information. The approach involves the following steps:

1. **Feature Extraction**: I used the VGG16 model to extract features from the house images. This pre-trained convolutional neural network is effective in capturing visual patterns.
2. **Text Data Processing**: The textual attributes were processed and structured as tabular data, ensuring compatibility with the predictive model.
3. **Model Development**: The extracted image features and processed textual data were combined and fed into a custom model built using Keras, a powerful deep learning framework.

The combination of visual and textual information provides a comprehensive understanding of the properties, enabling the model to make accurate predictions of house prices.


