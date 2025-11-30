### Programming for Psychologists (2025/2026)
# Home Assignment: Visualizing Neurosynth Meta-Analysis Data for “Decision Making”
Course coordination: Matthias Nau\
Student: Luca Celine Ruthe\
Date: Nov 30, 2025

Link to the Neurosynth page of my concept "Decision making": [MRI Data](https://neurosynth.org/analyses/terms/decision%20making/)

Description of the project:
This project analyses and visualizes meta-analytic fMRI data for the cognitive concept “decision making”, using anatomical and functional maps downloaded from the Neurosynth platform.
The functional map (uniformity test statistic) represents how strongly each voxel across the brain is associated with the term “decision making” in aggregated neuroimaging studies. 
The project includes code for automatically locating the MRI files, visualizing the functional data on top of the anatomical scan using Nilearn, and analysing voxel intensities through a histogram.

Table of Contents:
Notebook:
home_assignment_notebook.ipynb — includes all steps (file loading, visualization, histogram, documentation).
Data:
uploaded from here: https://neurosynth.org/analyses/terms/decision%20making/
Functional map (decision making_uniformity-test_z_FDR_0.01.nii)
Anatomical map (anatomical.nii)
Figures:
Visualization outputs shown directly in the notebook.


Python Packages Used
This project was completed in a dedicated conda environment containing:
Python 3
NumPy
Matplotlib
NiBabel
Nilearn
glob (standard library)
os (standard library)
