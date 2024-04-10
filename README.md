![Python 3.7](https://img.shields.io/badge/python-3.7-blue.svg)  

# CERA
> Pytorch implementation for Cross-Domain Heterogeneous Feature Association for Multimodel Emotion Recognition

## Overview
<p align="center">
<img src='img\\architecture.png'/>

CERA comprises three modules: Heterogeneous Feature Decoupling (HFD), Domain Association Modeling (DAM) and Feature Dynamic Fusion (FDF). HFD extracts heterogeneous features from multimodal data, and separates them into modality-invariant and modality-specific domains. DAM associates complementary features within the modality-specific domain (i.e., intra-domain features) or cross domains (i.e., cross-domain features). FDF fuses these intra-domain and cross-domain features for further prediction tasks.

## Usage


### Datasets

[CMU-MOSEI](http://immortal.multicomp.cs.cmu.edu/raw_datasets/CMU_MOSEI.zip)

### get started

1. Set up the environment (need conda prerequisite)

```
conda create -n env_name python==3.7
bash init.sh
```

2. Modify the data path in train.sh and start training

```
bash train.sh
```


