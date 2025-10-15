# Particle Track Reconstruction with Machine Learning

A personal project exploring the application of **machine learning** for reconstructing **particle trajectories** from the **TrackML dataset**.  
This repository implements **clustering algorithms** to group 3D hit coordinates in particle detectors — bridging **particle physics** and **data science**.  

---

## 🔍 Project Overview

In experimental **particle physics**, charged particles leave traces ("hits") as they move through layered detector systems.  
The challenge is to **group these hits into individual particle tracks**, a process known as **track reconstruction**.  

This project tackles that challenge using **unsupervised learning algorithms** to cluster 3D hit data into meaningful trajectories.

---

## ✨ Key Features

- **Exploratory Data Analysis (EDA)** — Analyze hit distributions and detector geometry.  
- **Machine Learning Models** — Implement **K-Means** and **DBSCAN** clustering using *Scikit-learn*.  
- **3D Visualization** — Render hit data and clustering outputs with *Matplotlib*.  
- **Modular Codebase** — Clean, extensible structure for quick experimentation and future upgrades.

---

## 📁 Dataset

This project uses the **TrackML Particle Identification** dataset from [Kaggle](https://www.kaggle.com/competitions/trackml-particle-identification),  
simulating detector hits from a collider experiment.  

Each event contains:
- 3D hit coordinates  
- Detector layer information  
- Ground-truth particle IDs (for benchmarking)  

---

## 🚀 Usage

Open the Jupyter Notebook to explore the full workflow:

```bash
trackml_clustering_analysis.ipynb

## The notebook covers:
1. Data loading and preprocessing
2. Exploratory data analysis (EDA)
3. Clustering with K-Means and DBSCAN
4. 3D visualization of particle tracks

