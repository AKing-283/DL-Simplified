## **Fracture Detection using DL**

### 🎯 **Goal**

The objective of this project is to classify images of x-ray scans of bones, into 2 classes: fracture and not-fractured.

### 🧵 **Dataset**

The dataset consists of 3 subdirectories under the bone_fracture_binary_classification directory, train, test and val, all three with 2 subdirectories: fracture and not-fractured; train with approximately 9200 images, val with approximately 850 and test with approximately 600 images respectively.

### 🧾 **Description**

The project deals with binary classification, classifying images into 2 categories: fracture and not-fractured bone x-ray scans.

### 🧮 **What I had done!**

To achieve our goals, the following steps were implemented:

- Images were loaded using keras.utils and normalized to the range 0 to 1.

- Images were scanned for appropriateness.

- Images were resized to a fixed size of 224x224 pixels.

- Custom and pre-trained models were used for this task.

### 🚀 **Models Implemented**

models used:

- ResNet-50
- Xception
- VGG16
- CNN
- InceptionV3
- DenseNet-121
- MobileNet

### 📚 **Libraries Needed**

- Keras

- Tensorflow

- Numpy

- Matplotlib

### 📊 **Exploratory Data Analysis Results**


- #### **EDA**

<p align="center">
  <img src="https://github.com/Arihant-Bhandari/DL-Simplified/blob/eye-disease/Eye%20Disease%20Classification%20using%20DL/Images/Cataract.png" height="400px" width="400px" />
  <img src="https://github.com/Arihant-Bhandari/DL-Simplified/blob/eye-disease/Eye%20Disease%20Classification%20using%20DL/Images/Diabetic%20Retinopathy.png" height="400px" width="400px" />
</p>

<img src="https://github.com/Arihant-Bhandari/DL-Simplified/blob/eye-disease/Eye%20Disease%20Classification%20using%20DL/Images/EDA.png"/>

- #### **DenseNet-121**

<p align="center">
  <img src="https://github.com/Arihant-Bhandari/DL-Simplified/blob/eye-disease/Eye%20Disease%20Classification%20using%20DL/Images/DENSENET121%20Accuracy.png" height="400px" width="400px" />
  <img src="https://github.com/Arihant-Bhandari/DL-Simplified/blob/eye-disease/Eye%20Disease%20Classification%20using%20DL/Images/DENSENET121%20Loss.png" height="400px" width="400px" />
</p>

- #### **CNN**

<p align="center">
  <img src="https://github.com/Arihant-Bhandari/DL-Simplified/blob/eye-disease/Eye%20Disease%20Classification%20using%20DL/Images/CNN%20Accuracy.png" height="400px" width="400px" />
  <img src="https://github.com/Arihant-Bhandari/DL-Simplified/blob/eye-disease/Eye%20Disease%20Classification%20using%20DL/Images/CNN%20Loss.png" height="400px" width="400px" />
</p>

- #### **InceptionV3**

<p align="center">
  <img src="https://github.com/Arihant-Bhandari/DL-Simplified/blob/eye-disease/Eye%20Disease%20Classification%20using%20DL/Images/InceptionV3%20Accuracy.png" height="400px" width="400px" />
  <img src="https://github.com/Arihant-Bhandari/DL-Simplified/blob/eye-disease/Eye%20Disease%20Classification%20using%20DL/Images/InceptionV3%20Loss.png" height="400px" width="400px" />
</p>

- #### **VGG16**

<p align="center">
  <img src="https://github.com/Arihant-Bhandari/DL-Simplified/blob/eye-disease/Eye%20Disease%20Classification%20using%20DL/Images/VGG16%20Accuracy.png" height="400px" width="400px" />
  <img src="https://github.com/Arihant-Bhandari/DL-Simplified/blob/eye-disease/Eye%20Disease%20Classification%20using%20DL/Images/VGG16%20Loss.png" height="400px" width="400px" />
</p>

- #### **MobileNet**

<p align="center">
  <img src="https://github.com/Arihant-Bhandari/DL-Simplified/blob/eye-disease/Eye%20Disease%20Classification%20using%20DL/Images/MobileNet%20Accuracy.png" height="400px" width="400px" />
  <img src="https://github.com/Arihant-Bhandari/DL-Simplified/blob/eye-disease/Eye%20Disease%20Classification%20using%20DL/Images/MobileNet%20Loss.png" height="400px" width="400px" />
</p>

- #### **RESNET50**

<p align="center">
  <img src="https://github.com/Arihant-Bhandari/DL-Simplified/blob/eye-disease/Eye%20Disease%20Classification%20using%20DL/Images/RESNET50%20Accuracy.png" height="400px" width="400px" />
  <img src="https://github.com/Arihant-Bhandari/DL-Simplified/blob/eye-disease/Eye%20Disease%20Classification%20using%20DL/Images/RESNET50%20Loss.png" height="400px" width="400px" />
</p>

- #### **Xception**

<p align="center">
  <img src="https://github.com/Arihant-Bhandari/DL-Simplified/blob/eye-disease/Eye%20Disease%20Classification%20using%20DL/Images/Xception%20Accuracy.png" height="400px" width="400px" />
  <img src="https://github.com/Arihant-Bhandari/DL-Simplified/blob/eye-disease/Eye%20Disease%20Classification%20using%20DL/Images/Xception%20Loss.png" height="400px" width="400px" />
</p>

### 📈 **Performance of the Models based on the Accuracy Scores**

#### Metrics: 

We used Validation **Loss** and **Accuracy** as metrics.

| Models | Accuracy | Loss |
|--------|---------------------|--------------------------|
| ResNet-50 | 23.06% | 12.4005 |
| InceptionV3 | 87.68%  | 0.3861 | 
| CNN | 87.68% | 0.4260 |
| VGG16 | 91.79% | 0.2457 |
| MobileNet | 90.52% | 0.2863 |
| DenseNet-121 | 92.42% | 0.2208 |
| Xception | 89.42% | 0.3184 |

### 📢 **Conclusion**

We conclude the following:



### ✒️ **Your Signature**

Original Contributor: Arihant Bhandari [https://github.com/Arihant-Bhandari]