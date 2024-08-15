# NEU CS7980 Capstone Project - Team Green Gardians
## Project 1-minute video Youtube Link
[![Watch the video](https://img.youtube.com/vi/lmzzuo7iB9o/0.jpg)](https://www.youtube.com/watch?v=lmzzuo7iB9o)

## Poster

<img width="1136" alt="Screenshot 2024-08-12 at 08 28 35" src="https://github.com/user-attachments/assets/fdf051a1-15a5-423a-8431-ca6878ae8c91">

## Project Description - Forest Vegetation Identification in British Columbia: A Static Algorithm Approach
- **Background**  
  Approximately 57% of British Columbia (BC) is forested, and while deep learning is effective for forest identification, it can be energy-intensive and unsustainable.

- **Goal**  
  The goal of this project is to develop an efficient and eco-friendly forest identification tool to enhance forest management and conservation, and to maintain ecosystem health in BC.

- **Research Objective**  
  The research objective is to utilize Sentinel-2 satellite data and various image processing algorithms through a static algorithm approach to identify forest vegetation in BC, evaluating the performance of different methods in forest identification.

- **Data Source**  
  The data sources for the project include Sentinel-2 L2A satellite imagery (e.g., sample images from the Pitt Meadows area) and Canada's Annual Forest Land Cover data to ensure detection results align with ground truth.

- **Methodology**  
  The methodology employs a static algorithm that combines texture features and NDVI (Normalized Difference Vegetation Index) values to effectively distinguish forested areas, emphasizing environmentally friendly and efficient vegetation classification.

## Folders description
- **Ground Truth**  
  This folder contains land cover data files used as ground truth in our forest vegetation identification project. These TIFF files are crucial for validating the accuracy of our satellite image processing algorithms.

- **Notebooks**  
  This folder houses all Jupyter notebooks used in our project. These notebooks include scripts for data retrieval, preprocessing, satellite image analysis, and algorithm application for forest vegetation identification. 

## Using the notebooks
- It is recommended that all notebooks be run in Google Colab. Ensure that you upload the ground truth files to the runtime Files in Google Colab. If you wish to save your progress, you may need to connect your Google Drive to Colab.
- `Main.ipynb` notebook contains scripts for downloading satellite data, identifying specific geographic locations, applying Laplacian, Sobel, and Gabor methods, and assessing performance.
- `Pitt_GLCM.ipynb` and `Gari_GLCM.ipynb` notebooks include scripts for performing Grey Level Co-occurrence Matrix (GLCM) analysis.
