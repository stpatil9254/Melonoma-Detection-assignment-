# Melonoma-Detection-assignment-
Melonoma Detection assignment 
Problem Statement
In this task, you'll use a customised convolutional neural network in Tensorflow to create a multiclass classification model.

Create a CNN-based model that accurately detects melanoma, which is the problem. If melanoma is not found in its early stages, it can be fatal. It is responsible for 75% of skin cancer fatalities. A system that can analyse photos and notify doctors of the existence of melanoma might potentially eliminate the need for a lot of manual diagnosis work. The International Skin Imaging Collaboration (ISIC) created the collection, which comprises of 2357 photographs of both malignant and benign oncological illnesses. All photos were sorted using the ISIC classification, and each subset was given an equal amount of images.

The data set contains the following diseases:

Actinic keratosis
Basal cell carcinoma
Dermatofibroma
Melanoma
Nevus
Pigmented benign keratosis
Seborrheic keratosis
Squamous cell carcinoma
Vascular lesion
Project Schedule
Defining the train and test picture paths for data reading and data understanding
Create a train & validation dataset with a batch size of 32 from the train directory.
Additionally, be sure to 180*180 resize your photographs.
Dataset visualisation:
Write a programme to display a single instance of each of the dataset's nine classes.
Building and training models:
Make a CNN model that can precisely identify the nine classes that are present in the dataset.
Rescale photos to normalise pixel values between (0,1) when developing the model.
For model training, pick an appropriate optimiser and loss function. 20 iterations of the model training
Write your conclusions once the model has been fitted, and look for any indications of overfitting or underfitting.
Select the best data augmentation technique toi dentify and fix under- or overfitting Building models and training using the augmented data:
Make a CNN model that can precisely identify the nine classes that are present in the dataset. Rescale photos to normalise pixel values between (0,1) when developing the model.
