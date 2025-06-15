# 🧠 Riemannian Neural Network for Multiclass Motor Imagery EEG Classification

This repository provides the implementation of our multiclass classification framework for motor imagery (MI) EEG data, combining Riemannian geometry with neural networks.

## 🔍 Overview

In motor imagery-based BCI tasks, spatial covariance matrices (SCMs) of EEG signals are symmetric positive definite (SPD) and lie on a Riemannian manifold. This project proposes a multibranch neural network architecture that efficiently extracts discriminative features from SCMs.

### ✨ Key Features

- **Multibranch Riemannian Module**: Parallel processing of SCMs on the SPD manifold.
- **Fusion Loss Mechanism**: Selectively updates the corresponding branch for the true label while incorporating auxiliary losses.
- **End-to-End Architecture**: Joint Riemannian feature extraction and classification.

The model has been validated on four public MI EEG datasets, demonstrating strong performance and training efficiency.

---

## 📄 Citation

If you find this work helpful, please cite:

```bibtex
@article{shi2024multiclass,
  title={Multiclass Classification Framework of Motor Imagery EEG by Riemannian Geometry Networks},
  author={Shi, Yuxuan and Jiang, Aimin and Zhong, Ju and Li, Min and Zhu, Yanping},
  journal={IEEE Journal of Biomedical and Health Informatics},
  year={2024},
  publisher={IEEE}
}
