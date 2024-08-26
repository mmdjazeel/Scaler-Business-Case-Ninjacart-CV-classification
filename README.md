# Scaler-Business-Case-Ninjacart-CV-classification

### Problem Statement

Ninjacart, India's largest fresh produce supply chain company, is at the forefront of solving complex supply chain challenges using innovative technology. They specialize in sourcing fresh produce from farmers and delivering it to businesses within 12 hours. As part of their automation process, they require robust classifiers capable of distinguishing between different types of vegetables and accurately labeling images that do not contain a specific vegetable type as noise.

Ninjacart has provided a dataset scraped from the web, containing images categorized into onions, potatoes, tomatoes, and market scenes. The task is to develop a multiclass classifier that can accurately identify these vegetables and distinguish them from non-vegetable images (noise).

### Dataset

The [dataset](https://drive.google.com/file/d/1clZX-lV_MLxKHSyeyTheX5OCQtNCUcqT/view?usp=sharing) is organized into two main folders: **train** and **test**, each containing four subfolders corresponding to the following categories:

1. **Tomato**
2. **Potato**
3. **Onion**
4. **Indian market (noise)**

#### **Train Folder:**
- **Tomato:** 789 images
- **Potato:** 898 images
- **Onion:** 849 images
- **Indian market:** 599 images

Total: 3135 images

#### **Test Folder:**
- **Tomato:** 106 images
- **Potato:** 83 images
- **Onion:** 81 images
- **Indian market:** 81 images

Total: 351 images

### Context

The dataset includes images of three vegetables (onion, potato, tomato) and images of Indian market scenes labeled as noise. The images were collected through web scraping from Google.

### Objective

The goal is to develop a program that can recognize and classify vegetable items in photos and correctly identify non-vegetable images as noise.

### Concepts Tested

This project will involve the following concepts:

- **Dataset Preparation & Visualization:** Preparing the dataset for modeling and visualizing the images.
- **CNN Models:** Developing convolutional neural network models for image classification.
- **Implementing Callbacks:** Using callbacks to enhance model training.
- **Dealing with Overfitting:** Techniques to prevent overfitting in the model.
- **Transfer Learning:** Applying transfer learning to improve model performance.
