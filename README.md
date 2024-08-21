# Higgs-Boson-Event-Detection
The goal of the project is to classify an event produced in the particle accelerator as background or signal. A background event is explained by the existing theories and previous observations. A signal event, however, indicates a process that cannot be described by previous observations and leads to the potential discovery of a new particle.


# Overview
In particle physics, an event refers to the results just after a fundamental interaction took place between subatomic particles, occurring in a very short time span, at a well-localized region of space.

A background event is explained by the existing theories and previous observations. On the other hand, a signal event indicates a process that cannot be described by previous observations and leads to the potential discovery of a new particle.

In this project, we aim to predict if a given event is background or signal, based on the data provided in the Kaggle competition Higgs Boson Machine Learning Challenge.

A detailed backdrop of the problem is given, and exploratory data analysis on the provided data is carried out.

The observations obtained from EDA are used in the data preprocessing and feature engineering stages.

We build a neural network and tune it to predict if a given event is background or signal.

I employ the approximate median significance (AMS) metric to evaluate the models. The final model obtains a training AMS of 2.500144 and a test AMS of 1.200022
. It achieves a training accuracy of 0.827070 and a test accuracy of 0.824100
.
