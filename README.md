# Chest X-Ray Classification Project
This repository contains a project focused on building and training a machine learning model to classify chest X-ray images for detecting specific findings, such as "Infiltration." The dataset used for this project is a subset of the NIH Chest X-ray Dataset.

## Project Overview
**Data Preprocessing**:

Images were resized to 224x224 resolution and normalized.  
Labels were processed into binary classes for simplicity.  
TensorFlow's tf.data pipeline was utilized for efficient data loading, caching, and batching.  
