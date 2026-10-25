#  Waste Classification Using Image Clustering

A Machine Learning and Computer Vision project that combines MobileNetV2, PCA, K-Means clustering, and supervised image classification to classify waste images into nine categories.

##  Overview

This project explores deep learning and unsupervised clustering for waste classification and potential recyclability assessment.

### Objectives
- Classify waste images into nine categories.
- Extract image features using MobileNetV2.
- Reduce feature dimensionality using PCA.
- Group similar images using K-Means clustering.
- Evaluate classification performance.

##  Dataset

**Source:** Kaggle Waste Dataset

| Waste Category | Images |
|---|---:|
| Cardboard | 461 |
| Food Organics | 411 |
| Glass | 420 |
| Metal | 790 |
| Paper | 500 |
| Plastic | 921 |
| Miscellaneous Trash | 495 |
| Textile Trash | 318 |
| Vegetation | 436 |
| **Total** | **4,752** |

## Techniques Used

- Python
- TensorFlow and Keras
- MobileNetV2
- PCA (Dimensionality Reduction)
- K-Means Clustering
- Scikit-learn
- OpenCV
- Matplotlib and Seaborn

##  Project Workflow

```text
Waste Images
     ↓
Image Preprocessing
     ↓
MobileNetV2 Feature Extraction
     ↓
PCA Dimensionality Reduction
     ↓
K-Means Clustering
     ↓
Supervised Classification
     ↓
Waste Category Prediction
```

## Model Performance

The waste classification model achieved **67% overall accuracy** on the evaluation dataset containing 949 samples.

| Metric             | Score |
| ------------------ | ----: |
| Overall Accuracy   |   67% |
| Weighted Precision |   66% |
| Weighted Recall    |   67% |
| Weighted F1-Score  |   66% |

### Class-wise F1-Score

| Waste Category      | F1-Score |
| ------------------- | -------: |
| Glass               |      32% |
| Cardboard           |      90% |
| Vegetation          |      78% |
| Textile Trash       |      73% |
| Metal               |      52% |
| Paper               |      66% |
| Miscellaneous Trash |      58% |
| Food Organics       |      61% |
| Plastic             |      94% |


## Training Configuration
Parameter	Value
Optimizer	Adam
Learning Rate	0.0001
Batch Size	32
Epochs	20
Loss Function	Categorical Crossentropy

## How to Run
Open the notebook in Google Colab or Jupyter Notebook.
Download and prepare the Kaggle waste dataset.
Mount Google Drive if required by the notebook.
Update dataset paths if necessary.
Run the notebook cells sequentially.
Train and evaluate the model.
Upload a waste image to test prediction.

## Challenges and Limitations
Challenge	Approach / Limitation
Similar-looking waste	Difficult to distinguish visually similar materials
High-dimensional features	PCA for dimensionality reduction
Class imbalance	Unequal image counts across categories
Weak cluster boundaries	K-Means may struggle with overlapping categories
Real-world variations	Further testing is needed on real-world images

## Future Improvements
Improve classification accuracy.
Add more diverse waste images.
Test alternative clustering algorithms.
Evaluate the model on real-world images.
Develop a web application for waste classification.
Improve recyclability assessment.

## Team Members
Saira Jabeen	|
Kainat Moin |	
Hafsa Naz	|
Sabiha Pirzadah

## 🎥 Project Demo

[Watch the Demo Video](https://github.com/SairaJabeen10/Waste_Classification_Using_Image_Clustering/blob/main/Demo%20Video.mp4)




## Author

Saira Jabeen

GitHub: SairaJabeen10
