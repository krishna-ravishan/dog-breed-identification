#🐶 End-to-end Multi-class Dog Breed Classification
This notebook builds an end-to-end multi-class image classifier using TensorFlow 2.0 and TensorFlow Hub.

1. Problem
Identifying the breed of a dog given its image. For example, when I'm sitting at a cafe and I take a photo of a dog, I want to know what breed of dog it is.

2. Data
The data we're using is from Kaggle's dog breed identification competition.

https://www.kaggle.com/competitions/dog-breed-identification/data

3. Evalutation
Evaluation are based on a Multi-Class Log Loss. The evaluation is a file with prediction probabilities for each dog breed for each test image.

https://www.kaggle.com/competitions/dog-breed-identification/overview

4. Features
Some information about the data:

We're dealing with images (Unstructured Data) so it's probably best we use Deep Learning / Transfer Learning.
There are 120 breeds of dogs (This means there are 120 different classes, therefore multi-class classification.)
Training Data Points (10,200 Images). These images have labels.
Test Data Points (10,200 Images). These images have no labels, because we'll want to predict them.
