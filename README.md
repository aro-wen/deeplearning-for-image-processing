# 🖼️ Deep Learning for Image Processing

<div align="center">

![Python](https://img.shields.io/badge/Python-3.10+-blue?style=for-the-badge\&logo=python)
![OpenCV](https://img.shields.io/badge/OpenCV-Computer_Vision-green?style=for-the-badge\&logo=opencv)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange?style=for-the-badge\&logo=jupyter)
![scikit-image](https://img.shields.io/badge/scikit--image-Image_Processing-yellow?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Active-success?style=for-the-badge)

**Exploring Classical Feature Detection and Image Processing Techniques using Python, OpenCV, and scikit-image**

</div>

---

## 📖 Overview

This repository serves as a hands-on exploration of traditional computer vision and image processing algorithms that laid the foundation for modern deep learning systems.

The project demonstrates and compares several widely used feature extraction and keypoint detection techniques through interactive Jupyter Notebooks.

### 🔍 Techniques Covered

| Algorithm                             | Purpose                                 |
| ------------------------------------- | --------------------------------------- |
| Haar Features                         | Object detection and feature extraction |
| HOG (Histogram of Oriented Gradients) | Shape and object recognition            |
| LBP (Local Binary Patterns)           | Texture analysis                        |
| SIFT                                  | Scale-invariant feature detection       |
| SURF                                  | Speeded-up robust feature detection     |
| FAST                                  | High-speed corner detection             |
| ORB                                   | Efficient feature matching and tracking |

---

## 🏗️ Project Structure

```text
deeplearning-for-image-processing/
│
├── notebooks/              # Jupyter notebooks
├── images/                 # Sample images and datasets
├── requirements.txt        # Project dependencies
├── .gitignore
└── README.md
```

---

## 🚀 Quick Start

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/aro-wen/deeplearning-for-image-processing.git
cd deeplearning-for-image-processing
```

---

### 2️⃣ Create a Virtual Environment

#### Windows

```bash
python -m venv venv
venv\Scripts\activate
```

#### macOS / Linux

```bash
python3 -m venv venv
source venv/bin/activate
```

---

### 3️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```

---

### 4️⃣ Launch Jupyter Notebook

```bash
jupyter notebook
```

or

```bash
jupyter lab
```

Open the desired notebook and run the cells sequentially.

---

## ⚙️ Prerequisites

Before running the project, ensure you have the following installed:

* Python 3.10+
* Git
* Visual Studio Code (recommended)
* Jupyter Notebook or JupyterLab
* Internet connection (for package installation)

---

## 🛠️ Recommended VS Code Extensions

To enhance your development experience, install:

| Extension | Publisher |
| --------- | --------- |
| Python    | Microsoft |
| Jupyter   | Microsoft |
| Pylance   | Microsoft |

Open the Extensions Marketplace using:

```text
Ctrl + Shift + X
```

and install the required extensions.

---

## 📦 Core Libraries

This project leverages the following Python libraries:

```text
opencv-python
numpy
matplotlib
scikit-image
jupyter
```

Install all dependencies with:

```bash
pip install -r requirements.txt
```

---

## 🎯 Learning Objectives

Through this project, you will:

* Understand classical computer vision techniques
* Explore feature extraction methods
* Compare detector performance and characteristics
* Visualize image transformations and keypoints
* Build a strong foundation before studying deep learning-based vision models

---

## 📸 Sample Outputs

Add screenshots of:

* SIFT Keypoint Detection
* ORB Feature Matching
* HOG Visualization
* LBP Texture Analysis
* FAST Corner Detection

Example:

```markdown
![SIFT Example](docs/images/sift-output.png)
```

---

## 🧹 .gitignore

Recommended entries:

```gitignore
venv/
__pycache__/
.ipynb_checkpoints/
*.pyc
.DS_Store
```

---

## 📚 References

* OpenCV Documentation
* scikit-image Documentation
* Computer Vision: Algorithms and Applications
* Feature Detection and Description Research Papers

---

## 👨‍💻 Author

**Leila Arowen A. Dumindin**

GitHub: https://github.com/aro-wen

---

<div align="center">

### ⭐ If you found this project useful, consider giving it a star!

Built with Python, OpenCV, and curiosity.

</div>
