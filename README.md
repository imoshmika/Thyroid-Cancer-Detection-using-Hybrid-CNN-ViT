# Thyroid Cancer Detection using Hybrid CNN-ViT

<p align="center">

**Hybrid Convolutional Neural Network and Vision Transformer Framework for Automated Thyroid Cancer Detection**

[![Python](https://img.shields.io/badge/Python-3.9%2B-blue.svg)](https://www.python.org/)
[![PyTorch](https://img.shields.io/badge/PyTorch-Deep%20Learning-ee4c2c.svg)](https://pytorch.org/)
[![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange.svg)](https://jupyter.org/)
[![Computer Vision](https://img.shields.io/badge/Computer%20Vision-Medical%20Imaging-green.svg)](https://github.com/imoshmika/Thyroid-Cancer-Detection-using-Hybrid-CNN-ViT)
[![Research](https://img.shields.io/badge/Research-Medical%20AI-purple.svg)](https://github.com/imoshmika/Thyroid-Cancer-Detection-using-Hybrid-CNN-ViT)

</p>

---

## 📌 Overview

Thyroid cancer detection from medical images is an important application of artificial intelligence in medical image analysis. Conventional image-classification approaches can effectively learn local visual patterns, while Transformer-based architectures provide mechanisms for capturing broader contextual relationships within an image.

This repository presents a **Hybrid CNN-ViT (Convolutional Neural Network–Vision Transformer) approach for thyroid cancer detection**.

The proposed framework combines the complementary capabilities of:

* **Convolutional Neural Networks (CNNs)** for learning local spatial and morphological features.
* **Vision Transformers (ViTs)** for modeling long-range dependencies and global contextual relationships.

The implementation is provided as a Jupyter Notebook:

```text
Thyroid Cancer Detection using Hybrid CNN-ViT.ipynb
```

The repository is intended for research and educational purposes in:

* Medical Image Analysis
* Deep Learning
* Computer Vision
* Thyroid Cancer Detection
* Medical Artificial Intelligence
* CNN Architectures
* Vision Transformers
* Computer-Aided Diagnosis

> **Important:** This repository represents a research implementation and is **not a clinically validated diagnostic system**. Model predictions must not be used as a substitute for diagnosis by qualified medical professionals.

---

## 🎯 Research Objective

The main objective of this project is to investigate a hybrid deep learning architecture that combines CNN-based local feature extraction with Vision Transformer-based global feature modeling for automated thyroid cancer identification.

### Primary objectives

1. Develop an automated thyroid cancer image-classification framework.
2. Extract discriminative local features using convolutional operations.
3. Model global spatial relationships using Vision Transformer mechanisms.
4. Combine local and global representations.
5. Train an end-to-end classification framework.
6. Evaluate classification performance using multiple metrics.
7. Investigate the suitability of hybrid CNN-Transformer architectures for medical image analysis.

---

## 🧠 Why Hybrid CNN + Vision Transformer?

CNNs and Vision Transformers provide complementary capabilities.

### CNN

CNNs are particularly effective at learning:

* Local edges
* Textures
* Shapes
* Cellular structures
* Morphological patterns
* Local spatial relationships

### Vision Transformer

Vision Transformers can model:

* Long-range dependencies
* Global image context
* Relationships between distant image regions
* High-level contextual representations

### Hybrid approach

The hybrid CNN-ViT architecture aims to exploit both representations:

```text
                    Input Image
                         │
                         ▼
              ┌──────────────────────┐
              │ CNN Feature Extractor│
              └──────────────────────┘
                         │
                         ▼
                 Local Features
                         │
                         ▼
              Feature Representation
                         │
                         ▼
              ┌─────────────────────┐
              │ Vision Transformer  │
              │       (ViT)         │
              └─────────────────────┘
                         │
                         ▼
                 Global Features
                         │
                         ▼
              Feature Integration
                         │
                         ▼
                 Classification
                         │
                         ▼
             Thyroid Cancer Prediction
```

The central idea is to combine **fine-grained local information** learned by CNN layers with **global contextual information** learned by Transformer attention mechanisms.

---

## 🔬 Proposed Hybrid Architecture

The overall conceptual architecture is:

```text
Input Thyroid Image
        │
        ▼
Image Preprocessing
        │
        ▼
Image Resizing / Normalization
        │
        ▼
CNN Feature Extraction
        │
        ├──────────────► Local Spatial Features
        │
        ▼
Feature Transformation
        │
        ▼
Patch / Token Representation
        │
        ▼
Vision Transformer
        │
        ├──────────────► Global Contextual Features
        │
        ▼
Feature Representation
        │
        ▼
Classification Head
        │
        ▼
Thyroid Cancer Class
```

The exact implementation details, layer configuration, training procedure, and experimental settings are available in the accompanying notebook.

---

## 📓 Main Research Notebook

The principal implementation is:

```text
Thyroid Cancer Detection using Hybrid CNN-ViT.ipynb
```

The notebook contains the experimental workflow for the proposed hybrid CNN-ViT approach.

### Notebook workflow

```text
1. Environment setup
2. Library import
3. Dataset configuration
4. Image loading
5. Data preprocessing
6. Dataset preparation
7. CNN feature extraction
8. Transformer-based representation learning
9. Hybrid feature processing
10. Model training
11. Model validation
12. Model evaluation
13. Performance analysis
```

---

## 🗂️ Repository Structure

```text
Thyroid-Cancer-Detection-using-Hybrid-CNN-ViT/
│
├── Thyroid Cancer Detection using Hybrid CNN-ViT.ipynb
│
├── Outputs/
│   ├── figures/
│   ├── confusion_matrix/
│   └── results/
│
├── README.md
│
├── requirements.txt
│
└── LICENSE
```

> The current repository primarily contains the research notebook. The additional directories above are recommended for a complete reproducible research release.

---

## ⚙️ Technologies Used

The project uses the Python deep learning ecosystem.

### Core technologies

* Python
* PyTorch
* Torchvision
* NumPy
* Pandas
* Scikit-learn
* Matplotlib
* Pillow
* Jupyter Notebook

Additional libraries may be required depending on the final notebook configuration.

---

## 💻 Requirements

Recommended environment:

```text
Python >= 3.9
PyTorch
Torchvision
NumPy
Pandas
Scikit-learn
Matplotlib
Pillow
Jupyter
```

A CUDA-compatible NVIDIA GPU is recommended for faster model training.

---

## 🚀 Installation

### 1. Clone the repository

```bash
git clone https://github.com/imoshmika/Thyroid-Cancer-Detection-using-Hybrid-CNN-ViT.git
```

### 2. Navigate to the repository

```bash
cd Thyroid-Cancer-Detection-using-Hybrid-CNN-ViT
```

### 3. Create a virtual environment

```bash
python -m venv venv
```

### Windows

```bash
venv\Scripts\activate
```

### Linux/macOS

```bash
source venv/bin/activate
```

### 4. Install dependencies

```bash
pip install numpy pandas matplotlib scikit-learn pillow jupyter
```

Install PyTorch according to your hardware and CUDA configuration:

```bash
pip install torch torchvision
```

For reproducibility, the final project should provide a pinned `requirements.txt`.

---

## 📓 Running the Notebook

Launch Jupyter Notebook:

```bash
jupyter notebook
```

or:

```bash
jupyter lab
```

Open:

```text
Thyroid Cancer Detection using Hybrid CNN-ViT.ipynb
```

Execute the notebook cells sequentially.

### Recommended execution order

```text
Environment Setup
        ↓
Import Libraries
        ↓
Configure Dataset
        ↓
Load Images
        ↓
Preprocess Images
        ↓
Create Dataset/DataLoader
        ↓
Initialize CNN
        ↓
Generate CNN Features
        ↓
Prepare Transformer Input
        ↓
Vision Transformer Processing
        ↓
Hybrid Representation
        ↓
Classification
        ↓
Training
        ↓
Validation
        ↓
Testing
        ↓
Performance Evaluation
```

---

## 🧬 Dataset

The thyroid cancer dataset used by the experiments should be obtained from its original authorized source.

Medical datasets may have specific:

* Licensing requirements
* Academic-use restrictions
* Redistribution restrictions
* Patient privacy requirements
* Institutional requirements

Therefore, datasets are not included in this repository unless their licenses explicitly permit redistribution.

Configure the dataset path in the notebook according to the local environment.

Example:

```python
DATASET_PATH = "/path/to/thyroid/dataset"
```

### Recommended dataset organization

```text
dataset/
│
├── train/
│   ├── class_1/
│   └── class_2/
│
├── validation/
│   ├── class_1/
│   └── class_2/
│
└── test/
    ├── class_1/
    └── class_2/
```

Replace the class names with the actual labels used by the dataset.

---

## 🔬 Image Preprocessing

Medical images often exhibit variations in:

* Image dimensions
* Illumination
* Contrast
* Acquisition conditions
* Image quality
* Background characteristics

A preprocessing pipeline may therefore include:

```text
Input Image
    │
    ▼
Image Resizing
    │
    ▼
Normalization
    │
    ▼
Data Augmentation
    │
    ▼
Model Input
```

The exact preprocessing configuration should match the final experimental notebook to ensure reproducibility.

---

## 🧠 CNN Feature Learning

The CNN component is responsible for extracting local visual representations.

CNN layers progressively learn hierarchical features:

```text
Low-Level Features
      │
      ├── Edges
      ├── Corners
      └── Textures
             │
             ▼
Intermediate Features
      │
      ├── Shapes
      ├── Structures
      └── Patterns
             │
             ▼
High-Level Features
      │
      └── Diagnostic Visual Representation
```

These learned features provide the input representation for the subsequent Transformer component.

---

## 🤖 Vision Transformer

The Vision Transformer component provides global contextual modeling.

Conceptually:

```text
CNN Features
      │
      ▼
Feature Tokens
      │
      ▼
Token Embedding
      │
      ▼
Transformer Encoder
      │
      ├── Multi-Head Self-Attention
      │
      ├── Feed-Forward Network
      │
      └── Residual Connections
      │
      ▼
Global Representation
```

Self-attention allows the model to learn relationships between different regions of the image representation.

---

## 🔗 Hybrid Feature Representation

The central concept of the proposed approach is the integration of CNN and Transformer representations.

```text
                    ┌───────────────┐
                    │    Image      │
                    └───────┬───────┘
                            │
             ┌──────────────┴──────────────┐
             │                             │
             ▼                             ▼
      CNN Representation          Transformer Representation
             │                             │
             ▼                             ▼
       Local Features                 Global Features
             │                             │
             └──────────────┬──────────────┘
                            │
                            ▼
                  Hybrid Representation
                            │
                            ▼
                    Classification
```

This design aims to preserve complementary information from both architectural families.

---

## 📊 Evaluation

The proposed framework is evaluated using complementary **classification and segmentation metrics** to provide a comprehensive assessment of its performance on the test dataset.

### Classification Metrics

#### Accuracy

Measures the proportion of correctly classified samples.

Accuracy = (TP + TN) / (TP + TN + FP + FN)

#### Precision

Measures the proportion of predicted positive samples that are actually positive.

Precision = TP / (TP + FP)

#### Recall / Sensitivity

Measures the proportion of actual positive samples correctly identified.

Recall = TP / (TP + FN)

#### Specificity

Measures the proportion of actual negative samples correctly identified.

Specificity = TN / (TN + FP)

#### F1-Score

Provides the harmonic mean of precision and recall.

F1-Score = 2 × (Precision × Recall) / (Precision + Recall)

#### Matthews Correlation Coefficient (MCC)

MCC provides a balanced measure of binary classification performance, particularly useful when the classes are imbalanced.

MCC = (TP × TN − FP × FN) / √[(TP + FP)(TP + FN)(TN + FP)(TN + FN)]

#### ROC-AUC

The Area Under the Receiver Operating Characteristic Curve (ROC-AUC) measures the model's ability to distinguish between the target classes across different classification thresholds.

#### PR-AUC

The Area Under the Precision-Recall Curve (PR-AUC) evaluates the trade-off between precision and recall and is particularly informative when class distributions are imbalanced.

---

### Segmentation Metrics

For segmentation evaluation, the proposed framework is assessed using **Dice Similarity Coefficient (Dice), Intersection over Union (IoU), and Hausdorff Distance**.

#### Dice Similarity Coefficient

Dice measures the overlap between the predicted segmentation and the ground-truth segmentation.

Dice = 2 × |Prediction ∩ Ground Truth| / (|Prediction| + |Ground Truth|)

where (P) represents the predicted segmentation and (G) represents the ground-truth segmentation.

#### Intersection over Union (IoU)

IoU measures the ratio between the intersection and union of the predicted and ground-truth regions.

IoU = |Prediction ∩ Ground Truth| / |Prediction ∪ Ground Truth|

#### Hausdorff Distance

Hausdorff Distance measures the maximum boundary discrepancy between the predicted and ground-truth segmentation regions.

Lower Hausdorff Distance values indicate closer boundary agreement.

Hausdorff Distance = max{d(P, G), d(G, P)}

---

## 📈 Experimental Results

The final model was evaluated on the **held-out test set** using both classification and segmentation metrics.

### Classification Performance

| Metric                   | Test Performance |
| ------------------------ | ---------------: |
| Accuracy                 |           93.20% |
| Precision                |           91.72% |
| Recall / Sensitivity     |           90.80% |
| F1-Score                 |           89.80% |
| MCC                      |           0.7031 |
| ROC-AUC                  |           0.9262 |
| PR-AUC                   |           0.9082 |

The model achieves **93.20% test accuracy**, with a **ROC-AUC of 0.9262** and **PR-AUC of 0.9082**, indicating strong discriminative capability on the held-out test data. The MCC of **0.7031** further indicates a substantial positive correlation between the predicted and true class labels.

---

### Segmentation Performance

| Metric                          | Test Performance |
| ------------------------------- | ---------------: |
| Dice Similarity Coefficient     |           93.38% |
| IoU                             |           87.59% |
| Hausdorff Distance              |        8475.0000 |

The segmentation results demonstrate a **Dice score of 93.38%** and an **IoU of 87.59%**, indicating substantial spatial overlap between the predicted and ground-truth regions.

The reported Hausdorff Distance is **8475.0000**. Because Hausdorff Distance is highly dependent on the image coordinate system, pixel spacing, image dimensions, and whether preprocessing/rescaling is applied, this value should be interpreted together with the corresponding implementation and spatial units.

> **Note:** The values reported above correspond to the test-set evaluation provided for the current implementation. They should be reproduced by executing the final notebook with the same dataset split and experimental configuration.


---


## 🔁 Reproducibility

For reproducible experiments, maintain consistent:

* Dataset version
* Dataset split
* Random seed
* Image size
* Normalization
* Data augmentation
* CNN architecture
* Transformer configuration
* Learning rate
* Optimizer
* Batch size
* Number of epochs
* Scheduler
* Loss function
* Hardware
* Software versions

A recommended configuration file is:

```text
configs/config.yaml
```

Example:

```yaml
seed: 42
batch_size: 16
learning_rate: 0.0001
epochs: 50
image_size: 224
```

The values above are examples only and should be replaced with the actual experimental configuration.

---

## 🧪 Experimental Protocol

For reliable medical-image evaluation, the experimental protocol should avoid data leakage.

Recommended practice:

```text
Patient-Level Dataset
        │
        ├──────── Train
        │
        ├──────── Validation
        │
        └──────── Test
```

Where multiple images originate from the same patient, images from an individual patient should not be distributed across training and test sets unless the experimental design explicitly requires and justifies such a setup.

This is particularly important for medical imaging research because image-level splitting can lead to overly optimistic estimates of generalization performance.

---

## 🩺 Clinical Disclaimer

This repository is intended **only for research and educational purposes**.

The proposed model:

* Is not a certified medical device.
* Has not been established as a clinical diagnostic system.
* Should not be used for patient diagnosis.
* Should not be used to determine treatment.
* Should not replace a qualified physician or pathologist.
* May fail on images from different acquisition environments or patient populations.

Clinical application would require extensive external validation, prospective studies, regulatory approval, appropriate clinical governance, and expert oversight.

---

## 🔐 Privacy and Ethical Considerations

When working with medical images:

* Remove personally identifiable information.
* Follow institutional data-governance requirements.
* Follow applicable privacy regulations.
* Respect dataset licensing.
* Do not redistribute restricted patient data.
* Obtain appropriate institutional approval where required.

---

## ⚠️ Limitations

Potential limitations of the approach include:

1. Dataset-specific performance.
2. Limited representation of diverse patient populations.
3. Variability between imaging devices and acquisition protocols.
4. Potential class imbalance.
5. Domain shift between institutions.
6. Dependence on image quality.
7. Computational requirements of Transformer-based architectures.
8. Potential overfitting when training data are limited.
9. Need for independent external validation.

High performance on a single dataset should therefore not automatically be interpreted as clinical generalization.

---

## 🔮 Future Work

Potential extensions of this work include:

* Multi-center validation
* External dataset evaluation
* Patient-level classification
* Explainable AI
* Attention-map visualization
* Model calibration
* Uncertainty estimation
* Robustness testing
* Cross-domain evaluation
* Stain/intensity normalization where appropriate
* CNN-only and ViT-only comparative experiments
* Extensive ablation studies
* Statistical significance testing
* Lightweight model development
* Deployment as a research-oriented clinical decision-support prototype

---

## 📚 Research Applications

The proposed framework can contribute to research in:

```text
Artificial Intelligence
        │
        ▼
Deep Learning
        │
        ▼
Computer Vision
        │
        ▼
Medical Image Analysis
        │
        ▼
Thyroid Imaging
        │
        ▼
Cancer Detection
        │
        ▼
Computer-Aided Diagnosis
```

---



## 🤝 Contributions

Research-oriented contributions are welcome.

If you find an issue:

1. Open a GitHub Issue.
2. Clearly describe the problem.
3. Include the relevant error message.
4. Specify the environment and software versions.
5. Provide reproducible steps where possible.

For substantial improvements, submit a pull request with a clear description of the proposed change.

---



## 👨‍🔬 Research Area

**Artificial Intelligence → Deep Learning → CNN → Vision Transformer → Medical Image Analysis → Thyroid Cancer Detection → Computer-Aided Diagnosis**

---

<p align="center">

**Developed for research in AI-assisted thyroid cancer image analysis.**

</p>
