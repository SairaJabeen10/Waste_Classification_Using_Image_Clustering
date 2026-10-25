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
| Metric | Result |
|---|---|
| Classification Accuracy | Approximately 65% |
| Clustering Evaluation | Silhouette Score and Davies–Bouldin Index |

The model performs better on visually distinct categories. Similar-looking waste materials remain challenging to classify.

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

## Author

Saira Jabeen

GitHub: SairaJabeen10
