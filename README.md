# 🩺 Diabetes Associated Retinal Detection (DARD)

A Machine Learning-based web application to detect and classify Diabetic Retinopathy (DR) from retinal images. The system allows medical professionals to upload retinal fundus images, receive predictions based on the severity of DR, and download diagnostic reports in PDF format.

---

## 📌 Project Overview

Diabetic Retinopathy (DR) is a complication of diabetes that affects the eyes and can lead to blindness. Early detection is critical. DARD uses Convolutional Neural Networks (CNNs) to analyze retinal images and classify the severity of DR into one of five stages:

- **0: No DR**
- **1: Mild**
- **2: Moderate**
- **3: Severe**
- **4: Proliferative DR**

---

## 🛠 Tech Stack

**Python:** - Programming Language 

**Streamlit:** - Web app framework

**TensorFlow / Keras** – Deep learning framework used to build the CNN model

**NumPy / Pandas** – Data processing and manipulation

**Scikit-learn** – Model evaluation (classification report, confusion matrix)

**FPDF** – Generating PDF reports with prediction results

### 📦 Other Tools
- **OpenCV / PIL** – Image loading and preprocessing
- **Matplotlib / Seaborn** – Visualizing training performance (accuracy, loss, etc.)
- **Jupyter Notebook** – Model training and evaluation environment

### 💾 Dataset
- **Kaggle** – Diabetic Retinopathy Retinal Image Dataset ("sovitrath/diabetic-retinopathy-224x224-2019-data")

---

## 🧠 Features

- ✅ Upload retinal images via a user-friendly web interface
- ✅ Predict DR severity using a trained CNN model
- ✅ Display model confidence level
- ✅ Generate and download a detailed PDF report
- ✅ Show doctor and patient details in reports
- ✅ Visualizations: Confusion matrix, accuracy/loss graphs, classification report


---

## 🧪 Model Summary

- **Framework**: TensorFlow / Keras
- **Architecture**: CNN with multiple Conv2D, MaxPooling, Dropout, Dense layers
- **Epochs**: 30
- **Image Size**: 224x224
- **Data Augmentation**: Yes (rotation, flipping, zoom)
- **Class Imbalance Handling**: Class weights
- **Evaluation Metrics**: Accuracy, precision, recall, confusion matrix

---

## 📈 Results

- Training Accuracy: ~93%
- Validation Accuracy: ~67%
- Classification Report and Confusion Matrix included in Jupyter notebook

---

## 📄 PDF Report Includes

- Patient Name, Age, Gender
- Doctor Name, Designation
- Upload Date and Time
- DR Prediction and Severity Level
- Model Confidence Score
- Doctor's Advice and Signature

---

## 🎥 Sample Usage

    1. Enter basic details of doctor and patient.

    2. Upload a Retinal Images.

    3. Click the "Submit" button to get Prediction.

    4. Download result in pdf format.

---

## 🚀 About Me
**Name:** Sameer Ahmad

**GitHUb:** SAhmad0000

---

## 🙏 Acknowledgements

 - [Kaggle]("sovitrath/diabetic-retinopathy-224x224-2019-data"): For Diabetic Retinopathy Retinal Image Datase.

 - [Website](https://dardtrail111.streamlit.app/): Website Address.

 - [Streamlit](https://streamlit.io/): For enabling fast web application deployment.
 
## Thank You for Visiting!
