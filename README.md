# Breast Cancer Classification 

**Contributors:**
  1. Heesuk Jang 
  2. Kesha Julien
  3. Rachael Phillips
  4. Tatianna Martinez
  
**Purpose:**
  Intro to Machine Learning (w207) - UC Berkeley

**Objective:** 
  <i> 
  Our goal was to classisfy breast cancer mount slide images into cancerous vs. non-cancerous. These images were obtained from the Kaggle website. We trained a baseline model and then three additional models with include Random Forest, CNN (Convolutional Neural Network), and CNN with transfer learning. 
  </i>
  
  ## Folder Structure
  | Folder | Descriptiion|
  |--------|-------------|
  | Data | Includes two data sets the original cleaned data set titled <i>Dataset</i> and another data set that has images where transformations (normalization, grayscale, augmentation) where applied titled <i>processed_images</i>.|
  | EDA | This folder includes the initial jupyter notebook with some EDA for image classification.|
  | SVM | SVM (Super Vector Machine) directory obtains two jupyter notebooks. One with a baseline model that was trained using the Dataset images after the preprocessing stage. Another SVM model that was trained using the transformed images. We noticed that the SVM model was not a good model to continue training on after trying to train with our tranformed issues.|
  | Random Forest | This folder holds the code for the Random Forest Model which was optimized using Randomize Search CV from sklearn.|
  | CNN |This folder obtains the first CNN model that was trained where we played with a number of filters, kernels, and layers during tuning. |
   | CNN Transfer Learning | This folder contains four different notebooks where four experiements were held for tuning with the best being CNN with ResNet50. |
