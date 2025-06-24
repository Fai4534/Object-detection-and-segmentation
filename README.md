# 🧪 Detection and Segmentation of Zones of Inhibition using Detectron2

This project uses Detectron2 to detect and segment zones of inhibition in antibiogram test images. These zones indicate the effectiveness of antibiotics against bacterial growth. Automating this process supports faster and more consistent diagnostic decisions.

---

## 🎯 Business Objective

Antibiograms are used by clinicians to monitor local antibiotic resistance patterns. During lab testing, antibiotics are applied to bacterial cultures, and zones of inhibition—areas with no bacterial growth—are measured to determine susceptibility. This project automates the detection and measurement of these zones using image detection and segmentation.

---

## 🧰 Tech Stack

- Language: Python  
- Libraries: PyTorch, Detectron2, OpenCV, NumPy, Matplotlib

---

## 📁 Folder Structure

- `Input/` includes training and testing folders  
- `Source/` includes modularized scripts  
- `Output/` stores the trained model  
- `Lib/` includes notebooks for experimentation

---

## 🧪 Dataset

The dataset consists of antibiogram test images, annotated in COCO format. After downloading and unzipping, place the data in the `Input/` directory before running the code.

---

## ⚙️ How It Works

1. Register dataset using Detectron2’s API  
2. Configure and initialize the model  
3. Train the model on labeled antibiogram images  
4. Perform inference on new images  
5. Generate bounding boxes and masks for zones of inhibition  
6. Save and visualize the results

---

## 💡 Key Learnings

- Understanding antibiotic susceptibility testing  
- Image classification vs detection vs segmentation  
- Using Detectron2 for medical image analysis  
- Modularizing ML projects for maintainability  
- Visualizing predictions and interpreting masks

---

## 📦 Usage

1. Clone the repository  
2. Install required dependencies  
3. Unzip the dataset and place it in the correct directory  
4. Run training and inference using provided scripts or notebooks

---

## 🔍 Output

The output includes segmented zones of inhibition with bounding boxes and masks for each object detected in the image.

---

## 📌 Notes

- This project is for educational and research purposes.  
- Further validation is required before any clinical application.  
- The model and code are structured for modular use and easy adaptation.

## 🧠 Project Overview

The project includes:

- Data setup and visualization
- Registration of the dataset in COCO format
- Training a Detectron2 model
- Performing inference on new images
- Visualizing and interpreting results

---


