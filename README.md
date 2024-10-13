# Image Classification with PyTorch

This project demonstrates **image classification** using a **Convolutional Neural Network (CNN)** built with PyTorch. The project utilizes the **Intel Image Dataset**, which contains images of various scenes (e.g., buildings, forests, glaciers) and demonstrates **data loading, augmentation, model training, and evaluation** techniques.

## **Table of Contents**
- [Dataset](#dataset)
- [Project Structure](#project-structure)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Training the Model](#training-the-model)
- [Results](#results)
- [References](#references)

---

## **Dataset**
The project uses the **Intel Image Classification Dataset**. This dataset contains images divided into six classes:
1. Buildings
2. Forests
3. Glaciers
4. Mountains
5. Seas
6. Streets

You can download the dataset from [Kaggle](https://www.kaggle.com/datasets/puneet6060/intel-image-classification) and place it in the following structure:
datasets/ │ └── intel_image_data/ └── seg_train/ └── seg_train/ ├── buildings/ ├── forest/ ├── glacier/ ├── mountain/ ├── sea/ └── street/


---

## **Project Structure**
. ├── datasets/ # Folder containing the dataset ├── cnn_model.pth # Saved trained model (after training) ├── main.py # Main script for training and evaluation ├── requirements.txt # Python dependencies └── README.md # Project documentation

