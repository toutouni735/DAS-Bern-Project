# DAS-Bern-Project

## Deep Learning-Based Cell Segmentation for Cellular Analysis

This repository contains the code used for the DAS project poster on fluorescence microscopy image segmentation using Cellpose.

### Contents

- `01_finetuning_cellpose.ipynb`: fine-tuning of the Cellpose model using manually corrected masks
- `02_metrics_evaluation.ipynb`: computation of IoU, Dice, Precision, Recall, F1-score, and nuclei count
- `03_plots_and_figures.ipynb`: generation of the figures used in the poster

### Dataset

The dataset consists of fluorescence microscopy images of Hoechst-stained nuclei with manually corrected segmentation masks generated in napari.

### Software

- Python 3.11
- Cellpose 4.0.5
- PyTorch 2.10.0+cu128
- scikit-image
- matplotlib
- pandas
- numpy
