**Particle Track Reconstruction with ML**

A personal project exploring the application of machine learning for reconstructing particle trajectories from the TrackML dataset. This repository contains implementations of clustering algorithms to group 3D hit coordinates in particle detectors, serving as a bridge between particle physics and machine learning.

**Project Overview**

In experimental particle physics, charged particles leave traces ("hits") as they travel through layered detector systems. The challenge is to group these hits into individual particle trajectories, a process known as track reconstruction. This project tackles this problem using unsupervised learning algorithms.

**Key Features:**

1) Exploratory Data Analysis (EDA) of the TrackML dataset to understand hit distributions and detector geometry.
2) Implementation of clustering algorithms (K-Means, DBSCAN) using Scikit-learn to group hits into potential particle tracks.
3) 3D visualization of hit data and clustering results using Matplotlib.
4) A modular codebase for easy experimentation and extension.

**Dataset**

This project uses the TrackML Particle Identification dataset from Kaggle, which simulates hits from a typical collider experiment.

**Usage**

The primary work is documented in the Jupyter Notebook:

(jupyter nb link): Contains the full workflow from data loading, EDA, preprocessing, clustering, and visualization.

**Preliminary Results**

The project successfully applies clustering techniques to the 3D hit data, providing a foundational baseline for particle track reconstruction. Future work will focus on improving accuracy with more sophisticated algorithms and evaluation metrics.

**License**

This project is licensed under the MIT License - see the LICENSE.md file for details.

**Acknowledgments**

TrackML collaboration for providing the dataset and the problem statement.
CERN and other particle physics laboratories for their pioneering work.
