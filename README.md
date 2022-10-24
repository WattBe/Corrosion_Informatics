## Corrosion Informatics

Notebooks and Data

Shield: [![CC BY 4.0][cc-by-shield]][cc-by]

This work is licensed under a
[Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International][cc-by].

[![CC BY 4.0][cc-by-image]][cc-by]

[cc-by]: http://creativecommons.org/licenses/by/4.0/
[cc-by-image]: https://i.creativecommons.org/l/by/4.0/88x31.png
[cc-by-shield]: https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg


## Summary of the Project

(Excuses to the original Autor) 
* 1. An educational institution has asked me to revisit this Study and the data it contains in order for it to be included on a university curriculum for second-year engineering students.
* 2. This is project to present as Capstone. Therefore I have to create an external stakeholder for which I will have to solve the problem. In this case a Journal had contacted me to prove the accuracy compliance of data published. The study tried different approaches and it is expected in the present study to reproduce the data but also to design a simple neuronetwork. Ultimately Data reliability is to be constatate through this approach.

### Abreviations
|Abreviation| Meaning|
|-|-|
|Electrochemical impedance spectroscopy| (EIS)  |
|Electrical equivalent circuit       | (EEC)|
|vector regression algorithm|(SVM)| 
|Back propagation neural network| (BPNN)|
|Laser powder bed fusion |(LPBF)|
|finite element method|FEM|
|Leave-one-out cross validation)|LOOCV|
|Potentiodynamic polarization |(PD)|

## Literature Research Background

This project is based on the work by O. V. Mythreyi 1, M. Rohith Srinivaas 2, Tigga Amit Kumar 3 and R. Jayaganthan 1
Machine-Learning-Based Prediction of Corrosion Behavior in
Additively Manufactured Inconel 718 (Data 2021, 6, 80. [Original Article](https://doi.org/10.3390/data6080080)
** Abstract
>This research work focuses on machine-learning-assisted prediction of the corrosion
>behavior of laser-powder-bed-fused (LPBF) and postprocessed Inconel 718. Corrosion testing data of
>these specimens were collected and fit into the following machine learning algorithms: polynomial
>regression, support vector regression, decision tree, and extreme gradient boosting

## Motivation
The motivation for conducting this study is to develop a predictive model that can predict the corrosion behavior of an LPBF component and mathematically compute the contribution Data 2021, 6, 80 3 of 16 arising from each postprocessing treatment in the additive processing cycle. machine learning algorithms were used to predict the electrochemical
behavior of Inconel 718 produced via the additive route.
The __independent__ features considered were heat treatment temperature and duration, shot peening
inclination and velocity

## Dataset
The specimens, thus printed, postprocessed, and categorized, were tested for general
corrosion using an electrochemical method.


Environment
Before you can install xgboost in your new environment you need to install cmake. If you haven't done it yet, run the following command:

brew install cmake
There are two ways to create and activate a new virtual environment for this repo. You can either use the requirements file and run the following commands...

pyenv local 3.9.8
python -m venv .venv
source .venv/bin/activate
pip install --upgrade pip
pip install -r requirements.txt
... or you can make use of the Makefile we included in this repo. This makefile stores a bunch of bash commands which will be executed when running the following command in the terminal (make sure you are in the correct folder):

make setup
After creating the environment using the makefile you still need to activate it running the source command!

Note: If there are errors during environment setup, try removing the versions from the failing packages in the requirements file.

