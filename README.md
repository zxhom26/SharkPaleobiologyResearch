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
- A **linear** statistical dimension reduction method to better identify similarities between observations with multiple attributes. 
## Step 4
### t-Distributed Stochastic Neighbor Embedding (t-SNE)
- A **non-linear** statistical dimension reduction method to better identify similarities between observations with multiple attributes.
## Step 5
### Plot Data and Interpret Results
- A comparison between performance of two dimension reduction techniques
## Packages Used 
- `OpenCV`: computer vision for image processing
- `pyEFD`: elliptical fourier analysis, normalization, and contour reconstruction
- `SciKitLearn`: pca and tsne reduction
- `Pandas`: DataFrame management
- `matplotlib`: data visualization
