# PECL
# PECL: Pseudo-label Enhanced Consistency Learning for Semi-supervised Medical Image Segmentation

This repository contains the official implementation of **PECL**, a pseudo-label enhanced consistency learning framework for semi-supervised medical image segmentation.

> **Code Release Notice**
> The code is currently being organized and documented. The complete implementation, including training scripts, testing scripts, configuration files, and data preparation instructions, will be released soon.

## Overview

PECL aims to improve pseudo-label reliability when only limited annotated medical images are available. The framework integrates:

* Triple-network voting for pseudo-label refinement
* Bidirectional copy-paste augmentation between labeled and pseudo-labeled data
* 3D GridMask-based data augmentation
* Consistency learning for semi-supervised segmentation

The method is evaluated on commonly used medical image segmentation benchmarks, including LA, ACDC, and Pancreas-CT datasets.
