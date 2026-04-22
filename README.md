# DP-GB: Differentially Private Granular Ball Classification with Laplace and Exponential Mechanisms 

This repository provides the implementation and experimental code for the paper:

**“DP-GB: Differentially Private Granular Ball Classification with Laplace and Exponential Mechanisms .”**

---

## 📌 Overview

This work proposes **DP-GB**, a differentially private classification framework based on granular ball computing. The method incorporates:

* Laplace mechanism for private center estimation
* Exponential mechanism for radius selection
* Extension to multi-ball hierarchical construction

The approach is evaluated on multiple tabular and image datasets and compared with standard differentially private baselines.

---

## 🚀 Code

All experiments are implemented in a Jupyter/Google Colab notebook:

* `dp_gb_experiments.ipynb`

The notebook includes:

* Data loading and preprocessing
* Implementation of DP-GB (one-ball and multi-ball)
* Baseline comparisons
* Experimental evaluation and visualization

---

## ▶️ How to Run

1. Open the notebook in:

   * Jupyter Notebook, or
   * Google Colab

2. Install required dependencies:

   ```bash
   pip install -r requirements.txt
   ```

3. Run all cells sequentially to reproduce results.

---

## 📊 Reproducibility

* Random seeds are fixed for reproducibility
* All experiments can be reproduced by executing the notebook from top to bottom

---

## 📝 Code Availability

The code used to generate the experimental results in the paper is publicly available in this repository.

---

## 📜 License

This project is licensed under the MIT License.

---
