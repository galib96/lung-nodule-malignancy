# Detection of Lung Nodule Malignancy Using Residual Neural Network

Code: https://github.com/galib96/lung-nodule-malignancy/blob/main/Lung_nodule_malignancy.ipynb

Tha dataset consisted of lung x-ray images classifying the nodule malignancy condition into Normal and Abnormal class. A Residual Neural Network was built using Keras to create a classification model. Adam optimizer was used, initial learning rate was 0.001, binary crossentropy loss as used for loss function amd accuracy was used as evaluation metric during training.

Dataset was splitted in training, test and validation set with ratio of 70:15:15

Training stopped after 37 epochs beacuase of early-stopping callback function.

Final accuracy for test set was 93.4%

Confusion matrix:

![Confusion matrix of Lung nodule malignancy classifier](https://user-images.githubusercontent.com/33948311/179935903-670a0e87-644e-4ca5-ab79-f9eec2c493dd.png)
