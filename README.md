# Fingerprint_Classification

---
This is a college assignment required for Digital Image Processing course (CS456) .<br>
It is done as teamwork by Khloud Alnufaie, Raghad Albosais and Weaam Alghaith.

---
## Table of content
* [Project overview](#project-overview)
* [Data description](#data-description)
* [Proposed Method](#proposed-method)
* [Tools](#tools)
* [How to run](#how-to-run)
* [Contributors](#contributors)
---

### Project overview

Fingerprints identification and verification systems have been used widely in most important applications in order to ensure public security. Fingerprints are unique and are the most reliable human feature which can be utilized for personal identification. In this project, we aim to build a Machine Learning model to classify fingerprint images into four types: arch, right loop, left loop and whorl. 

---

### Data description

We use the Fingerprint Verification Competition (FVC) 2004 dataset. It consists of fingerprint images of four different types of fingerprints. The dataset has been collected with different types of sensors. You can download the dataset and see more detailed information in this [link](http://bias.csr.unibo.it/fvc2004/databases.asp).


---

### Proposed Method

![Proposed method](https://github.com/RaghadKhaled/Optimization_and_Metaheuristics/blob/main/proposed%20method.jpg)

The overall model architecture that follows the step of implementation is illustrated in figure above. We describing and explain our approach to tackling the CNN model by following the approach applied in this paper “Novel Convolutional Neural Networks based Jaya algorithm Approach for Accurate Deepfake Video Detection”[1](https://journals.mesopotamian.press/index.php/CyberSecurity/article/view/58). We used their proposed method regarding the hyperparameter tuning of CNN using Jaya optimization algorithm. You can find more detiles about each step i the report.

---

### Tools

#### Libraries: 
- Pandas
- openCV
- NumPy
- scikit-learn
- seaborn
- matplotlib


#### Softwares: 
- Google Colab

---

### How to run

You can follow the code in the jupyter notebook 

---

### Contributors

[@AlhanoufAlmans](https://github.com/AlhanoufAlmans)

[@KhloudAlnufaie](https://github.com/KhloudAlnufaie)

[@RaghadKhaled](https://github.com/RaghadKhaled)
