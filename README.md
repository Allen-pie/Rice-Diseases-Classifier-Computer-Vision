
# Rice Plant Diseases Classification
<p align="center">
  <img src="https://github.com/user-attachments/assets/8afa2594-c44b-4331-9855-bd5d45901882" alt="DL-DEMO-GIF"/>
</p>

This repository presents a Rice Plant Diseases Classifier that utilizes **computer vision** feature extraction techniques combined with a fully connected **Artificial Neural Network (ANN)** for classification.

The main objective of this project is to evaluate the effectiveness of different feature extraction methods for rice disease classification and integrate the best-performing model into a simple web-based application.


## Experiments

**ANN Classifier Architecture**
<p align="center">
  <img width="817" height="65" alt="classifier layer" src="https://github.com/user-attachments/assets/f43b1f44-34a2-43ae-a5d0-a32e06dcf3d2" />
</p>


The resulting feature vectors were classified using the same defined architecture.
Three main experimental setups were conducted:

**Experiment 1**

Feature extraction techniques used:
- **Color Features: HSV Histogram**
- **Shape Features: Hu Moments**
- **Texture Features: Haralick Features**

**📊 Result**
<img width="578" height="261" alt="3h-cr" src="https://github.com/user-attachments/assets/295e2331-7186-4424-9558-734680e8f26a" />


**Experiment 2**

Feature extraction techniques used:
- **Color Features: HSV Histogram**
- **Shape Features: Hu Moments**
- **Texture Features: Haralick Features**
- **Spatial Texture Features:Gray Level Co-occurrence Matrix (GLCM)** 


**📊 Result**
<img width="568" height="257" alt="3h-glcm-cr" src="https://github.com/user-attachments/assets/41e98ed0-9b0d-46ec-8380-a5b441f55794" />


**Experiment 3**

Feature extraction techniques used:

- **ORB (Oriented FAST and Rotated BRIEF)**
- **Bag of Visual Words (BoVW)**


**📊 Result**

![classification report](https://github.com/user-attachments/assets/fbbba170-bddf-4287-9686-2032c6bc2abf)



## Conclusion
Based on the experimental results, **Experiment 1** performance came on top.


## Dataset
Original Dataset Sources:

**Kaggle 1**

- https://www.kaggle.com/datasets/minhhuy2810/rice-diseases-image-dataset/data


**Kaggle 2**

- https://www.kaggle.com/datasets/dedeikhsandwisaputra/rice-leafs-disease-dataset

**UC Irvine**

- https://archive.ics.uci.edu/dataset/486/rice+leaf+diseases


**Mendeley Data**

- https://data.mendeley.com/datasets/dwtn3c6w6p/1

Final classes that are chosen: 
**Healthy, Brownspot, Bacterial Leaf Blight & Leaf Blast**


# Application
The trained model is integrated into a web-based application designed to be simple and user-friendly.


## How to Use    
**Upload Image**

    1. Click to upload the leaf of rice plant image
    2. Click "Analyze"
    3. The result and insights will be displayed
    4. Click "Change Image" to upload another image


## Screenshots
<p align="center">
  <img width="1895" height="943" alt="Screenshot 2025-12-17 230524" src="https://github.com/user-attachments/assets/93e90adb-df73-4126-9971-fc56ab93845f" />
  <img width="1897" height="720" alt="Screenshot 2025-12-17 230458" src="https://github.com/user-attachments/assets/14b0ce2c-96f5-4c6e-8ef6-2870afe5feac" />
<img width="1897" height="686" alt="Screenshot 2025-12-17 230216" src="https://github.com/user-attachments/assets/65af8dd9-058c-4c76-bfc3-4b0eaa2b6a08" />
<img width="1891" height="969" alt="Screenshot 2025-12-17 230331" src="https://github.com/user-attachments/assets/7f331f29-8889-45b0-af91-86760042b7c1" />

</p> 

## Demo
<p align="center">
  <img src="https://github.com/user-attachments/assets/f2c4241c-b8ae-470b-afee-dec62f0585cc" alt="DL-DEMO-GIF"/>
</p> 

## Authors

- [Pieter Allen](https://github.com/Allen-pie)
- [Fernando Gunawan](https://github.com/NandoG1)
