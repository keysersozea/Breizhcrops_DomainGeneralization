# Domain-Adversarial Neural Networks for Time Series Domain Generalization

This repository contains the implementation and experiments of using Domain-Adversarial Neural Networks (DANN) to enhance domain generalization in time series data, specifically applied to the BreizhCrops dataset.

## Overview

This project aims to improve the generalization capabilities of an LSTM model to handle data from different geographic regions. By integrating DANN, the model is trained to produce features that are invariant to domain-specific characteristics, enhancing its performance on unseen data.

## Project Structure


- `firstly.ipynb`: Trains an LSTM model and performs a 4-fold cross-validation across regions.
- `Lower_Upper.ipynb`: Calculates the lower and upper baselines for each fold.
- `Lower_Upper_Decision.ipynb`: Further analysis and decision-making on the baseline calculations.
- `domain_adversarial_learning.ipynb`: Implements and trains the DANN model.
- `analyze.ipynb`: Analyzes the results of the experiments.
- `README.md`: Project overview and instructions.
