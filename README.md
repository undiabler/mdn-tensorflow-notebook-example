# MDN on TensorFlow v2 Example Notebook

This repository contains a Jupyter notebook with an example of a Mixture Density Network (MDN) using Tensorflow. It accompanies [our blog-post](https://engineering.taboola.com/predicting-probability-distributions/) about MDNs.


## Changelog
  - refactored model creation using new tf.keras api
  - added missing optimizers
  - added missing functions from new TensorFlow probability lib
  - refactored loss functions using new eager-style functions
  - removed sessions, refactored model training for TensorFlow v2.0 style
