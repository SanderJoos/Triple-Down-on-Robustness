Triple Down on Robustness: Understanding the Impact of Adversarial Triplet Compositions on Adversarial Robustness

## Description

This paper contains the code for the paper Triple Down on Robustness: Understanding the Impact of Adversarial Triplet Compositions on Adversarial Robustness, under review at MDPI MAKE.

Included in this repository is:

* The source code for the submission, including code for:
    * Training new models
    * Mining adversarial triplets
    * Allignment of the VGGFace2 Dataset (See [Datasets](#datasets))
    * The exact backbone sof our deep convolutional neural networks
    * Data augmentation
    * Performing the AutoAttack benchmark
* The exact replication of our conda environment, including pip-installed packages
* A link to the models (See [Models](#models))

## Models

The models can be downloaded from [this Google drive link](https://drive.google.com/drive/folders/1LX4yllAjcwQ1zITEqJwWSk78qPOo3d1f?usp=sharing). The link contains all final models used in evaluation and some additional numpy files that contain our counting of the triplets that would have been mined from the test set.

## Datasets

The following datasets are used:

* CIFAR-10, which can be downloaded with the provided data loaders in the source code through the default PyTorch code
* CIFAR-100, which can also be downloaded in the same way
* VGGFace2, which can be downloaded from for example [InsightFace](https://github.com/deepinsight/insightface/tree/master/recognition/_datasets_), or another source and aligned with the provided source code.
