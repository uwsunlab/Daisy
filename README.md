# 🔬🧪 DAISY

Vision intelligence assists microstructural optimization of lead-free perovskite semiconductors.

## 📌 Overview

This repository contains all the code developed for the Daisy project. It includes image classification, segmentation models, clustering models, and optimization algorithms, along with support, visualization, and pre-processing code. The goal is to provide structured and reusable code for research and development.

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

## 🚀 Features & Usage

All the code provided was run on Google Colab.
### 📂 Data Preprocessing

- **Preprocessing & Patch-Based Processing for Classification** (`DAISY_Pre-Process.ipynb`, `Daisy_Patch_creator.ipynb`)
  - Prepares images for analysis and breaks SEM images into smaller patches to aid classification models.
  
### 📂 Image Interpreter
#### Classification
- **Image Classification & Feature Extraction** (`Daisy_VGG16.ipynb`)
  - Uses VGG16 architecture to classify and extract features from SEM images.

#### Image Segment & Clustering
- **Segmentation & Clustering** (`DAISY_SINGLE_IMAGE_SEGMENT_AND_DATA_EXTRACTION.ipynb`)
  - Performs segmentation and clustering while extracting defect and grain size information.


### 📂 Synthesis Planner

#### Reinforcement Learning
- **Reinforcement Learning for Parameter Optimization** (`DAISY_RL.ipynb`)
  - Implements reinforcement learning to optimize experimental parameters.
#### PCA Data Space
- **Principal Component Analysis (PCA) for Data Visualization** (`DAISY_PCA.ipynb`)
  - Applies PCA for parameter space visualization and dimensionality reduction.
  - 
### 📂 Additional Modules

- **Bayesian Optimization for Process Optimization** (`DAISY_BAYESIAN_OPTIMIZATION.ipynb`)
  - Tests Bayesian optimization models to identify optimal parameter combinations.
- **Alternative Model Architectures for Image Classification** (`Daisy_Mobile.ipynb`, `Daisy_ResNet50.ipynb`)
  - Provides alternative deep learning models for classification.
- **Eandom forest Regression for Process Optimization** (`DAISY_OPTIMIZATION.ipynb`)
  - Tests Random Forest Regression model and extracts feature importnaces to identify optimal parameter combinations.
  
### 📂 Image Support Data

- **Data Files for Processing and Analysis** (`Image_support_data` folder)
  - Contains essential CSV files (`Pixel_to_um_scale.csv`, `Synthesis_parameters.csv`, `Unique_synthesis_parameters.csv`) for data processing.

## 📂 Repository Structure
```plaintext
📦 your-repo-name
 ┣ 📂 Image_support_data     # Data files related to image processing
 ┃ ┣ 📜 Pixel_to_um_scale.csv
 ┃ ┣ 📜 Synthesis_parameters.csv
 ┃ ┣ 📜 Unique_synthesis_parameters.csv
 ┣ 📂 src                   # Source code for various models and analysis
 ┃ ┣ 📂 Image Interpreter
 ┃ ┃ ┣ 📂 Image_segment_cluster
 ┃ ┃ ┃ ┣ 📜 DAISY_SINGLE_IMAGE_SEGMENT_AND_DATA_EXTRACTION.ipynb
 ┃ ┃ ┣ 📂 classification
 ┃ ┃ ┃ ┣ 📜 Daisy_VGG16.ipynb
 ┃ ┣ 📂 Synthesis Planner
 ┃ ┃ ┣ 📂 PCA_data_space
 ┃ ┃ ┃ ┣ 📜 DAISY_PCA.ipynb
 ┃ ┃ ┣ 📂 Reinforcement_Learning
 ┃ ┃ ┃ ┣ 📜 DAISY_RL.ipynb
 ┃ ┣ 📂 additional
 ┃ ┃ ┣ 📜 DAISY_BAYESIAN_OPTIMIZATION.ipynb
 ┃ ┃ ┣ 📜 Daisy_Mobile.ipynb
 ┃ ┃ ┣ 📜 Daisy_ResNet50.ipynb
 ┃ ┃ ┣ 📜 Daisy_RF.ipynb
 ┃ ┣ 📂 data_Preprocessing
 ┃ ┃ ┣ 📜 DAISY_Pre-Process.ipynb
 ┃ ┃ ┣ 📜 Daisy_Patch_creator.ipynb
 ┣ 📜 README.md              # This README file
 ┣ 📜 requirements.txt
```

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


