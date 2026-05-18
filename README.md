# OCTA-Analysis
Automated OCTA image analysis using U-Net++ for vessel segmentation and MLP for diabetic retinopathy classification.

# OCTA-Based Vessel Segmentation and Diabetic Retinopathy Classification

## 📌 Overview
This project presents an automated system for analyzing Optical Coherence Tomography Angiography (OCTA) images to support early detection and severity classification of diabetic retinopathy. The system integrates image preprocessing, deep learning-based vessel segmentation, and machine learning-based classification to extract clinically relevant insights from retinal scans.

---

## 🎯 Problem Statement
Diabetic retinopathy is a major cause of vision impairment worldwide. Manual interpretation of OCTA images is time-consuming and depends heavily on clinical expertise. There is a need for an efficient and automated approach to analyze retinal images and assist in early diagnosis.

---

## 💡 Proposed Solution
This project implements a complete pipeline that:
- Enhances OCTA images using preprocessing techniques  
- Segments retinal blood vessels using U-Net++  
- Extracts features such as vessel density in the foveal avascular zone (FAZ)  
- Classifies diabetic retinopathy severity using a Multi-Layer Perceptron (MLP)  

---

## 🧠 Methodology
1. Image acquisition from OCTA dataset  
2. Preprocessing (denoising and contrast enhancement)  
3. Vessel segmentation using U-Net++  
4. FAZ region extraction  
5. Vessel density calculation  
5. Feature extraction  
6. Classification using MLP  

---

## 📂 Dataset
- OCTA retinal images  
- Classes:
  - Normal  
  - Diabetic  
- Subcategories:
  - Clear  
  - Marked  

*Note: Dataset sourced from OpenICPSR (or equivalent dataset source).*

---

## ⚙️ Technologies Used
- Python  
- TensorFlow / PyTorch  
- OpenCV  
- NumPy, Pandas  
- Matplotlib  

---

## 📊 Results
The model demonstrates high-performance segmentation and promising classification capability.

- Segmentation Accuracy: **99.77%**  
- Classification Accuracy: To be updated  
- Sensitivity: To be updated  
- Specificity: To be updated  

---

## 📁 Project Structure
project-folder/ │── data/ │── preprocessing/ │── segmentation/ │── classification/ │── results/ │── notebooks/ │── requirements.txt │── README.md

## 🚀 How to Run

### 1. Clone the repository
git clone https://github.com/harinisanthakumar22/OCTA-Analysis.git  
cd OCTA-Analysis  

### 2. Install dependencies
pip install -r requirements.txt  

### 3. Run the project
python main.py

---

## 📸 Sample Outputs
Sample OCTA images, segmented vessel maps, and performance graphs are available in the `results/` directory.

---

## 🔮 Future Work
- Improve segmentation accuracy using attention-based models  
- Expand dataset for better generalization  
- Develop a user-friendly interface for clinical use  

---

## 👩‍💻 Author
Harini Santhakumar  
Biomedical Engineering Student  

---

## 📜 License
This project is intended for academic and research purposes only.