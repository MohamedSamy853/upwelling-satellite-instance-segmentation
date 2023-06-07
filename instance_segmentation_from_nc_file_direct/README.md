## Fuzzy C-Means Clustering for Upwelling Satellite Image Analysis to use as a Mask 
This repository provides an implementation of Fuzzy C-Means (FCM) unsupervised algorithm for clustering and extracting masks from NetCDF (nc) files. The extracted masks can be used to train a U-Net model for instance segmentation, specifically targeting the regions associated with upwelling phonemes.
## Introduction
Instance segmentation plays a vital role in computer vision tasks by identifying and delineating individual objects within an image. This project focuses on utilizing Fuzzy C-Means clustering as an unsupervised algorithm to extract masks from NetCDF files. These masks are specifically designed to highlight regions associated with upwelling phonemes.

The Fuzzy C-Means algorithm provides a flexible approach for clustering data points based on their similarity. By leveraging this algorithm, we can effectively group similar areas within NetCDF files and extract masks that isolate regions exhibiting upwelling phonemes. These masks serve as valuable training data for the subsequent U-Net model used for instance segmentation.
