# Deep Learning Model with two outputs


## Project Description
In this Work we have a Dataset of a pipe under water and we want to know create a model that can Predict the pipe orientation and the sign of that orientation, so we are in a situation where we have to build a multi output model where it can Predict sign and orientation in the same time

## Project Dataset
|Image 1|Image 2 | Image 3|Image 4| Image 5|Image 6|
|---|---|---|--|--|--|
|![](Dataset_sample/00336.jpg)|![](Dataset_sample/00336.jpg)|![](Dataset_sample/00368.jpg)|![](Dataset_sample/00447.jpg)|![](Dataset_sample/00462.jpg)|![](Dataset_sample/00578.jpg)|![](Dataset_sample/00586.jpg)|![](Dataset_sample/00336.jpg)|

## Models Results

## orientation model Results
Based on **VGG16** architecture

|Orientaion loss|Orientation Mean absolute Error|
|--|--|
|![](Results/orientation_loss.png)|![](Results/orientation_mae.png)|

## sign model Results

|sign loss| sign Accuracy|
|--|--|
|![](Results/sign_loss.png)|![](Results/sign_accuracy.png)|

## Hybrid model Results

|Hybrid model losses| Hybrid model accuracy & MAE|
|--|--|
|![](Results/hybrid_model_losses.png)|![](Results/hybrid_model_mae_accuracy.png)|
