# Image Classification using VGG16 and SVM

This project demonstrates an image classification pipeline using a pre-trained VGG16 model for feature extraction and a Support Vector Machine (SVM) for classification. The project is designed to classify images of cats and dogs.

## Directory Structure
The project directory is organized as follows:

project_directory/
│  
├── train/  
│   ├── cat/  
│   └── dog/  
│  
├── test/  
│   ├── test_image1.jpg  
│   └── test_image2.jpg  
│  
├── SVM for Cats vs Dogs.py  

## Dependencies
To run this project, you need the following dependencies:
- Python 3.x
- NumPy
- TensorFlow
- Keras
- scikit-learn
- matplotlib

## Dataset
The dataset should be organized into two directories: train and test. The train directory should contain subdirectories for each class (e.g., cat and dog), each containing the corresponding images. The test directory should contain the images you want to classify.

## Usage
- After following all the previously mentioned steps, run the python program in a coding environment of your choice.
- Follow the comment lines to understand the use of the different code snippet sections of the program.
- After training, the SVM model can classify images of cats and dogs with the accuracy obtained from the validation set.
- The classify_images_in_folder function will display the classified images with their predicted labels in the form of plots.
