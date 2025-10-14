# ALMA Fitting and Pixelated Source Reconstruction with Lenstronomy

This repository contains example notebooks and resources for performing pixelated source reconstruction and parametric modeling of ALMA interferometric images using [`lenstronomy`](https://github.com/lenstronomy/lenstronomy). The examples are designed to help users understand and apply these techniques in their own work.

---

## 📁 Repository Structure

### `code_tutorials/`  
This is the **main part of the repository** and contains well-documented example notebooks:

- `ALMA image parametric fitting.ipynb`:  
  A complete example demonstrating how to fit simulated ALMA dirty images using a parametric lens model and the specialized interferometric likelihood in `lenstronomy`.

- `Pixelated source reconstruction.ipynb`:  
  A walkthrough of pixelated source reconstruction from a lensed image, including the setup of regularization and solving for the optimal regularization strength. Not specific to ALMA.

- `source_reconstruction_explanation.md`:  
  A companion file providing background and notations for the pixelated source reconstruction method.

These notebooks can be used as practical templates for lens modeling projects.

### `additional_tests/`  
This folder provides notebooks and results for additional tests of the ALMA fitting pipeline that are not displayed in the paper.
- ALMA Point Source Fitting Tests:
  We test the ALMA image fitting in two senarios that involve point sources: unlensed point sources and quadruply imaged quasar. The result shows the likelihood function works well for point source as well.

### `science_results/`  
This folder contains scripts and notebooks related to the lens modeling analysis of SPT galaxies. These are provided as reference materials.

---

##  Citation and Method
The methods used here are described in detail in: (https://arxiv.org/abs/2508.08393)

---


##  Feedback
If you have questions, suggestions, or would like to contribute improvements to the examples, feel free to contact Nan Zhang at nanz6@illinois.edu
