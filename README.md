# Facial Expression Prediction
This project aims to predict different facial expressions given a neutral model, to populate a Neural Network dataset.

For this purpose we made some statistics analysis of a set of facial expressions. After these studies, we achieved to build an
efficent facial expression predictor that can translate a neutral model to an expressive face.

The expressions studied are:

* angry;
* contempt;
* disgust;
* fear;
* happy;
* sadness;
* surprise.

The project is developed by [Alessandro Sestini](https://github.com/SestoAle) and [Francesco Lombardi](https://github.com/fralomba)

## Implementation
In order to strengthen the results, different techniques have been used:
* Mean, median, mode
* Linear regression
* Support Vector Regression (SVR)
* Neural Network

After a study of data distributions thorugh *Mean Shift* algorithm, we can conclude that the best method to create a 
good quality facial expression is the statistics method.

A result example is shown in the figure below:

<p align="center">
<img  src="/results/happy/happy_face_49_alpha_10.jpg" width="100%" height="100%"/>
</p>

The script let the user to emphasize the expression changing an alpha value:

## Installation
To run the project follow these instructions:

1. download the [repository](https://github.com/fralomba/Facial-Expression-Prediction.git);

2. open main.py and change the values in order to obtain the expressions you prefer. You can follow the 
instructions on the comments;

3. the script will output both the neutral and expressive faces.

## Requirements
| Software                                                 | Version         | Required |
| ---------------------------------------------------------|-----------------| ---------|
| **Python**                                               |     >= 3.5      |    Yes   |
| **MATLAB**                                               |    >= R2017b    |    Yes   |
| **MATLAB engine**                                        |       *         |    Yes   |
| **Numpy** (Python Package)                               |Tested on v1.13.3|    Yes   |
| **Scikit-learn** (Python Package)                        |Tested on v0.19.1|    Yes   |
| **h5py** (Python Package)                        		   |Tested on v0.19.1|    Yes   |


 *the installation procedure for Matlab engine for Python is available [here](https://it.mathworks.com/help/matlab/matlab_external/install-the-matlab-engine-for-python.html)

## Report
A copy of the report (italian) can be found 
<a href="https://github.com/SestoAle/Facial-Expression-Prediction/raw/master/report/report.pdf" download="report.pdf">here</a>.

## License
Licensed under the term of [MIT License](https://github.com/SestoAle/Facial-Expression-Prediction/blob/master/LICENSE).
