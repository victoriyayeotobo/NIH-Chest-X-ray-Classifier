# NIH Chest X-ray Classifier

This project uses deep learning to classify chest X-ray images using the [NIH Chest X-ray Dataset](https://huggingface.co/datasets/alkzar90/NIH-Chest-X-ray-dataset/tree/main). The model is trained to detect multiple thoracic diseases from frontal-view X-ray scans.

## Project Summary

- **Task**: Multi-label image classification
- **Model**: Convolutional Neural Network (CNN)
- **Dataset**: NIH Chest X-ray (over 112,000 images)
- **Source**: [NIH Chest X-ray Dataset on HuggingFace](https://huggingface.co/datasets/alkzar90/NIH-Chest-X-ray-dataset/tree/main)

## Repository Contents

- `NIH_Chest_X_ray.ipynb` — Jupyter notebook with all code: preprocessing, training, and evaluation
- `requirements.txt` — Python dependencies (if applicable)

## How to Run the Project 

1. Clone the repository:

```bash
git clone https://github.com/YOUR_USERNAME/NIH-Chest-X-ray-Classifier.git
cd NIH-Chest-X-ray-Classifier

2. Install required packages:
pip install -r requirements.txt


3. Launch the notebook:
jupyter notebook NIH_Chest_X_ray.ipynb


 Dataset Info:

The dataset used in this project can be found here:
NIH Chest X-ray Dataset on HuggingFace - https://huggingface.co/datasets/alkzar90/NIH-Chest-X-ray-dataset/tree/main

It includes over 112,000 X-ray images labeled with 14 disease classes including pneumonia, fibrosis, edema, and more.

License:
This project is intended for academic and research purposes only.
