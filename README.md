# MoCapRunFatigue: Enhancing Motion Capture Running Analysis for Fatigue Detection

This repository contains the source code and documentation for the MoCapRunFatigue project, which aims to replicate and improve upon the findings of the paper titled "A Novel Approach to Motion Capture Analysis for Running Fatigue Detection" ([Original Article](http://xkdd2023.isti.cnr.it/papers/223.pdf)). Our project not only replicates the original study's results but also introduces several enhancements to improve the model's performance and applicability in real-world scenarios.

## Project Overview

The MoCapRunFatigue project is structured around the following key objectives:

1. **Replication of Original Study Results**: Initially, we focused on accurately replicating the results presented in the original paper to establish a baseline for our improvements.

2. **Performance Enhancement through Parallel Processing**: We significantly improved the model's execution speed by approximately 18 times by leveraging parallel processing techniques, utilizing a high-performance computing environment with 96 vCPUs and 192 GiB of memory.

3. **Stabilization with Blocked Cross Validation**: To ensure the results are more stable and reflective of real-world conditions, we introduced blocked cross validation into our analysis process.

4. **Exploration of Multivariate Models**: Our investigation into multivariate models demonstrated noticeable improvements in mean accuracy, standard deviation, and minimum accuracy, indicating a substantial enhancement over the original model.

5. **Experimentation with Rolling Barycenter Smoothing**: Although we experimented with rolling barycenter smoothing to reduce noise in the input data, this approach did not yield the expected improvements.

## Enhancements Detail

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
- The source code and results are presented in a Jupyter notebook, opting for simplicity and ease of understanding over a typical data science project structure.

Navigate to the notebook for a step-by-step guide on how to run the analysis and view the results.
