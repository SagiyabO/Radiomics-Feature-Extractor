# Radiomics-Feature-Extractor
This project involves the extraction and analysis of radiomic features from medical imaging data to classify lesions in MRI scans. The primary objective is to distinguish between active and inactive multiple sclerosis (MS) lesions without the use of contrast agents.

## Project Overview

This repository contains Python scripts for loading, processing, and analyzing MRI data, specifically focusing on extracting features from T2, ADC, and PD maps. The goal is to develop machine learning models that can classify lesions into different categories, aiding in the study of multiple sclerosis.

## Key Features

- **Loading MRI Data**: Scripts to load and manage MRI data from `.mat` files. (Using the data from the folder '02_Subjects_reformatted' from the google drive : https://drive.google.com/drive/folders/1RNU2BFO97LkcPQ7oKD9QJCT59Rg7p_KC?usp=drive_link
- **Lesion Segmentation**: Implements methods for lesion segmentation and masking.
- **Data Visualization**: Functions for plotting and visualizing 2D slices and 3D representations of the MRI data.
- **Feature Extraction**: Utilizes the Pyradiomics library to extract radiomic features.
- **Machine Learning Integration**: Prepares data for use with machine learning models to classify lesions.

## Requirements

- Python 3.x
- [Pyradiomics](https://pyradiomics.readthedocs.io/en/latest/)
- NumPy
- Matplotlib
- SciPy
- Plotly
- PIL (Python Imaging Library)
- SimpleITK

To install the required packages, you can run:

```bash
pip install numpy matplotlib scipy plotly Pillow SimpleITK pyradiomics
