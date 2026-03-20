
# 🍅 AI-TOPSCS: AI-Based Tomato Production & Supply Chain System
<img width="1080" height="1080" alt="Recipes for Tomato Paste" src="https://github.com/user-attachments/assets/c9c5ee93-2267-4878-90f0-f01b3d702388" />


## 📌 Overview

**AI-TOPSCS (AI-Based Tomato Operation, Production, and Supply Chain System)** is an intelligent system designed to **predict tomato yield using satellite data and AI models**, and integrate predictions into an **efficient supply chain management platform**.

The system leverages:

* 🛰️ Satellite imagery (Sentinel-2)
* 🌱 Vegetation indices (NDVI, SAVI, etc.)
* 🤖 Deep learning models (RCNN / Mask R-CNN)
* 🌐 Web-based e-market platform



## 🎯 Problem Statement

Tomato supply chains require **planning at least 2 months in advance**. Incorrect yield predictions lead to:

* Overproduction → wastage
* Underproduction → price spikes
* Inefficient logistics & storage

👉 Goal:

* Predict tomato yield accurately
* Optimize storage, transportation, and marketing
* Reduce losses and improve farmer profit



## 🧠 Key Features

* 📊 Satellite-based crop monitoring
* 🌱 Vegetation index computation (NDVI, SAVI, WDVI, RVI, PVI)
* 🤖 AI-based yield prediction (RCNN / Mask R-CNN)
* 📦 Supply chain optimization
* 🌐 E-market platform (AI-TOPSCS)
* 📈 Demand forecasting & cost prediction

## 🏗️ System Architecture

### 🔹 Stage 1: NDVI & Yield Relationship

* Satellite images of tomato farms collected
* NDVI values extracted
* Analytical relationship developed between NDVI & yield

### 🔹 Stage 2: AI Model Development

* Mask R-CNN / RCNN model trained
* Predicts:

  * Crop health
  * NDVI
  * Tomato yield

### 🔹 Stage 3: Supply Chain Management

* Integration into **AI-TOPSCS e-platform**
* Connects:

  * Farmers
  * Sellers
  * Cold storage
  * Value-added product units


## 🔬 Methodology

### 1. Data Acquisition

* Source: ESA Sentinel-2 satellite
* Resolution: 10m × 10m
* Frequency: Every 5 days
* Data type: Multispectral images



### 2. Data Preprocessing

* Resampling to uniform resolution
* Removal of cloud-affected data
* Cleaning & normalization



### 3. Vegetation Indices (VIs)

Calculated indices:

* NDVI (Normalized Difference Vegetation Index)
* SAVI (Soil Adjusted VI)
* WDVI (Weighted Difference VI)
* RVI (Ratio VI)
* PVI (Perpendicular VI)

👉 These indices help establish **crop health vs yield relationship**

### 4. AI Model (RCNN / Mask R-CNN)

* Performs:

  * Object detection
  * Pixel-level segmentation
* Outputs:

  * Class label
  * Bounding box
  * Mask

👉 Used for:

* Crop identification
* Yield prediction
* NDVI estimation


### 5. Predictive Analytics

* Uses historical + satellite data
* ANN/ML model predicts yield
* Accuracy: ~95% (expected) 



### 6. Supply Chain Optimization

* Demand forecasting
* Storage planning
* Delivery optimization
* Cost prediction



## ⚙️ Tech Stack

### 🔧 Software

* Python
* TensorFlow / PyTorch
* OpenCV
* GIS Tools
* Satellite Data APIs

### 🛰️ Data Source

* ESA Sentinel-2 (Copernicus Hub)



## 🚀 How It Works

1. Satellite captures farm images
2. Vegetation indices are calculated
3. AI model analyzes crop condition
4. Yield is predicted in advance
5. Data is integrated into supply chain platform
6. Decisions made for:

   * Storage
   * Transport
   * Sales



## 📊 Results

* 📈 Accurate yield prediction (~95%)
* 📉 Reduced wastage
* 🚚 Improved logistics planning
* 💰 Better pricing & farmer profit



## 🌐 AI-TOPSCS Platform

A web-based system that connects:

* 👨‍🌾 Farmers
* 🏪 Sellers
* 🧊 Cold Storage Units
* 🏭 Value-added product industries

👉 Enables **smart tomato marketplace & supply chain management**



## 📂 Project Structure

```
AI-TOPSCS/
│── data/
│── models/
│── preprocessing/
│── src/
│── results/
│── web-platform/
│── README.md
```



## 🔮 Future Enhancements

* 📡 Real-time satellite integration
* 🤖 Advanced deep learning models (Transformers)
* 📱 Mobile app for farmers
* 🌍 Multi-crop extension
* ☁️ Cloud deployment

Youtube link: https://youtu.be/TbCPIGtxZdY?si=H3SZ0cysjyrd7icj


## 📜 License

This project is for academic/research purposes.

