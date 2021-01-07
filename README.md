# Ocular-disease-image-recognition
This is a practice using Convolutional Neural Networks (CNN) model for image recognition. The repository includes a brief inroduction of CNN model (see details in  <a href='https://github.com/junglewill/Ocular-disease-image-recognition/blob/master/Final.pdf'>Final.pdf</a> ) and the model application using keras. The programming language for this project is python.

## Data Source & Management Command
The data source for this project is from <a href='https://www.kaggle.com/andrewmvd/ocular-disease-recognition-odir5k'>Kaggle - Ocular Disease Recognition</a>. The dataset contains 6,392 images of left and right eyes for approxiamte 3,500 patients collected by Shanggong Medical Technology Co., Ltd. The patients are classified into 8 groups, based on their specific ocular disease: Normal (N), Diabetes (D), Glaucoma (G), Glaucoma (G), Cataract (C), Age related Macular Degeneration (A), Hypertension (H), Pathological Myopia (M), Other diseases/abnormalities (O).

## Models and Approaches
#### Training data:
1. Binary - Normal (N) to Other Diseases
2. Multi-categories
3. Categories exploration
   * Normal (N) to Diabetes (D) to Other Diseases
   * Cataract (C) to Other Diseases
   * All the diseases wiothout Normal (N)

#### Approach and preprocessing of data:
1. Merge images and Separated images: predict the diagnose based on both eyes of a patient vs. predict the diagnose based on each single eye
2. RGB and Grayscale: using the original colored images vs. changing into grayscale images

#### Model:
1. Built CNN model: 2 Convolution Layers & Max Pooling using Relu, Sigmoid, and Softmax activation with Gradient Descent optimizer.
2. VGG19

## Contributors
It was a group project created in the Data Analytics course at Columbia University.

Team member: 


  
