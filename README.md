# MoCapRunFatigue: Enhancing Motion Capture Running Analysis for Fatigue Detection

This repository contains the source code and documentation for the MoCapRunFatigue project, which aims to replicate and improve upon the findings of the paper titled "A Novel Approach to Motion Capture Analysis for Running Fatigue Detection" ([Original Article](http://xkdd2023.isti.cnr.it/papers/223.pdf)). Our project not only replicates the original study's results but also introduces several enhancements to improve the model's performance and applicability in real-world scenarios.

## Project Overview

The MoCapRunFatigue project is structured around the following key objectives:

- **Replication of Original Study Results**
- **Performance Enhancement through Parallel Processing**
- **Stabilization with Blocked Cross Validation**
- **Exploration of Multivariate Models**
- **Experimentation with Rolling Barycenter Smoothing**

## Key Results and Improvements

Through our enhancements, we achieved significant improvements in the model's performance:

- **Mean Accuracy**: Improved from 95% to 98.5%.
- **Standard Deviation**: Reduced from 0.077 to 0.035, indicating more consistent performance across runners.
- **Minimum Accuracy**: Improved from 70% to 86%, showcasing the model's ability to extrapolate to all different types of runners.
- **Speed**: The model now runs upwards of 18x faster.

Additionally, the introduction of blocked cross validation has resulted in less variation in results between train/test splits, further stabilizing the model's performance and making it more representative of real-world conditions.

## Enhancements Detail

### Replication of Original Study Results
Initially, we focused on accurately replicating the results presented in the original paper to establish a baseline for our improvements.

### Parallel Processing
By implementing parallel processing, we were able to reduce the model's execution time significantly, making it more feasible for real-time analysis and larger datasets. This optimization was achieved in a high-performance computing environment, showcasing the scalability of our approach.

### Blocked Cross Validation
The introduction of blocked cross validation has made our model's results more robust and reliable, addressing the variability often seen in motion capture data and ensuring that our findings are more representative of diverse running patterns.

### Multivariate Models
Our exploration into multivariate models has opened new avenues for understanding the complex dynamics of running fatigue. The improvements in accuracy and reliability underscore the potential of these models in enhancing fatigue detection and prevention strategies.

### Rolling Barycenter Smoothing
While our experiments with rolling barycenter smoothing did not result in the anticipated improvements, they provided valuable insights into the challenges of preprocessing motion capture data and the need for further research in this area.

## Getting Started

To replicate our study or explore the enhancements we've made:

- All necessary data has been included in the `data` folder for simplicity.
- The source code and results are presented in a Jupyter notebook in the `notebooks` folder, opting for simplicity and ease of understanding over a typical data science project structure.

Navigate to the notebook for a step-by-step guide on how to run the analysis and view the results.
