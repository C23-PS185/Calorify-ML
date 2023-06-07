# Calorify-ML
This repository contains a transfer learning model implemented using the DenseNet121 architecture, trained on a dataset with 27 classes. The model achieves an impressive accuracy of 89% on the test dataset.

## Table of Contents
- [Introduction](#introduction)
- [Datasets](#datasets)
- [Model Architecture](#model-architecture)
- [Training](#training)
- [Evaluation](#evaluation)
- [Further Work](#further-work)

## Introduction
Transfer learning is a popular technique in deep learning, where a pre-trained model is utilized as a starting point for a new task. In this repository, we employ the DenseNet121 architecture, which is a deep convolutional neural network known for its excellent performance on image classification tasks. By fine-tuning the pre-trained model on a new dataset with 27 classes, we achieve an accuracy of 89% on the test dataset.

## Datasets:
- [food11](https://www.kaggle.com/datasets/imbikramsaha/food11)
- [Fast Food Classification Dataset - V2](https://www.kaggle.com/datasets/utkarshsaxenadn/fast-food-classification-dataset)
- [Padang Cuisine (Indonesian Food Image Dataset)](https://www.kaggle.com/datasets/faldoae/padangfood)
- [food-101-tiny](https://www.kaggle.com/datasets/msarmi9/food101tiny)

Merged datasets download link:\
https://drive.google.com/file/d/1qN_h9odj_FM7fLehwRbkfgbdFqcYZnEk/view?usp=share_link

We have 27 classes in total:
1. apple_pie
2. ayam_goreng
3. ayam_pop
4. baked_potato
5. burger
6. cheesecake
7. chicken_curry
8. crispy_chicken
9. daging_rendang
10. dendeng_batokok
11. donut
12. french_fries
13. fried_rice
14. gulai_ikan
15. gulai_tambusu
16. gulai_tunjang
17. hot_dog
18. ice_cream
19. omelette
20. pizza
21. ramen
22. sandwich
23. sushi
24. taco
25. taquito
26. telur_balado
27. telur_dadar

We splitted the dataset into:
- Train (20200 images)
- Validaiton (4685 images)
- Test (2359 images)

## Model Architecture
The DenseNet121 architecture is a convolutional neural network with 121 layers, widely used for image classification tasks. It introduces the concept of densely connected blocks, where each layer is directly connected to every other layer in a feed-forward fashion. This architecture facilitates feature reuse and strengthens gradient flow, leading to improved accuracy and efficiency.

## Training
To train the transfer learning model, we start with the pre-trained DenseNet121 weights and fine-tune the model on our dataset. The training process involves several steps, including data preprocessing, data augmentation, and model optimization. By adjusting hyperparameters, such as learning rate, batch size, and number of epochs, we optimize the model's performance on our specific task.

![image](https://github.com/C23-PS185/Calorify-ML/assets/26085135/12c615b3-6410-4993-b183-110608421f0e)
![image](https://github.com/C23-PS185/Calorify-ML/assets/26085135/7288e196-e7d0-48f1-8ce5-301e4f6bec2a)

## Evaluation
The model's performance is evaluated using a separate test dataset, which is not seen during training or validation. In this case, the transfer learning model achieves an accuracy of 89% on the test dataset, demonstrating its ability to generalize well to unseen data.

![image](https://github.com/C23-PS185/Calorify-ML/assets/26085135/8f29c75e-2949-48df-a6b1-4767e479a668)

## Further Work
We plan to add more classes, especially Indonesian dishes using image scraper.






