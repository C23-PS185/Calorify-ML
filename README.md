# Calorify-ML
This repository contains a transfer learning image classification model with 25 labels implemented using three different architectures: DenseNet121, InceptionV3, and ResNet50V2. The results revealed that DenseNet121 achieved the highest accuracy, with an impressive 90% accuracy on the test dataset.

## Table of Contents
- [Introduction](#introduction)
- [Datasets](#datasets)
- [Model Architecture](#model-architecture)
- [Training](#training)
- [Evaluation](#evaluation)
- [Further Work](#further-work)

## Introduction
Transfer learning is a popular technique in deep learning, where a pre-trained model is utilized as a starting point for a new task. In this repository, we have trained the model using three different architectures: DenseNet121, InceptionV3, and ResNet50V2. After training the models using the three architectures, we meticulously evaluated their performance. The results revealed that DenseNet121 achieved the highest accuracy, with an impressive 90% accuracy on the test dataset.

## Datasets:
- [food11](https://www.kaggle.com/datasets/imbikramsaha/food11)
- [Fast Food Classification Dataset - V2](https://www.kaggle.com/datasets/utkarshsaxenadn/fast-food-classification-dataset)
- [Food-101](https://www.kaggle.com/datasets/kmader/food41)

Merged datasets download link:\
[dataset](https://drive.google.com/file/d/1L5pwbWQMTK7YiUOhOV1NI4OvdmHLYYO7/view?usp=sharing)

We have 25 classes in total:
1. baked_potato
2. bibimbap
3. cheesecake
4. chicken_curry
5. chicken_wings
6. crispy_chicken
7. donut
8. fish_and_chips
9. french_fries
10. fried_rice
11. hamburger
12. hot_dog
13. ice_cream
14. omelette
15. pizza
16. ramen
17. sandwich
18. spaghetti_bolognese
19. spaghetti_carbonara
20. steak
21. sushi
22. taco
23. takoyaki
24. taquito
25. waffles

We splitted the dataset into:
- Train (20000 images)
- Validation (2500 images)
- Test (2500 images)

## Model Architecture
The DenseNet121 architecture is a convolutional neural network with 121 layers, widely used for image classification tasks. It introduces the concept of densely connected blocks, where each layer is directly connected to every other layer in a feed-forward fashion. This architecture facilitates feature reuse and strengthens gradient flow, leading to improved accuracy and efficiency.

## Training
To train the transfer learning model, we start with the pre-trained DenseNet121 weights and fine-tune the model on our dataset. The training process involves several steps, including data preprocessing, data augmentation, and model optimization. By adjusting hyperparameters, such as learning rate, batch size, and number of epochs, we optimize the model's performance on our specific task.

![image](https://github.com/C23-PS185/Calorify-ML/assets/26085135/395149d8-535d-4d6d-8c97-784b32d6d894)
![image](https://github.com/C23-PS185/Calorify-ML/assets/26085135/e99c0280-c048-44e6-a6da-4eff0f01d508)

## Evaluation
The model's performance is evaluated using a separate test dataset, which is not seen during training or validation. In this case, the transfer learning model achieves an accuracy of 90% on the test dataset, demonstrating its ability to generalize well to unseen data.

![image](https://github.com/C23-PS185/Calorify-ML/assets/26085135/4f4a7acd-58b2-4341-aed1-76f65e3e60fb)

## Further Work
We plan to add more classes, especially Indonesian dishes using image scraper.






