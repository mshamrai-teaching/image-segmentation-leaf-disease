# Computer Vision Course Assignment: Semantic Segmentation with Leaf Disease

## Overview

Welcome to the Semantic Segmentation assignment for the Computer Vision course! In this assignment, your task is to develop a Neural Network (CNN) for binary semantic segmentation of leaf diseases using the provided dataset. The primary goal is to accurately identify and segment diseased regions on plant leaves.

### Getting Started

1. **Join the Kaggle Competition:**
  - Follow the competition link provided to join the Kaggle competition.
  - Familiarize yourself with the competition data and evaluation metric.

2. **Clone this repository to your local machine:**
     ```bash
     git clone https://github.com/mshamrai-teaching/image-segmentation-leaf-disease-*your-name*
     ```
3. **Navigate to the project directory:**
      ```bash
       cd image-segmentation-leaf-disease-*your-name*
      ```

### Guidelines

* Dataset:
  * The training dataset with images and masks is available for semantic segmentation.
  * Utilize the provided data to train your segmentation model.
* Model:
  * Develop any CNN model for binary semantic segmentation.
  * Experiment with different architectures and fine-tuning strategies.
  * Aim to surpass the baseline performance.
* Baseline:
  * The baseline used in this competition is a secret.
  * Your goal is to beat the baseline using your own model architecture and training strategy.
* Evaluation:
  * Submissions will be evaluated based on the Dice loss metric.
  * Aim for a high Dice coefficient to demonstrate accurate segmentation.
 
### Hints

* Architecture:
  * Explore different CNN architectures suitable for semantic segmentation (e.g., U-Net).
  * Consider the depth and complexity of your model.
* Augmentations:
  * Experiment with data augmentations to enhance model generalization.
  * Consider augmentations like random crop, random rotation, and horizontal flip to increase dataset diversity.

### Submission

To submit your solution commit your files to the `main` branch. 

Ensure your final submission includes:
* Source code (semantic_segmentation_leaf_disease.py or similar).
* A brief report (report.md or similar) explaining your model architecture, training strategy, and any challenges faced.

### Evaluation

Your solution will be evaluated based on the Dice loss on the test set. The higher the Dice coefficient, the better the segmentation accuracy.

Good luck, and may the best semantic segmentation model prevail! If you have any questions, feel free to reach out.
