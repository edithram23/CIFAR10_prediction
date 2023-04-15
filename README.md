# CIFAR10 Image prediction
This is a simple image classification project using the CIFAR-10 dataset and Keras library. The CIFAR-10 dataset 
consists of 60,000 32x32 color images in 10 classes, with 6,000 images per class.

## Installation

To use this Model, you need to follow these steps:

```bash
# Clone the repository to your local machine.
git clone https://github.com/edithram23/CIFAR10_prediction.git
```


# 

* The code imports necessary libraries such as NumPy, Pandas, Keras, 
  TensorFlow, Matplotlib, and OpenCV.
* It loads the CIFAR-10 dataset, which contains 60,000 32x32 color images of 10 different classes, and preprocesses the 
  data by normalizing the pixel values and converting the target variable into categorical form.
* It then builds a convolutional neural network (CNN) model using the Keras Sequential API and trains it on the preprocessed 
  data. The model achieves a high accuracy on the test set, indicating its ability to accurately classify new images.

# Output

![image](https://user-images.githubusercontent.com/106003437/232229951-ed9738c6-17ae-4574-8d40-ef88a44b3558.png)
