Mangrove Deforestation Mapping Using Integrated SAR and Optical Imagery with XGBoost
This repository contains the source code, notebooks, and workflow developed for an undergraduate thesis entitled:

“Mangrove Deforestation Mapping Using Integrated SAR and Optical Imagery with the XGBoost Algorithm (Case Study: Cilacap Regency, Indonesia)”

The research aims to map mangrove land cover and analyze mangrove deforestation in a spatial–temporal manner by integrating optical and radar satellite imagery using a machine learning approach.

🛰️ Data Used

Sentinel-1 (SAR)

Acquisition mode: IW

Polarization: VV & VH

Spatial resolution: 10 m

Sentinel-2 (Optical)

Level-2A (Surface Reflectance)

Bands with 10 m and 20 m spatial resolution

Training and Validation Samples

Format: CSV / Shapefile 

Used for training and validating the classification model

🧪 Research Methodology

The overall research workflow consists of the following steps:

Image Preprocessing

Radiometric and geometric preprocessing

Cloud masking for Sentinel-2 imagery

Speckle filtering and terrain correction for Sentinel-1 imagery

Feature Extraction

Optical features: spectral bands and vegetation indices

SAR features: backscatter coefficients and polarization ratios

Feature Selection

Recursive Feature Selection (RFS)

Extremely Randomized Trees (ERT)

Feature importance analysis

Land Cover Classification

Classification using the XGBoost algorithm

Comparison between SAR-only, Optical-only, and combined datasets

Accuracy Assessment

Confusion matrix

Overall accuracy, producer’s accuracy, user’s accuracy, and Kappa coefficient

Mangrove Deforestation Analysis

Post-classification comparison

Spatial–temporal analysis of mangrove loss (2020–2024)
