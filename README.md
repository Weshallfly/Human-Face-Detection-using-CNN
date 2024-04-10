In this project, I have implemented a convolutional network using TensorFlow and Keras to train a model  that detects the location of faces in an image and gives coordinates of the rectangle. 

# Dataset used 
https://www.kaggle.com/datasets/sbaghbidi/human-faces-object-detection/data

# EDA and Preprocessing steps
Due to computation inabilities, using a subset of whole images which have a decent size, i.e. niether too large nor too small.
For data preparation, I resized the images and applied additional padding.
Created 4-dimentional arrays, X_train and X_test to give them as input to CNN model by converting each image to a 3-dimentional array.

# Model Training and result
Further, I fine-tuned the hyperparameters a bit by hit and trail. Due to computational inabilities , it was not possible to apply for all combinations of hyperparameters.
Plotted the history of training to ensure that model is not overfitted.
At the end , we achieved satisfactory results for detecting faces.
