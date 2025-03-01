### Oil Spill Detection using SAR Data and Machine Learning

####  Project Overview

This project focuses on detecting and classifying oil spills using Synthetic Aperture Radar (SAR) data through Machine Learning (ML) and Deep Learning (DL) techniques. The study was conducted as part of an academic assignment at the Faculty of Geo-Information Science and Earth Observation (ITC), University of Twente.

####  Methodology

The project employs a combination of traditional ML techniques and deep learning-based semantic segmentation for oil spill detection, overcoming challenges like speckle noise, class imbalance, and false alarms.

####  Techniques Used:

- **Exploratory Data Analysis (EDA)**
- **Traditional Machine Learning (ML)**
  - Random Forest
  - Feature Engineering (GLCM-contrast, Kernel Filtering)
- **Deep Learning (DL)**
  - DeepLabV3+ for semantic segmentation
  - U-Net for pixel-wise classification

####  Results metrics

The models were evaluated based on:

- **Overall Accuracy**
- **Intersection over Union (IoU)**
- **Classification Report**

#### Dataset

The project utilizes SAR satellite imagery to classify oil spills and distinguish them from look-alikes caused by meteo-oceanographic events.

#### Requirements

To reproduce the results, you may need the following:

- Python (3.x)
- TensorFlow / PyTorch
- Scikit-learn
- OpenCV
- GDAL

#### Contributors

- **Group Project**
- Rezaul Hasan Bhuiyan
- Abdul-Raheem Umar
- Kaushal Kishor
- Patrícia C. Genovez

#### 🗓 Date

November 10, 2023

#### Citation
This project is mostly a reuse of the work of Krestenitis, So,
If you use this project, please cite:

*Krestenitis, M., Orfanidis, G., Ioannidis, K., Avgerinakis, K., Vrochidis, S., & Kompatsiaris, I. (2019). Oil spill identification from satellite images using deep neural networks. Remote Sensing, 11(15), 1762.*
