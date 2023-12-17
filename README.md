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
* [Slides (X slides)](https://github.com/gwendysyd/Placenta-Insufficiency-Classification/blob/master/doc/...pdf)
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

| Criteria                                     | AUC  | F1-Score PoC | Accuracy | Sensitivity | Specificity | PPV   | NPV   | PLR   | NLR   |
|---------------------------------------------------|------|--------------|----------|-------------|-------------|-------|-------|-------|-------|
| Birth weight percentile < 3                       | 0.8  | 0.43         | 0.85     | 0.75        | 0.86        | 0.3   | 0.98  | 5.46  | 0.29  |
| CIR | 0.74 | 0.4          | 0.9      | 0.5         | 0.93        | 0.33  | 0.96  | 6.75  | 0.54  |
| Preeclampsia    | 0.76 | 0.53         | 0.96     | 0.44        | 0.99        | 0.67  | 0.97  | 34.67 | 0.56  |
| LBS or CIR or Preeclampsia           | 0.63 | 0.39         | 0.74     | 0.58        | 0.77        | 0.3   | 0.92  | 2.51  | 0.54  |
