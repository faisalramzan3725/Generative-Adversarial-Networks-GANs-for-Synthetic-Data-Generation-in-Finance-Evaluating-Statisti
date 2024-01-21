# Synthetic Data Generation for Tabular Data

## Overview

In this project, our goal is to address challenges in working with a given input dataset containing irregularities such as missing rows and other inconsistencies. We have performed data cleaning and preprocessing, resulting in a cleaned dataset named `Train.csv`.

## Baseline Model

To tackle the task of synthetic data generation, we initially tested a baseline model from [Diyago's GAN for Tabular Data](https://github.com/Diyago/GAN-for-tabular-data). The synthetic data generated by this baseline model is stored in the file named `synthetic_tbGan.csv`.

## Customization and Modifications

Upon evaluating the synthetic data against our requirements for production tasks, we found that the baseline model did not meet our needs. As a result, we decided to modify the GAN default model and adjust some parameters to better suit our dataset.

## FinGan - Our Custom Model

The modified GAN, which we refer to as FinGan, was used to generate a new synthetic dataset. The output of this process is stored in the file named `synthetic.csv`. In this README, we will discuss our results and demonstrate how the produced data aligns with the input dataset, showcasing its relevance and utility for prediction tasks.

## Repository Structure

data/
Train.csv # Cleaned and preprocessed input dataset
synthetic_tbGan.csv # Synthetic data generated by the baseline GAN
synthetic.csv # Synthetic data produced by our custom FinGan model
code/
fin_gan_model.ipynb # Jupyter notebook for our custom FinGan model
Jupyter notebook for comparing synthetic data with requirements
README.md # Project overview and documentation

