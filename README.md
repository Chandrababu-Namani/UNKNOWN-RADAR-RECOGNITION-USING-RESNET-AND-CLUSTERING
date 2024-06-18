# UNKNOWN-RADAR-RECOGNITION-USING-RESNET-AND-CLUSTERING
This system recognizes unknown and known signals and helps in identifying the threat.
Dataset: [link](https://www.kaggle.com/datasets/aleksandrdubrovin/deepsigio-radioml-201801a-new)

**Signals**:<br>
Raw radar signals represented as 3D arrays.<br>
Shape: (532,480 samples, 1024 time steps, 2 components)<br>
**Labels**:<br>
Indicates radar emitter types or modes for each signal sample.<br>
Shape: (532,480 samples, 24-dimensional label vector)<br>
**Signal-to-Noise Ratios** (SNRs):<br>
Reflects the quality of radar signals.<br>
Shape: (532,480 samples, 1 SNR value)<br>

## PROBLEM STATEMENT<br>
In modern radar signal analysis, the identification of unknown radar emitters poses a significant challenges due to the limitation of traditional methods.
To address these challenges, our project aims to leverage machine learning techniques to effectively identify and classify unknown radar emitters, contributing to advancements in defense, security, and airspace management.

## ABSTRACT<br>
This project aims to develop an advanced system using machine learning techniques to accurately identify and classify unknown radar emitters, crucial for defense, security, and airspace management.
<br><br>
The system architecture for radar signal recognition integrates a combination of ResNet and K-Means clustering. 
The process is divided into three main stages: <br>
- Model Training<br>
- Clustering of Features<br>
- Recognition of Signals<br>

