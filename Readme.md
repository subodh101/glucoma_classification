GLAUCOMA CLASSIFICATION using Convolutional Neural Network


DataSet: Glaucoma(40), Non-Glaucoma(360)

Total images: 400

Data Preparation: Cropped the OD area, resized to 597, 597, 3 and normalized all the images

Real-time Data Augumentation: Horizontal flips, Vertical flip, Rotations, Width shift, Height shift, Zooming

Model: Tried out different neural network models and further increased it accuracy by using SVM and XGBoost

Conclusion: Since my data was skewed so SVM and XGBoost really helped in increasing the accuracy of the classifier
