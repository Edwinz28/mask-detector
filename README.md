# COVID-19 Mask Detection
This repository contains a convolutional neural network attempting to combat the issue of citizens not wearings masks or wearing them incorrectly.
The neural network recieves an image input from a camera/webcam and is able to classify a face into 3 categories: mask, no mask or incorrectly worn mask.

## File Overview
**face_detection.ipynb:** The main driving code. Links the CNN model with opencv to recieve live data input \
**mask-detector.ipynb:** Main code for devloping the CNN \
**mask-detector-svm.ipynb:** Main code for developing the baseline model (SVM) \
**image-preprocessing.ipynb:** Code for preprocessing \
**randomize_mask_colors.ipynb:** File containing data augmentation techniques \
**confusion_matrix.ipynb:** Code for illustrating confusion matrix of main model. Used for making the final video presentation \
**haarcascade_frontal.xml:** Save file for opencv haarcascade classifier \
**/models:** saved models folder \
**IMFD & data:** raw data folders (before preprocessing) \
**data_color_shifted:** dataset folders. After preprocessing & data augmentation
