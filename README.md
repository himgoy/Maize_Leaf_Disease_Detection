# Maize_Leaf_Disease_Detection
![maize](https://user-images.githubusercontent.com/54285534/131239710-1817dd49-14ed-423a-bbdf-5266c07ab969.jpg)
## Introduction
Plant diseases are the primary cause of low agricultural productivity. Mostly the farmers encounter difficulties in controlling and detecting plant diseases. Thus, early detection of these diseases will be beneficial for farmers to avoid further losses.

## Dataset

The Dataset which we have used is the Plant Village Dataset. The dataset was published by crowdAI during the "PlantVillage Disease Classification Challenge". The dataset contains a total of 4 classes for Maize listed below:

- Corn Gray Leaf Spot : 513
- Corn Common Rust : 1192
- Corn healthy : 1162
- Corn Northern Leaf Blight : 985

Due to the limited computational power, it is difficult to train the classification model locally on a majority of normal machines. Therefore, we used the processing power offered by Google Colab notebook & Kaggle as it connects us to a free TPU instance quickly and effortlessly.

For computation of the model, we have taken the image data size of 224<img src="https://render.githubusercontent.com/render/math?math=\times">224 pixels.

## Results

Using the CNN model, we were able to get the Training Accuracy of 99.09% and Validation Accuracy of 95.96%.
