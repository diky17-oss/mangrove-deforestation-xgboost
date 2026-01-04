# Mangrove Deforestation Mapping Using Integrated SAR and Optical Imagery with XGBoost

This repository contains the source code, notebooks, and workflow developed for an undergraduate thesis entitled:

**“Mangrove Deforestation Mapping Using Integrated SAR and Optical Imagery with the XGBoost Algorithm (Case Study: Cilacap Regency, Indonesia)”**

The research aims to map mangrove land cover and analyze mangrove deforestation in a spatial–temporal manner by integrating optical and radar satellite imagery using a machine learning approach.

---

## 🛰️ Data Used

1. **Sentinel-1 (SAR)**

   * Acquisition mode: IW
   * Polarization: VV & VH
   * Spatial resolution: 10 m

2. **Sentinel-2 (Optical)**

   * Level-2A (Surface Reflectance)
   * Bands with 10 m and 20 m spatial resolution

3. **Training and Validation Samples**

   * Format: CSV / Shapefile (polygon)
   * Used for training and validating the classification model

---

## 🧪 Research Methodology

The overall research workflow consists of the following steps:

1. **Image Preprocessing**

   * Radiometric and geometric preprocessing
   * Cloud masking for Sentinel-2 imagery
   * Speckle filtering and terrain correction for Sentinel-1 imagery

2. **Feature Extraction**

   * Optical features: spectral bands and vegetation indices
   * SAR features: backscatter coefficients and polarization ratios

3. **Feature Selection**

   * Recursive Feature Selection (RFS)
   * Extremely Randomized Trees (ERT)
   * Feature importance analysis

4. **Land Cover Classification**

   * Classification using the XGBoost algorithm
   * Comparison between SAR-only, Optical-only, and combined datasets

5. **Accuracy Assessment**

   * Confusion matrix
   * Overall accuracy, producer’s accuracy, user’s accuracy, and Kappa coefficient

6. **Mangrove Deforestation Analysis**

   * Post-classification comparison
   * Spatial–temporal analysis of mangrove loss (2020–2024)

---

## 🌱 Land Cover Classes

The classification scheme consists of eight land cover classes:

1. Water Body
2. Built-up Area
3. Bare Land
4. Mangrove
5. Paddy Field
6. Aquaculture Pond
7. Terrestrial Vegetation
8. Coastal Area

---

## 🛠️ Tools and Libraries

* Python
* XGBoost
* Scikit-learn
* Rasterio
* GDAL
* NumPy & Pandas
* Matplotlib / Seaborn

---

## 📁 Repository Structure

```
.
├── data/                # Sample data and data description
├── notebooks/           # Jupyter notebooks for each processing step
├── src/                 # Python scripts
├── results/             # Output maps, figures, and tables
├── docs/                # Additional documentation
├── requirements.txt     # Python dependencies
└── README.md            # Project description
```

---

## 📌 Notes

* This repository is intended for academic and research purposes.
* The code can be adapted for similar mangrove or coastal land cover mapping studies in other regions.

---

## 👤 Author

**Moh. As'adul Kholqi*
