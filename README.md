# 🐍Venomous Snake Detection Using Computational Neural Network

This repository contains complete resources for NNFLL Project (Dataset Link : https://data.mendeley.com/datasets/28r5f3vmrp/2)

This project presents a learning system designed for the precise recognition of highly venomous snake species in Bangladesh, an essential measure, for providing proper antivenom therapy and lowering snakebite death rates.

Key Problem

Identifying snakes manually is difficult because many species look alike there is public knowledge and expert herpetologists are rare in resource-poor rural areas. The three main species, which cause than 90% of potentially deadly snakebites, in Bangladesh include the Common Krait (Ckrait) King Cobra (Kcobra) and Russells Viper (Rviper).

Methodology and Models

This framework employs Convolutional Neural Networks (CNNs) along, with transfer learning derived from leading-edge models (VGG16, ResNet50 Inception V3, MobileNet V2).

Dataset: A tier, clinically authenticated dataset consisting of 101 training images and 45 testing images spanning the three venomous species was utilized.

Top Performing Model: MobileNet V2 attained the total test accuracy of 91% greatly surpassing the custom CNN baseline (44%) along, with other transfer learning models.

Techniques: To enhance generalization despite the dataset size data augmentation methods (flipping, rotation, zoom contrast modification) and class weighting were utilized.

Impact and Future Work

The superior performance and lightweight architecture of MobileNet V2 (3.5M parameters) make it a viable candidate for deployment in a light-weight, offline-capable mobile application. This application could aid healthcare workers, forest officials, or common people in rapid, accurate species identification during an emergency, thereby improving clinical outcomes.

## Installation

To run this project, you will need to install the following Python libraries:

```bash
pip install tensorflow keras scikit-learn matplotlib numpy seaborn
=======

