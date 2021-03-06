# Food-recognition-2021-AML

The main purpose of the project was to create a complete image classification pipe-line and test different image classification algorithms, ranging from small self-trained networks to larger pre-trained ones like Efficient-Net. 


## The data:
The dataset consists of 30612 images for the training set and 7653 images for the test set. An older version of the data can be found on Kaggle: https://www.kaggle.com/c/food-recognition-challenge/overview

### Files
* train_set - the training set with 30612 images
* train_labels.csv - the correct labels for the training set
* test_set - the test set with 7653 images
* sample.csv - a sample submission file in the correct format

### Data fields
* img_name - The unique identifier for each image
* label - The food category that the image belongs to. This is a value between 1 to 80.

## Code:
### EDA
The EDA folder contains the following files:
* The pipe-line with a self created benchmark model (the Performance is terrible). 
* A small EDA notebook that shows some of the data properties.

### Models:
The models folder contains the following files:
* Model Efficient-net-B4, with an validation accuracy of 67%
* Model x, with an validation accuracy of XX
* Model x, with an validation accuracy of XX


Also, these models where trained on Kaggle with the GPU enabled!
