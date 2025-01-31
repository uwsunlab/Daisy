# 🔬🧪 DAISY

Vision intelligence assists microstructural optimization of lead-free perovskite semiconductors.

## 📌 Overview

This repository contains all the code developed for the Daisy project. It includes image classification, segmentation models, clustering models, and optimization algorithms, along with support, visualization, and pre-processing code. The goal is to provide structured and reusable code for research and development.

## 🚀 Features

- **Segmentation**
- **Clustering**
- **Grain Size and Defect Percentage Extraction**
- **Deep Learning Architectures:** Implementation of **ResNet50, VGG16, and MobileNet** for classification.
- **Reinforcement Learning (RL):** Q-learning-based **parameter optimization** to optimize synthesis conditions.
- **Principal Component Analysis (PCA):** Dimensionality reduction for parameter space visualization.
- **Bayesian Optimization**
- **Patch-Based Image Processing:** Patch creation for training classification.
- **Data Visualization:** Custom visualizations using **Altair and Matplotlib** to analyze results effectively.

## 🛠 Installation

1. Clone this repository:
   ```sh
   git clone https://github.com/your-username/your-repo-name.git
   cd your-repo-name
   ```
2. Install dependencies:
   ```sh
   pip install -r requirements.txt
   ```

## 📂 Repository Structure

```plaintext
📦 your-repo-name
 ┣ 📂 Image_support_data     # Data files related to image processing
 ┃ ┣ 📜 Pixel_to_um_scale.csv
 ┃ ┣ 📜 Synthesis_parameters.csv
 ┃ ┣ 📜 Unique_synthesis_parameters.csv
 ┣ 📂 src                   # Source code for various models and analysis
 ┃ ┣ 📜 DAISY_OPTIMIZATION.ipynb
 ┃ ┣ 📜 DAISY_PCA.ipynb
 ┃ ┣ 📜 DAISY_Pre-Process.ipynb
 ┃ ┣ 📜 DAISY_RL.ipynb
 ┃ ┣ 📜 DAISY_SINGLE_IMAGE_SEGMENT_AND_DATA_EXTRACTION.ipynb
 ┃ ┣ 📜 Daisy_Mobile.ipynb
 ┃ ┣ 📜 Daisy_Patch_creator.ipynb
 ┃ ┣ 📜 Daisy_ResNet50.ipynb
 ┃ ┣ 📜 Daisy_VGG16.ipynb
 ┣ 📜 README.md              # This README file
 ┣ 📜 requirements.txt
```

## 📖 Usage

All the code provided was run on Google Colab.

- **Grain Size and Defect Percentage Extraction using Segmentation & Clustering:** `DAISY_SINGLE_IMAGE_SEGMENT_AND_DATA_EXTRACTION.ipynb` performs single-image segmentation and clustering while extracting defect and grain size information. 
- **Image Classification & Feature Extraction:** Use `Daisy_VGG16.ipynb`, `Daisy_ResNet50.ipynb`, and `Daisy_Mobile.ipynb` to classify and extract features from SEM images.
- **Reinforcement Learning for Parameter Optimization:** `DAISY_RL.ipynb` implements reinforcement learning to optimize experimental parameters.
- **Bayesian Optimization:** `DAISY_OPTIMIZATION.ipynb` tests a Bayesian optimization model for optimal parameter combinations.
- **Patch-Based Processing for Classification:** `Daisy_Patch_creator.ipynb` breaks SEM images into smaller patches to aid classification models.
- **Data Processing & Visualization:** The `Image_support_data` folder contains essential CSV files for data processing, assisting in running the other codes. `DAISY_PCA.ipynb` applies PCA for parameter space visualization.

## 🏗 Contributing

Contributions are welcome! Feel free to:

- Open an issue for any bug reports or feature requests.
- Submit pull requests with improvements or additional functionalities.
- Suggest optimizations for existing workflows.
- Ensure that any proposed models or modifications follow best practices and include sufficient experimental validation.
- Clearly document any new features or optimizations, providing appropriate benchmarking where applicable.

## 📬 Contact

For questions, discussions, or collaborations, feel free to reach out:

- **GitHub Issues**: Open an issue in the repository.
- **Email**: [ks121200@uw.edu](mailto:ks121200@uw.edu), [shuan19@uw.edu](mailto:shuan19@uw.edu), [shijing@uw.edu](mailto:shijing@uw.edu)

---

🚀 **Happy Coding!** 🎯

