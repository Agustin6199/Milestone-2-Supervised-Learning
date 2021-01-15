# Milestone 2  - Supervised Learning

This repository that contains the material related to the milestone 2 of the subject Machine Learning Techniques from the computer engineering degree of the University of Castilla-La Mancha.


## Introduction

The purpose of this work is to use machine learning techniques to make prediction of dengue cases over the environmental data collected by various U.S. Federal Government Agencies from two different cities (San Juan in Puerto Rico and Iquitos in Peru).

![alt text](https://drivendata-prod-public.s3.amazonaws.com/images/drivendata-logo.svg "Logo Title Text 1")

This data comes from a competition of the site DrivenData. The information about this competition can be found in the following link: 

[DrivenData Competition](https://www.drivendata.org/competitions/44/dengai-predicting-disease-spread/}{https://www.drivendata.org/competitions/44/dengai-predicting-disease-spread/)

Our main objective, as we said previously, is to apply supervised learning techniques in order to predict the total cases of Dengue for each city, year and week of the test data. In the notebooks, a submission has been built containing the predictions for both cities, which can be uploaded to DrivenData to evaluate the error made on the test set when predicting. To achieve this goal, we have first developed a baseline with simple regression techniques, on which we have subsequently made two lines of improvement.


## File hierarchy

In the following scheme you can see the directory structure of our repository, containing descriptions of each element.

```python
├── README.md                                                                     <- The top-level README for users using this project.
├── data
│   ├── dengue_features_train.csv                                                 <- Data related to the features of the training dataset.
│   ├── dengue_labels_train.csv                                                   <- Data related to the labels of the training dataset.
│   └── dengue_features_test.csv                                                  <- Data related to the features of the test dataset.
│
├── notebooks
│   ├── Supervised_Learning_Base_Line_Machine_Learning.ipynb                      <- Base line where we use a basic regression technique.
│   ├── Supervised_Learning_Medium_Line_Machine_Learning.ipynb                    <- Medium line where we do some improvements over base line.
│   └── Supervised_Learning_High_Line_Machine_Learning.ipynb                      <- High line containing the model that gives us the best results.
│
├── reports      
│   ├── report.pdf                                                                <- Report describing the process and techniques used.
│   └── figures                                                                   <- Folder containing images of all the graphics generated in the notebooks.
│
└── results
    ├── Base-Line                                                                 <- Folder containing the .csv with the best result provided by the Base-Line.
    ├── Medium-Line                                                               <- Folder containing the .csv with the best result provided by the Medium-Line.
    └── High-Line                                                                 <- Folder containing the .csv with the best result provided by the High-Line.

```

## Reproducibility

In order to be able to reproduce our results, the first thing we will have to do is clone the repository on your local.  

Although we have three different notebooks (each one corresponding to a line of improvement), they are totally independent from each other, so if you want to run one of them, no intermediate data will be necessary. To run any of our notebooks, you will have to open them with appropriate software such as [Jupyter Notebook](https://jupyter.org/) or [Google Colab](https://colab.research.google.com/), and run all the cells of that notebook. The only thing you will have to do is to load the files corresponding to the training and test data in the data load cells. 

Once every cell has been executed, a .csv file will be downloaded containing the results of the notebook. This results can be uploaded as a submission to DrivenData.

## Other links

Finally, here you can find some links that may be useful. These links correspond to the cloud versions of the notebooks in the repository.

* [Supervised Learning: Base Line - Machine Learning](https://colab.research.google.com/drive/1Djc_IIkVi0dvFdNQN1xlL8-KEi9JStIf?usp=sharing)
* [Supervised Learning: Medium Line - Machine Learning](https://colab.research.google.com/drive/1sYMJDbV94GME8XiZoxZ_fy9e9fF9o0BN?usp=sharing)
* [Supervised Learning: High Line  - Machine Learning](https://colab.research.google.com/drive/15UjKjH000ZwIdVHswM5XzF4Uv_BghU_r?usp=sharing)
