# Brain Tumor Detection Notebook 🧠 | CNN | Transfer Learning

# Overview

In this notebook, we investigate the task of detecting brain cancers from MRI scans using Convolutional Neural Networks (CNNs) and Pre-trained Models. Brain tumors are a major health concern worldwide, and early diagnosis is critical to treatment and patient outcomes. With advances in deep learning and medical imaging technologies, CNNs have emerged as valuable tools for automating abnormality identification in medical pictures.

## Dataset Description

This study's dataset consists of MRI (Magnetic Resonance Imaging) scans of the brain obtained from patients with and without brain malignancies. Each image in the collection is labeled 'yes' or 'no' to indicate the presence or absence of a tumor.

## Approach

- **Data Exploration:** We begin by exploring the dataset to gain insights into its distribution, class balance, and image characteristics.
- **Preprocessing:** Prior to model development, we apply normalization techniques to standardize the pixel values across images. Additionally, we apply a cropping function to focus on the region of interest within the brain MRI images, which helps reduce noise and irrelevant information.
- **Model Development:** We design and train CNN architectures tailored for brain tumor detection. We experiment with different network architectures, regularization techniques, and hyperparameters to optimize the model's performance.
- **Evaluation:** We evaluate the baseline and pre-trained models. Additionally, we analyze the model's performance on validation and test datasets to assess its generalization capabilities.
