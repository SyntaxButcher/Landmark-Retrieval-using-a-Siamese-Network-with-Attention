# Landmark-Retrieval-using-Deep-Neural-Networks

This is our project on Landmark Retrieval using 2 different models and to show how siamese network(similarity score output) outperforms a ResNet101 classification network for Landmark Retrieval.

The combination of the following GPUs were used for training from HPC Discovery Cluster Platform:
- NVIDIA Tesla A100
- NVIDIA Tesla P100 

*We haven't uploaded the trained model weights due to github size restrictions*
Siamese Model Weights: https://drive.google.com/file/d/1qeikdVI6KJ3Zj6FzQqcI3qSvi6kk8_HH/view
ResNet-101 Baseline Model Weights: https://drive.google.com/file/d/1T0bCxtr0kV1GnYU8qZivzhQWKgv7wv6x/view?usp=sharing

The following is the retrieval results using the Siamese Network
![ProposedOutput](https://user-images.githubusercontent.com/68157882/234788098-85463619-2898-4bba-9f65-b616ccb6b50c.png)
![ProposedOutput1](https://user-images.githubusercontent.com/68157882/234788107-6f9401fc-abc6-43b7-85cd-fc26cdabb6bb.png)
The following is from the baseline ResNet101_Arcface Network
![BaselineOutput](https://user-images.githubusercontent.com/68157882/234788001-740246a0-5d99-4fcb-8c77-06f7d5e00dbe.png)
