# Snowline Detection and Classification Using Sentinel-2 Imagery

This repository contains notebooks and tools for snowline detection and classification on White Glacier using Sentinel-2 satellite imagery. It integrates unsupervised and supervised machine learning workflows including PCA, KMeans clustering, and Random Forest classifiers.

## Repository Structure

* `white_glacier_of_sentinel_2_image_download.ipynb`
  📥 Download and preprocess Sentinel-2 images for White Glacier.

* `Snow line Detection.ipynb`
  ❄️ Extract the snowline from classified images using elevation data.

* `Traning Classifer (PCA + Kmeans).ipynb`
  🤖 Perform unsupervised learning using PCA and KMeans to generate pseudo-labels for classifier training.

## Features

* Automated Sentinel-2 imagery filtering and downloading
* PCA-based dimensionality reduction
* KMeans clustering to generate training labels
* Random Forest classifier training
* Snowline extraction based on classified imagery and elevation band


## Author

Wilson Cheung
PhD Candidate in Glaciology
Queen's University, Canada
