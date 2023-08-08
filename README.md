# Semantic Segmentation for Self-Driving Cars

This repository showcases the implementation of a **Semantic Segmentation Model for Self-Driving Cars**. The model is developed on dataset from the 'Lyft Udacity Challenge' for self-driving cars.

## Introduction

Semantic segmentation is a crucial task for enabling self-driving cars to understand their surroundings. By labeling each pixel in an image with its corresponding object class, the model gains a comprehensive understanding of the road scene, which is vital for safe navigation.

## U-Net Architecture

The U-Net architecture is employed in this project due to its effectiveness in capturing spatial information for segmentation tasks. The network features a contracting path for context extraction and an expansive path for accurate segmentation. 

## Dataset

The project utilizes the 'Lyft Udacity Challenge' dataset, which can be accessed on Kaggle using the following link: ([Semantic Segmentation for Self Driving Cars | Kaggle](https://www.kaggle.com/datasets/kumaresanmanickavelu/lyft-udacity-challenge)).

## Result

Training accuracy : 98.02 %
Validation accuracy : 97.78 %

Below are sample results achieved by the model:

![Sample Result](/prediction/1.png)
![Sample Result](/prediction/2.png)

Feel free to explore more results and the model's performance in the project's Jupyter Notebook.

---

By [Your Name]

**Disclaimer:** The project's performance is influenced by factors like dataset quality, preprocessing techniques, and hyperparameter settings. This work is conducted for educational and research purposes.
