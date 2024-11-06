# DataMining-HK241

## Overview
A mini project about Recommendation System for Ecommerce \
Based on the paper [Mamba4rec: Towards efficient sequential recommendation with selective state space models](https://arxiv.org/abs/2403.03900)
and their source code for [Mamba4Rec model](https://github.com/chengkai-liu/Mamba4Rec)

## Quickstart
Train on custom dataset
1. Add a subdirectory containing the interaction data `.inter` in `dataset/`
  For example:
  ```
  dataset/hm/hm.inter
  ```
2. Modify or create a new config file (.yaml)
3. Train the model
  ```
  python run.py --config_file=<path/to/config_file> --checkpoint_file=<path/to/checkpoint_file>[optional]
  ```
