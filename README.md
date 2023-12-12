# LMTSC-IOD

# Lightweight Multivariate Time-Series Classification for Indoor-Outdoor Detection

This repository contains the implementation and resources associated with the paper focusing on the accurate classification of indoor and outdoor environments using multivariate time series data.

## Abstract

In location-based services, the importance of accurately classifying indoor-outdoor detection (IOD) using various context-aware sensors is gaining much importance, making it a valuable research topic. IOD aims to classify the user's location in an indoor or outdoor environment using context-aware sensors. Threshold-based methods have shown poor accuracy and limited scalability, while machine learning and deep neural network-based approaches have yet to consider the temporal dimension. Despite advances, the accuracy of state-of-the-art approaches remains under 90%, continuing to challenge the precise classification of indoor and outdoor systems. This paper significantly increases accuracy by presenting a novel, robust framework using a lightweight, custom Bi-Parallel CNN-LSTM architecture and ensemble learning. We also proposed a novel adaptive feature scaling-based method (AFS) for augmentation. In this proposed scaling approach, the features are scaled to the calculated range, giving a more adequate representation of the data since every feature is separately normalized. The proposed architecture has two parallel 1D CNN branches, followed by LSTM, and concatenates both, thus effectively capturing spatial and temporal features. We conducted comprehensive evaluations, incorporating rigorous six-fold cross-validation on the proposed and public datasets. The results show a test accuracy of 99.69%, an increase of approximately 10% compared to the baseline, a reduction in training time of approximately 97%, and a reduction in memory utilization of around 95%, thus demonstrating the robustness of the proposed approach.

## Introduction

The accurate identification of transitions between indoor and outdoor environments is crucial for various applications. Traditional methods and existing deep learning models face challenges in capturing temporal dependencies and spatial patterns. This paper introduces an enhanced framework incorporating adaptive feature scaling, a novel CNN-LSTM architecture, and ensemble learning, surpassing limitations of prior approaches.

## Major Contributions

1. Introduction of a lightweight, custom Bi-Parallel CNN-LSTM architecture for distinguishing between indoor and outdoor settings.
2. Adaptive Feature Scaling (AFS) approach to dynamically adjust feature ranges, enhancing data representation.
3. Utilization of ensemble-based inference for increased prediction stability and performance.
4. Release of a novel dataset specifically designed for indoor-outdoor detection, promoting reproducibility and future research.

## Usage

The code and resources provided here implement the methodologies and techniques proposed in the paper. Follow the instructions in each directory to reproduce experiments and results.

Download the datasets from [here](https://drive.google.com/drive/folders/1bVoTa0JYDVYIkGKHgTxG5WcBy3vw_eoe)

## Citation

If you find this work helpful or use any part of the provided resources, please consider citing:

[Insert Paper Citation]

## License

This project is licensed under [Insert License]. See the LICENSE file for details.

---

For more details, methodology, and results, please refer to the full paper.

[Link to Paper PDF or DOI]

