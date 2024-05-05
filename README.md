# Image Colorization Comparative Analysis

## Overview

This repository contains code and documentation for a comparative analysis of various image colorization techniques. The project explores both deep learning and non-deep learning methods, evaluating their performance on a dataset of grayscale images.

## Project Structure

The repository is organized into several directories, each corresponding to a different colorization method:

- `SVR`: Contains code and documentation for the Support Vector Regression method.
- `Parzen_Window_Method`: Code and documentation for the Parzen Window Method.
- `CNN`: Implementation details for the Convolutional Neural Network approach.
- `cGAN`: Information about the conditional Generative Adversarial Network (cGAN) method.

## Contributors

- Henry Lam
- Thomas Skøtt Gummesen
- Bartholomeus Diederik Rasmussen Pepping
- Magne Egede

## Key Findings

The comparative analysis revealed various insights into the performance of different colorization techniques:

- SVR demonstrated suitability for smaller datasets but struggled with nuanced color transitions.
- The Parzen Window Method exhibited patchiness and inconsistent coloration, suggesting the need for refinement.
- CNN showed promising results, especially for nature images, but faced challenges with cityscapes.
- The cGAN method holds potential but requires further exploration and evaluation against other techniques.

## Next Steps

Based on the findings, several recommendations for further research and development were proposed:

- Improving scalability and quality of SVR through alternative algorithms and smoothing techniques.
- Enhancing the Parzen Window Method with pixel-to-section level approaches and coherence optimization.
- Fine-tuning CNN models, exploring hyperparameter optimization, and incorporating diverse datasets.
- Further evaluation and comparison of cGAN against other methods, considering training data quantity and quality.

## Report

For detailed insights and analysis, please refer to the full written report available in my blog.

## Contact

For questions, feedback, or support, please contact me at [support@henrylam.blog](mailto:support@henrylam.blog).
