# CarND-LeNet-Lab
[![Udacity - Self-Driving Car NanoDegree](https://s3.amazonaws.com/udacity-sdc/github/shield-carnd.svg)](http://www.udacity.com/drive)

![LeNet-5 Architecture](lenet.png)
Implement the LeNet-5 deep neural network model.

### Dependencies
This lab requires:

* [CarND Term1 Starter Kit](https://github.com/udacity/CarND-Term1-Starter-Kit)

The lab enviroment can be created with CarND Term1 Starter Kit. Click [here](https://github.com/udacity/CarND-Term1-Starter-Kit/blob/master/README.md) for the details.

## Implementation Details:
* 2 layers ov convolutions followed by max pooling
* 3 fully connected layers (last is output)
*    weights = {
    'wc1': [5, 5, 1, 6],
    'wc2': [5, 5, 6, 16],
    'wd1': [5*5*16, 120],
    'wd2': [120, 84],
    'out': [84, n_classes]}
**validation accuracy achieved 0.988
** Test accuracy: 0.989

* Additional Cells created to test accuracy on 1 or group of images selected from X_train (matches 100%, As expected!!)


