**Optimizing Cardiovascular Health: Leveraging Deep Learning for Enhanced Real-Time Detection of Coronary Artery Stenosis**

This repository contains the code, Results, and documentation for the project "Optimizing Cardiovascular Health: Leveraging Deep Learning for Enhanced Real-Time Detection of Coronary Artery Stenosis", conducted as part of the MSc Data Analytics program at the University of Warwick.

**Overview**

This project explores the application of deep learning models—Faster R-CNN, DETR, and YOLOv5—for the detection and classification of coronary artery stenosis from angiographic images. By leveraging these cutting-edge techniques, the project aims to enhance diagnostic accuracy and processing efficiency for real-time clinical applications.

**Objectives**

Develop and train deep learning models to detect coronary artery stenosis.
Compare model performance based on key metrics such as mAP, F1-score, and inference time.
Identify a suitable model for real-time clinical deployment.
Analyze the strengths and weaknesses of the models to propose improvements.
Key Features

**Faster R-CNN:** High accuracy and detailed localization with ResNet backbones.
**DETR (Detection Transformer):** Global context consideration using transformer-based architecture.
**YOLOv5:** Real-time object detection optimized for speed and efficiency.
**Data Preprocessing:** Normalization, augmentation, and custom annotations using tools like LabelBox and COCO API.
**Evaluation Metrics:** ROC AUC, Precision-Recall curves, mAP, and F1-score.
Dataset

The dataset comprises 8,325 angiographic images, annotated for stenotic regions. Data preprocessing includes normalization and format conversions for compatibility with the selected models.

**Technologies Used**

**Programming Languages:** Python
**Deep Learning Frameworks:** PyTorch, TensorFlow
**Libraries:** Torchvision, COCO API, Timm, PyTorch Lightning
**Visualization Tools:** Matplotlib
**Hardware:** Google Colab Pro (Tesla T4 GPU), local development on MacBook Air M2.

**Results**

**YOLOv5:** Best suited for real-time applications due to its speed and efficiency.
**Faster R-CNN:** Offers the highest accuracy for detailed localization.
**DETR:** Balances global context with accuracy but has higher computational requirements.

**Future Work**

Explore unsupervised learning techniques for stenosis classification.
Integrate advanced logging and role-based access for scalable deployment.
Improve generalizability across diverse patient datasets.
Contact

For any inquiries, please contact:

**Author:** Rifhath Aslam Jageer Hussain
**Email:** rifhathaslam.jr.162@gmail.com
**LinkedIn:** [Rifhath Aslam](https://www.linkedin.com/in/rifhath-aslam-j-791a6a21b/)
