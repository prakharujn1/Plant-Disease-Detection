https://github.com/user-attachments/assets/a6105fd3-911e-4b1d-8466-68b2b3b1a3ff


# source of dataset
https://www.kaggle.com/datasets/vipoooool/new-plant-diseases-dataset this is link of dataset  odel: "sequential_2"
# Plant_disease_prediction
1.The dataset used for training the model is sourced from Kaggle: New Plant Diseases Dataset. 
It includes images of healthy and diseased leaves of various plants.
# Model Architecture
The model is a Convolutional Neural Network (CNN) built using TensorFlow and Keras. 
The architecture includes several convolutional and pooling layers, followed by fully connected layers.
Model: "sequential_2"
_________________________________________________________________
 Layer (type)                Output Shape              Param #   
=================================================================
 conv2d_18 (Conv2D)          (None, 128, 128, 32)      896       
                                                                 
 conv2d_19 (Conv2D)          (None, 126, 126, 32)      9248      
                                                                 
 max_pooling2d_9 (MaxPooling (None, 63, 63, 32)        0         
                                                                 
 conv2d_20 (Conv2D)          (None, 63, 63, 64)        18496     
                                                                 
 conv2d_21 (Conv2D)          (None, 61, 61, 64)        36928     
                                                                 
 max_pooling2d_10 (MaxPoolin (None, 30, 30, 64)        0         
                                                                 
 conv2d_22 (Conv2D)          (None, 30, 30, 128)       73856     
                                                                 
 conv2d_23 (Conv2D)          (None, 28, 28, 128)       147584    
                                                                 
 max_pooling2d_11 (MaxPoolin (None, 14, 14, 128)       0         
                                                                 
...                                                              
Total params: 7,842,762
Trainable params: 7,842,762
Non-trainable params: 0


# Training and Validation Accuracy
Training Accuracy: 0.9924
Validation Accuracy: 0.9686
