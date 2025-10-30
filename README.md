# Shark Paleobiology Research Project
## Step 1
### Image Processing
- First, we need to process the megatooth images to isolate the silhouette in a B/W image (white: tooth silhouette, black: background)
- I can do this using the computer vision package OpenCV to flatten images, reduce noise, and make them B/W.
## Step 2
### Elliptical Fourier Analysis (EFA)
- Now we'll use elliptical fourier analysis to distinguish groups of species within an assemblage
- From this, we'll obtain 4 coefficients with multiple harmonics
- We'll consider the first 10 harmonics to identify groups using PCA
## Step 3
### Principal Component Analysis (PCA)
- A statistical dimension reduction method to better identify similarities between observations with multiple attributes. 

## Step 4
### Plot Data and Interpret Results
