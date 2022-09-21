# Keras_Object_Classifer
using Keras API to implement CNN model to classify images into one of 8 categories.

## Structure
the project's structure is a simple convolution layer followed by Normalization and a maxpool layer. 
the model is only about 15MB large.
![image](https://user-images.githubusercontent.com/55613060/191607833-63a3d636-c9aa-48fe-ac97-c148bf1d397c.png)

## Results
although the structure is nothing fancy, it could detect up to accuracy 99% on training data. 
and a ~97% on testing data after only 15 epochs.
![image](https://user-images.githubusercontent.com/55613060/191608417-55ab426c-5eaa-4f8d-b808-21bdbdfa99a6.png)

## Interface 
finally I used Gradio to make a simple interface for the CNN 
https://huggingface.co/spaces/SeifMostafa/Object_Classifier
