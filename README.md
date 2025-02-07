# **Satellite Image Segmentation using U-Net Neural Networks**

**Authors:** Petrus Salminen, Daniel Richter  

**Institution:** Karls-Ruprecht-Universität Heidelberg  

**Year:** 2021  

**Grade:** 1.7 (German Grading Scale)  

---

## 📖 **Overview**
This repository contains the final project for the **Advanced Machine Learning** course, focusing on **semantic segmentation of satellite images** using the **U-Net neural network architecture**. This project involves:
- Processing high-resolution satellite imagery.
- Applying segmentation techniques to classify pixels into four distinct categories: **FOREST**, **FIELDS**, **URBAN**, and **WATER**.
- Comparing U-Net variations, including **ResNet18** and **Inception V1** backbones.

---

## **Results**

### **Satellite Image Before and After Segmentation:**
<div style="display: flex; flex-direction: row;">
  <img src="sat.png" alt="Satellite Image" style="width: 10cm; margin-right: 50px;">
  <img src="bo128.png" alt="Segmented Image" style="width: 10cm;">
</div>

---

## 🛠 **Technologies Used**
- **Deep Learning Frameworks**: TensorFlow, Keras
- **Programming Languages**: Python
- **Geospatial Tools**: QGIS, GDAL
- **Satellite Data Sources**: Bing Maps, OpenStreetMap

## 📊 **Evaluation Metrics**
- **Categorical Accuracy**: Up to **91.21%** on the validation dataset.
- **Jaccard Coefficient**: Up to **0.7609**.

---

## 📄 **Project Highlights**
- **Data Preparation:** Processed satellite imagery from the Frankfurt area with custom annotations for better accuracy.
- **Model Training:** Experimented with different hyperparameters, loss functions, and backbone architectures.
- **Optimization:** Improved segmentation accuracy by refining the dataset and model parameters.
- **Visualization:** Demonstrated the effectiveness of U-Net in segmenting real-world satellite imagery.

---

## 📩 **Contact & Reference**
Feel free to explore the repository or reach out for further information:
- [GitHub Repository]([[https://github.com/petsal96/aml-fp-repo](https://github.com/drichter-official/AdvancedMachineLearning-Final-Project)](https://github.com/drichter-official/AdvancedMachineLearning-Final-Project))
---

For more details, check the full **project report** available in this repository!

