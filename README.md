# TCC-Detection-INSAT
AI/ML-based algorithm for identifying Tropical Cloud Clusters using INSAT-3D half-hourly IR Brightness Temperature data
# Tropical Cloud Cluster Detection using INSAT-3D

This project develops an AI/ML-based algorithm to identify and track Tropical Cloud Clusters (TCCs) using half-hourly INSAT-3D Infrared Brightness Temperature (IRBT) data.

## 📌 Objectives
- Detect TCCs using IRBT thresholding
- Calculate features such as:
  - Convective latitude & longitude
  - Pixel count & cluster size
  - Mean, min, max, and median Tb
  - Cloud-top height
- Track TCC movement over the Indian Ocean region

## 📂 Project Structure
TCC-Detection-INSAT/
│── data/ # Satellite data files (.h5)
│── notebooks/ # Jupyter notebooks for analysis
│── src/ # Core Python scripts
│── output/ # Processed results, plots
│── docs/ # Documentation
│── requirements.txt
│── README.md

## 🛠️ Technologies
- Python 3.10+
- Numpy, Pandas, Matplotlib, Cartopy
- OpenCV / Scikit-image for cloud cluster identification
- h5py / xarray for satellite HDF5 file handling
- TensorFlow / PyTorch (future ML integration) 

## 📧 Contact
Maintainer: Shireesha Reddy  
