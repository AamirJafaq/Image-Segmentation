# Image-Segmentation
Image Segmentation
The image segmentation data is a complex and large data set. The instances were
drawn randomly from a database of 7 outdoor images. The images were hand
segmented to create a classification for every pixel. Each instance is a 3x3 region.
The seven outdoor images are brickface, sky, foliage, cement, window, path, grass.
In this project, we applied first implement K-Means clustering to find intrinsic
groups within this dataset, getting it misfit, we applied an ML algorithm (SVC) to
train an SVM classification model with default options for hyperparameters and
computed different classification scores for the training and testing set.
Finally, we applied the ensemble algorithm GradientBoostingClassifier also and
compared the accuracies.
