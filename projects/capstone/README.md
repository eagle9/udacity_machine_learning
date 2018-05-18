# Machine Learning Engineer Nanodegree
## Specializations
## Project: Capstone Proposal and Capstone Project

Software environment
====================
In this project, the python version is Python 2.7.13 :: Anaconda custom (64-bit).
Since version Anaconda version 4.3.0 dated 2017-01-31, Anaconda comes with seaborn installed by default.
The Anaconda version at my laptop is 4.5.3, under windows 10 linux subsystem ubuntu.
Since version 4.3.0 dated 2017-01-31, Anaconda comes with seaborn installed by default.
XGBoost and LightGBM does not come with Anaconda by default. 
XGBoost(py-xgboost version 0.71) has been installed as follows:
conda install -c anaconda py-xgboost #specify the channel of anaconda
The installation guide is at https://anaconda.org/conda-forge/xgboost
The following packages will be UPDATED:

    ca-certificates: 2018.03.07-0                      --> 2018.03.07-0        anaconda
    certifi:         2018.4.16-py27_0                  --> 2018.4.16-py27_0    anaconda
    conda:           4.5.3-py27_0                      --> 4.5.4-py27_0        anaconda
    libxgboost:      0.60-hdfa14d8_0          anaconda --> 0.71-hf484d3e_0     anaconda
    openssl:         1.0.2o-h20670df_0                 --> 1.0.2o-h20670df_0   anaconda
    py-xgboost:      0.60-py27np112h0aae3cd_0 anaconda --> 0.71-py27hf484d3e_0 anaconda
LightGBM has been installed as follows:
conda install -c conda-forge lightgbm #specify the channel of conda-forge
This is based on the installation guide at https://anaconda.org/conda-forge/lightgbm

The final software environment is set up as follows under ubuntu: 
voyiger@LAPTOP-MFFM0LBM:~$ conda list |grep light
lightgbm                  2.1.0                    py27_0    conda-forge
voyiger@LAPTOP-MFFM0LBM:~$ conda list |grep xgboost
libxgboost                0.71                 hf484d3e_0    anaconda
py-xgboost                0.71             py27hf484d3e_0    anaconda
voyiger@LAPTOP-MFFM0LBM:~$ conda list|grep seaborn
seaborn                   0.7.1                    py27_0
voyiger@LAPTOP-MFFM0LBM:~$ conda list|grep pandas
pandas                    0.20.1              np112py27_0
voyiger@LAPTOP-MFFM0LBM:~$ conda list |grep numpy
numpy                     1.12.1                   py27_0
numpydoc                  0.6.0                    py27_0
voyiger@LAPTOP-MFFM0LBM:~$ conda list|grep scipy
scipy                     0.19.0              np112py27_0
voyiger@LAPTOP-MFFM0LBM:~$ conda list|grep  learn
scikit-learn              0.18.1              np112py27_1

Datasets
========
The training and test data sets can be downloaded from
https://www.kaggle.com/c/zillow-prize-1/data

Original Message
================
The Capstone is a two-staged project. The first is the proposal component, where you can receive valuable feedback about your project idea, design, and proposed solution. This must be completed prior to your implementation and submitting for the capstone project. 

You can find the [capstone proposal rubric here](https://review.udacity.com/#!/rubrics/410/view), and the [capstone project rubric here](https://review.udacity.com/#!/rubrics/108/view). Please ensure that you are following directions correctly before submitting these two stages which encapsulate your capstone.

Please email [machine-support@udacity.com](mailto:machine-support@udacity.com) if you have any questions.

