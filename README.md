# Deep Learning Course Project

## Overview

Welcome to the repository for our deep learning course project! This project encompasses both the source code and datasets used for our exploration and implementation of the convolutional neural network architecture.

## Contents

- **Code:** The `code` directory contains a Jupyter notebook containing all the code for our project and a `model_final` folder containing our trained models.

- **Data:** The `training_dataset` directory contains the dataset utilized in our experiments (provided by the supervisor).

## Dataset

This dataset was obtained using Ptychographic X-ray Tomography on a sample extracted from Solid Oxide Cells.

The microstructure presents three phases (nickel, yttria-stabilized zirconia and pores). 
The accurate segmentation of the three phases is crucial to extract quantitative morphological properties. 

So, the grayscale values need to be reduced to a set of labels, one for each phase. 

In the training dataset, you have:

- data: this folder contains the RAW data (gray-scale) in the TIFF format (16-bit) 
- labels: this folder contains the segmented data (manual segmentation) in the TIFF format (8-bit) 

The goal of the project is to  teach a neural network to perform this segmentation, eliminating the manual intervention. 

## Usage

- **Loading Models:**
  Change the main_path variable in Parameters with the path to your folder that contains the model_final folder and run all the cells in Load Model.

- **Evaluating Results:**
  After loading the model run all the cells in Show Some Results and Prediction to see the results and the ROC curve. To test the model on images with noise run all the cells in Noise. To see results with a noisy model load one of the models with noise (as above) and run all the cells in Evaluation in the corresponding noise type.

## Authors

- David Basilio Rodriguez Cortez (s231486)
- Diego Jimenez Pasillas (s231479)
- Dana Georgiana Toma (s232042)
