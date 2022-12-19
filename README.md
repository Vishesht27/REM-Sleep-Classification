# REM Sleep Disorder prediction using EDF dataset and Score level fusion

## Table of Contents

- [Abstract](#abstract)

- [Introduction](#introduction)

- [Objective](#objective)

## Abstract

Rapid eye Movement (REM) sleep behavior disorder belong to the family of sleep
disorders occurring worldwide. Several existing studies demonstrate EEG images and EMG metrics for classifying RBD & non-RBD patients. However, merely few researchers have used EDF data available into the existing algorithms. This paper builds an ensemble method combing the metrics and results of different models trained on the EDF dataset to analyze the difference between REM and non-REM patients. The EDF's numerical data is also integrated for further results. The different algorithms and models which were trained included Naive Bayes Classification, Random Forest, Logistic Regression and Gradient Boosted trees. However, the final prediction is attained by their score-level fusion, where each model is assigned with some weight based on its individual recall score.

## Introduction

Sleep is a significant determinant of mental wellbeing and happiness. Sleep disorders are conditions that impair our sleep or prevent us from getting restful sleep and, as a result, can cause daytime sleepiness and other symptoms. Troubled sleep is a common complaint all over the world. According to the American Sleep Association (AMA), sleep disorders affect 50 to 70 million adults in the United States of America  Not getting the proper amount or quality of sleep leads to more than just feeling tired. Sleepiness interferes with cognitive function, which can lead to learning disabilities in children, memory impairment in people of all ages, personality changes and depression. People who are deprived of sleep have trouble making decisions, irritability, have problems with performance, and slower reaction times, placing them at risk for automobile and work-related accidents. Sleep loss can also adversely affect life by contributing to the development of obesity, diabetes and heart disease. Insomnia, Bruxism, Narcolepsy, Nocturnal frontal lobe epilepsy, Periodic leg movements, REM behavior disorder, Sleep-disordered breathing are the widely known forms of sleep disorders. The most predominant manners of sleep are Rapid Eye movement (REM), sleep and non-REM sleep. REM sleep first begins about one and a half hours after falling asleep. The eyes switch rapidly behind shut eyelids from side to side. The respiration is quicker; the pulse and heart rate rise to waking levels. Most of the dreams take place during REM sleep, while some could occur in non-REM too. The body passes through all stages of non-REM sleep before entering the REM. Each of the stage lasts for 5-15 minutes.


## Objective

The objective of work was to study the EDF data and process it in such a way that we can use it for visualization and to train model. Also, after visualizing the EDF data, we had used different type of classification algorithms to build a model, which can classify the REM and Non-REM type of sleep disorder. So that, it can help people manage their sleep time accordingly and easily understand their REM sleep disorder.
