# Optimize Animal Tranquilizer Aiming System

> [!Important]
> What's interesting is that the training data is fully cats and dogs, but the model works with new animals too! 
> The model is trained on the Oxford IIIT Pets dataset, which contains 37 classes of pets. 
> The model can be used for any animal.

https://github.com/user-attachments/assets/43c4bf6d-5754-47bc-aa2c-c2daaedee4ef

Term project for the course: `Neural Networks and Deep Learning`. This project emphasizes improving the tracking of animals in real-time to ensure that the tranquilizer accurately aims at the target.

The dataset used is [Oxford IIIT Pets dataset](https://www.robots.ox.ac.uk/~vgg/data/pets/). The dataset itself contains the respective maskings.

![image](https://github.com/user-attachments/assets/a3c593a9-3169-48a2-a2fd-41cc6d564f4e)

We have developed a model to track the motion of the animal by masking the animal to represent the trace of the tracking achieved by our model.

We have worked with three models, namely:
1. Simple Unet `tensorflow` `trained in Google Colab TPU`
2. Unet CNN `tensorflow` `trained in Google Colab TPU`
3. FPN with ResNet34 `pytorch` `trained in Apple M2 Pro with Metal GPU 19 cores.`

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

### FPN with ResNet34  

![image](https://github.com/user-attachments/assets/de01ed13-2d44-43bd-bc80-9a54124c841a)
![image](https://github.com/user-attachments/assets/b62df75f-99e2-4060-9976-3753573b557f)
![image](https://github.com/user-attachments/assets/2671e59a-b621-45d2-b22d-d5bf6e98817f)
![image](https://github.com/user-attachments/assets/150933a6-6794-4879-8851-dacf8a2a1772)

https://github.com/user-attachments/assets/43c4bf6d-5754-47bc-aa2c-c2daaedee4ef


