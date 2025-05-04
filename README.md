#  Retinal Disease Detection Using Deep Learning

This project focuses on detecting retinal diseases from fundus images through image classification techniques. It aims to support early diagnosis by identifying conditions such as **Dry AMD**, **Wet AMD**, **Glaucoma**, **Diabetic Retinopathy (Mild/Moderate/Severe/PDR)**, **Cataract**, **Hypertensive Retinopathy**, **Pathological Myopia**, and other retinal pathologies.

##  Project Overview
- Developed and tested entirely in **Google Colab**
- Custom convolutional neural network for multi-class image classification
- Data preprocessing, augmentation, and training pipelines included
- Notebook for real-time prediction interface using Gradio

##  Repository Structure

| File/Folder           | Description                                               |
|-----------------------|-----------------------------------------------------------|
| `model.ipynb`         | Data loading, preprocessing, augmentation, and training   |
| `deployment.ipynb`    | Gradio interface setup and demonstration of real-time use |
| `requirements.txt`    | Pinning of all Python dependencies                        |
| `images/`             | Sample input/output screenshots                           |
| `README.md`           | Project documentation                                     |

##  Accuracy Summary

| Condition                  | Test Accuracy (%) |
|----------------------------|-------------------|
| Dry AMD                    | 89.7              |
| Wet AMD                    | 90.3              |
| Glaucoma                   | 91.2              |
| Mild Diabetic Retinopathy  | 92.1              |
| Moderate Diabetic Retinopathy | 93.5           |
| Severe Diabetic Retinopathy | 91.8             |
| Proliferative DR (PDR)     | 90.6              |
| Cataract                   | 94.0              |
| Hypertensive Retinopathy   | 87.3              |
| Pathological Myopia        | 88.5              |

##  Tools and Libraries

- Python (Jupyter / Colab)
- TensorFlow / Keras
- OpenCV, NumPy, Pandas
- Matplotlib, Seaborn

##  Suggested Enhancements

- Enable real-time image input from devices
- Improve model accuracy using data augmentation and regularization
- Prepare for clinical dataset integration with secured access


