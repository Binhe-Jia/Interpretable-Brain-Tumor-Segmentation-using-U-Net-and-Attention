# Interpretable Brain Tumor Segmentation using U-Net and Attention

This project explores interpretable brain tumor segmentation using U-Net architectures, Grad-CAM visualization, and metadata-driven extensions. Built on the LGG MRI dataset, it aims to support surgical data science with interpretable tools.

---

## Project Goals

- Accurate tumor segmentation from MRI slices
- Model interpretability via Grad-CAM
- Uncertainty modeling with MC Dropout
- Metadata integration for weak supervision

---

## Project Structure

```
brain_tumor_segmentation_project/
├── notebooks/                      # Jupyter Notebooks for each module
│   ├── 1_preprocessing.ipynb
│   ├── 2_train_unet.ipynb
│   ├── 3_gradcam_visualization.ipynb
│   ├── 4_attention_unet.ipynb
│   ├── 5_uncertainty_estimation.ipynb
│   └── 6_metadata_integration.ipynb
└── README.md
```


## Dataset

- [LGG MRI Segmentation Dataset (Kaggle)](https://www.kaggle.com/datasets/mateuszbuda/lgg-mri-segmentation)
- ~110 patient scans in `.tif` format with tumor masks

---
Note: the project structure is subjected to future modification


## Installation

```bash
# Option 1: pip
pip install -r requirements.txt

# Option 2: conda
conda env create -f environment.yml
conda activate brain-tumor-env
```

---

## Future Work

- 3D segmentation models (V-Net / nnUNet)
- Multi-omics integration (e.g., TCGA)
- CLAM-based weakly supervised learning
- Hugging Face / Streamlit deployment

---
