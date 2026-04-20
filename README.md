# Temporal Action Segmentation using TCN (GTEA Dataset)

## 📌 Overview
This project implements a Temporal Convolutional Network (TCN) for action segmentation on the GTEA dataset. The model learns temporal dependencies in sequential video data and predicts frame-wise activity labels.

---

## 📂 Dataset
- **Name:** GTEA (Georgia Tech Egocentric Activities)
- **Link:** https://ai.stanford.edu/~alireza/GTEA/

---

## ⚙️ Methodology
- Data preprocessing and normalization
- Custom PyTorch Dataset & DataLoader
- Temporal Convolutional Network (TCN)
- Frame-wise classification using CrossEntropyLoss

---

## 📊 Results
- Precision: ~0.65  
- Recall: ~0.59  
- F1 Score: ~0.60  

The model demonstrates effective learning of temporal patterns with a steady decrease in training loss.

---

## 📈 Visualizations
- Training Loss Curve  
- Confusion Matrix  
- Sample Predictions  

---

## 🧠 Key Learnings
- Handling sequential data in deep learning  
- Importance of tensor shape alignment  
- Temporal modeling using 1D convolutions  

---

## 🛠 Tech Stack
- Python  
- PyTorch  
- NumPy  
- Matplotlib  
- Scikit-learn  

---

## 🚀 Future Improvements
- Use deeper TCN architecture  
- Apply data augmentation  
- Improve class imbalance handling  

---

## 👤 Author
Lakshya Verma
