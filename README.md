## X-Ray classification with Transfer Learning in Keras

This is the Keras model for classification of Chest X-Rays into either of the two categories:
* Normal or 
* PNeumonia

### The model used
InceptionV3 pretrained Keras model has been re-trained for this dataset. 

### Data
The dataset used for training has been taken from this kaggle link: https://www.kaggle.com/paultimothymooney/chest-xray-pneumonia

### Accuracy
Obtained :
* Tranining acc : ~91%
* Validation acc: ~80 %

### Some Prediction Visualisations
![](https://github.com/yashprakash13/XRays-Classification-Transfer-Learning-in-Keras/blob/master/out1.png)  ![](https://github.com/yashprakash13/XRays-Classification-Transfer-Learning-in-Keras/blob/master/out2.png)
![](https://github.com/yashprakash13/XRays-Classification-Transfer-Learning-in-Keras/blob/master/out3.png)
