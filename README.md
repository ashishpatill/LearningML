# LearningML

> A structured collection of Jupyter notebooks documenting a hands-on ML journey — from Python basics to deep learning, reinforcement learning, and generative models.

![Language](https://img.shields.io/badge/language-Jupyter%20Notebook-orange)
![License](https://img.shields.io/badge/license-GPL--3.0-blue)

---

## Contents

### 1. Python & PyTorch Foundations
| Notebook | Description |
|---|---|
| `1_Revisiting_Python_Basics.ipynb` | Core Python concepts — data structures, functions, OOP |
| `2_Revisiting_tensors_in_Pytorch.ipynb` | Tensor operations, shapes, broadcasting in PyTorch |
| `3_Revisiting_Basics_of_Pytorch_for_DL.ipynb` | PyTorch autograd, nn.Module, training loop fundamentals |

### 2. Classical Machine Learning
| Notebook | Description |
|---|---|
| `ML_Learning_Types.ipynb` | Overview of supervised, unsupervised, and reinforcement learning |
| `data_preprocessing,_Linear_regression,_SVM.ipynb` | Data preprocessing pipelines, Linear Regression, SVM |
| `PCA.ipynb` | Principal Component Analysis for dimensionality reduction |
| `decision_tree_from_scratch.ipynb` | Decision Tree implementation from scratch |
| `Boosting_Regressor.ipynb` | Gradient Boosting for regression tasks |
| `adaboost_classifier.ipynb` | AdaBoost classifier implementation |
| `rf_imbalance_challenge.ipynb` | Random Forest with imbalanced datasets |
| `feature_importance.ipynb` | Feature importance analysis and selection techniques |
| `hyper_tuning.ipynb` | Hyperparameter tuning (GridSearch, RandomSearch) |
| `Pima_Indian_Diabetes.ipynb` | End-to-end classification on the Pima Indian Diabetes dataset |
| `Cars.ipynb` | Regression/classification on car dataset |

### 3. Optimization
| Notebook | Description |
|---|---|
| `ODS_Newton's_method_and_steepest_descent.ipynb` | Newton's method and gradient descent optimization |

### 4. Deep Learning
| Notebook | Description |
|---|---|
| `4_Classification_and_Feature_Extraction_using_CNN.ipynb` | CNNs for image classification and feature extraction |
| `5_Transfer_Learning.ipynb` | Transfer learning with pretrained CNN models |
| `6_Datasets_and_DataLoaders.ipynb` | PyTorch Dataset and DataLoader utilities |
| `7_Custom_Datasets_and_Dataloaders.ipynb` | Building custom Dataset classes for any data format |
| `GPU_Assignment_(Random_Forest).ipynb` | GPU-accelerated Random Forest experiments |

### 5. Generative Models & Autoencoders
| Notebook | Description |
|---|---|
| `3b_generative_models.ipynb` | Introduction to generative modeling concepts |
| `Sparse,_Contractive,_and_Variational_Auto_Encoders.ipynb` | Sparse AE, Contractive AE, and VAE implementations |

### 6. Reinforcement Learning
| Notebook | Description |
|---|---|
| `Goal_Based_Agent_for_Warehouse.ipynb` | Goal-based agent navigating a warehouse environment |
| `Grid_world_Q_star.ipynb` | Q-learning / Q* on a GridWorld environment |

---

## Getting Started

### Prerequisites

- Python 3.8+
- PyTorch
- scikit-learn
- NumPy, Pandas, Matplotlib
- Jupyter Notebook / JupyterLab

### Installation

```bash
git clone https://github.com/ashishpatill/LearningML.git
cd LearningML
pip install torch torchvision scikit-learn numpy pandas matplotlib jupyterlab
jupyter lab
```

---

## License

Distributed under the [GPL-3.0 License](LICENSE).
