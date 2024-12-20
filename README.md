# Optimize Animal Tranquilizer Aiming System

Term project for the course: `Neural Networks and Deep Learning`. This project emphasizes improving the tracking of animals in real-time to ensure that the tranquilizer accurately aims at the target.

The dataset used is [Oxford IIIT Pets dataset](https://www.robots.ox.ac.uk/~vgg/data/pets/). The dataset itself contains the respective maskings.

![image](https://github.com/user-attachments/assets/a3c593a9-3169-48a2-a2fd-41cc6d564f4e)

We have developed a model to track the motion of the animal by masking the animal to represent the trace of the tracking achieved by our model.

We have worked with three models, namely:
1. Simple Unet
2. Unet CNN
3. FPN with ResNet34

## Evaluation Plots

### Simple Unet  
    
![image](https://github.com/user-attachments/assets/451a21b2-0467-4e9c-8224-b8173bda2f65)

### Unet CNN  

![image](https://github.com/user-attachments/assets/59e5c650-0af2-4eb3-9400-b200c5dd00bf)

### FPN with ResNet34  

![image](https://github.com/user-attachments/assets/0797877c-1fad-4ce7-bc32-1226ec20c6b2)

## Model Comparison

![image](https://github.com/user-attachments/assets/a81e1233-6c19-4bc1-8971-7237bae3fd4b)

## Inference

To showcase the results, we use images and videos to prove its effectiveness.

### Unet CNN  

![image](https://github.com/user-attachments/assets/b661384b-78df-4abb-b18c-4e7230e3b786)

### ResNet34  
    *Video to be added*
