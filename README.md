# 🌟 Lung Cancer Detection using Convolutional Neural Networks (CNN) 🌟

## 📖 Overview

This project focuses on developing algorithms that accurately determine when lesions in the lungs are cancerous using a dataset of high-resolution lung scans provided by the National Cancer Institute. The goal is to reduce the false positive rate in current detection technology, enable earlier access to life-saving interventions, and allow radiologists to spend more time with their patients.

## 📂 Dataset

The dataset includes over a thousand low-dose CT images from high-risk patients in DICOM format. Each image contains a series with multiple axial slices of the chest cavity. The number of 2D slices varies based on the machine and the patient. The DICOM files contain headers with patient ID and scan parameters such as slice thickness.

### Key Points:
- *Source*: National Cancer Institute
- *Format*: DICOM
- *Content*: Low-dose CT images with multiple axial slices
- *Patient Data*: High-risk patients
- *Labels*: Pathology-confirmed ground truth labels

## 🎯 Objective

The task is to create an automated method capable of determining whether a patient will be diagnosed with lung cancer within one year of the date the scan was taken. The algorithm should perform well across a range of image qualities, including older scans with less sophisticated equipment and newer, higher-quality scans.

## 📁 Project Structure

```bash
├── data/            # Contains DICOM files for CT images
├── notebooks/       # Jupyter notebooks for data exploration and model development
├── src/             # Source code for the project, including data preprocessing, model training, and evaluation scripts
├── models/          # Saved models and checkpoints
├── results/         # Results and evaluation metrics
└── README.md        # Project documentation
