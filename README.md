Machine Learning in materno-fetal ultrasound images for early detection of late-onset placental insufficiency
=

[![made-with-python](https://img.shields.io/badge/Coded%20with-Python-21496b.svg?style=for-the-badge&logo=Python)](https://www.python.org/)
[![made-with-latex](https://img.shields.io/badge/Documented%20with-LaTeX-4c9843.svg?style=for-the-badge&logo=Latex)](https://www.latex-project.org/)
![GitHub repo size](https://img.shields.io/github/repo-size/gwendysyd/Placenta-Insufficiency-Classification?style=for-the-badge&logo=Github)
![Github code size](https://img.shields.io/github/languages/code-size/gwendysyd/Placenta-Insufficiency-Classification?style=for-the-badge&logo=Github)
![GitHub license](https://img.shields.io/github/license/gwendysyd/Placenta-Insufficiency-Classification?style=for-the-badge&logo=Github)

###### Ultrasound images binary classification for late-onset placental insufficiency

***********

**Master's Thesis. Master's in Data Science at Universitat Oberta de Catalunya.**

#### Author
* **Gwendolin Herrera Carballido** - [gherrerac@uoc.edu](mailto:gherrerac@uoc.edu)

#### Tutor: 
* **Xavier Paolo Burgos Artizzu** - [xburgosa@uoc.edu](mailto:xburgosa@uoc.edu)

***************
* [Report (X pages)](http:...)
* [Slides (24 slides)](https://github.com/gwendysyd/Placenta-Insufficiency-Classification/blob/master/docs/Slides.pdf)
***************

#### Experiments:
* **Deep Learning**:
    * ***Architectures:***
        * Custom ANN (Artificial Neural Network)
        * VGG16
        * MobileNet
        * ResNet50
        * ResNet18

* **Computer Vision**:
    * ***Feature extraction:***
        * HOG (Histogram of Oriented Gradients)
        * GLCM (Gray Level Co-occurrence Matrix)
    * ***Classifiers:***
        * SVC (Support Vector Classifier)
        * XGBOOST (eXtreme Gradient Boosting)
        * Logistic Regression

***************
## Results

| Criteria | Max Sensitivity | AUC  | F1-Score Pos Class | Accuracy | Specificity | PPV  | NPV  | PLR   | NLR   |
|----------|------------------|------|---------------------|----------|--------------|------|------|-------|-------|
| LBW or CIR or PRE       | 0.36             | 0.60 | 0.33                | 0.69     | 0.79         | 0.31 | 0.82 | 1.64  | 0.83  |
| Birth weight percentile < 10 (LBW)      | 0.29             | 0.53 | 0.27                | 0.77     | 0.86         | 0.27 | 0.86 | 1.96  | 0.84  |
| Preeclampsia (PRE)      | 0.56             | 0.76 | 0.53                | 0.96     | 0.99         | 0.67 | 0.97 | 34.67 | 0.56  |
| Fetal Growth Restriction (CIR)     | 0.33             | 0.55 | 0.29                | 0.91     | 0.96         | 0.33 | 0.94 | 6.42  | 0.78  |
