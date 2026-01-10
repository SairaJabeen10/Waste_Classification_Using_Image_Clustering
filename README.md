# *Waste Classification Using Image Clustering*

A machine learning project that classifies waste images into multiple categories and predicts whether the waste is recyclable or biodegradable using deep learning and clustering techniques.

---

## What This Project Does:
- Takes a waste image as input  
- Extracts features using a pretrained CNN  
- Groups images using K-Means clustering  
- Classifies the image into a waste category  
- Predicts recyclability of the waste  

---

## Techniques Used:
- Transfer Learning (MobileNetV2)
- CNN Feature Extraction
- PCA for Dimensionality Reduction
- K-Means Clustering
- Supervised Image Classification

---

## Dataset:
- Source: Kaggle Waste Dataset  
- Total Classes: 9  
(Cardboard, Plastic, Glass, Paper, Metal, Food, Textile, Vegetation, Misc.)

| Class | Images |
|------|--------|
| Cardboard | 461 |
| Food Organics | 411 |
| Glass | 420 |
| Metal | 790 |
| Paper | 500 |
| Plastic | 921 |
| Miscellaneous Trash | 495 |
| Textile Trash | 318 |
| Vegetation | 436 |

---

## Workflow:
Image → CNN Features → PCA → K-Means Clustering
→ CNN Classifier → Prediction

---

## Model Performance:
- Clustering evaluated using Silhouette Score & Davies–Bouldin Index  
- Classification accuracy ≈ **65%**  
- Better performance on visually distinct classes  

---

### Hyperparameters:
- Optimizer: Adam  
- Learning Rate: 0.0001  
- Batch Size: 32  
- Epochs: 20  
- Loss Function: Categorical Crossentropy  

---

## Image Upload & Prediction:
- Upload an image via Google Colab  
- Preprocess the image  
- Predict waste category  
- Determine recyclability or biodegradability  
- Display image with prediction result  

---

## Challenges & Limitations:
### Challenges
- Visual similarity between waste categories  
- High dimensional CNN features  
- Class imbalance  
- Weak clustering boundaries  

### Limitations
- Not optimized for real-time deployment  
- Performance depends on dataset quality  
- K-Means assumes spherical clusters  
- PCA may remove fine details  

---

## Ethical & Fairness Considerations:
- Predictions should assist humans, not replace decisions  
- Incorrect classification can affect recycling outcomes  
- Dataset bias may exist  

---

## Setup & Installation:
### Requirements
- Python  
- TensorFlow  
- Scikit-learn  
- OpenCV  
- Matplotlib  
- Seaborn  

### Hardware
- Minimum 8 GB RAM  
- GPU recommended (Google Colab GPU sufficient)

### How to Run
1. Mount Google Drive  
2. Unzip dataset  
3. Run notebook cells sequentially  
4. Train the model  
5. Upload image for prediction  

---

## Conclusion:
This project demonstrates how **Deep Learning and Unsupervised Clustering** can be integrated to build a practical waste management system. Although the model has limitations, it provides a strong foundation for intelligent waste classification and highlights future improvement possibilities.

---

## Team Members:
- Saira Jabeen(23-AI-10) 
- Kainat Moin(23-AI-48) 
- Hafsa Naz(23-AI-56)
- Sabiha Pirzadah(23-AI-84)

**Instructor:** Engr. Hamza Farooqui  
**Institution:** Dawood University of Engineering & Technology  
