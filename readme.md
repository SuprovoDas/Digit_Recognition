Digit Recognition using CNN on synthetic digit dataset.
STEPS:--
1. Generate synthetic digit's image using functions of 'Pillow' python libary. 100 images of each digit is generated with their labels for classification purpose.
2. The whole dataset is divided into 75-25 for training and validation of the model.
3. create a sequential model containing 2 conv2d, 2 maxplool, 1 flatten and 2 dense layer for image classification using CNN.
4. Softmax activation function is used in last dense layer for getting final output labels of each image.
5. The model is fitted with 10 epoch and batch size of 42.
6. The model perform arround 99% accuracy on train and validation data.
7. Model loss/accuracy is shown in line chart where X-axis denotes No of epochs and Y-axis denotes Loss/Acuuracy.
