# OD-GCResNet: A Deep Learning Model for Kitchen Activity Recognition Using Micro-Doppler Signatures

**IEEE ICC 2025 · Co-first authors: Yinan Pei, Shaohua Hu, and Junjia Cao**

[DOI: 10.1109/ICC52391.2025.11161477](https://doi.org/10.1109/icc52391.2025.11161477) · Pages 3168–3173 · [Official code and data](https://github.com/Canberra1111/Kitchen-Micro-Doppler-HAR-with-OD-GCResNet)

## Overview

OD-GCResNet is a hybrid deep-learning model for kitchen activity recognition from radar micro-Doppler spectrograms. The work addresses non-invasive, privacy-preserving monitoring for elderly people living alone, without relying on cameras or wearable devices.

## Method

- **ODConv:** dynamic attention for adaptive convolutional feature extraction.
- **Recursive gated convolution (gⁿConv):** higher-order spatial interaction and broader contextual modelling.
- **SEBlock:** channel-wise feature recalibration.
- **Residual connections:** support training and gradient flow.
- **Radar data:** two BumbleBee radar nodes, 15 kitchen activities, spectrograms downsampled to `80 × 80 × 2`.

## Reported Results

- **99.61% classification accuracy** on the collected kitchen activity dataset.
- **99.29% accuracy** on the UORED-VAFCLS dataset, as documented by the official project page.
- Real-time activity predictions matched ground truth more than **89% of the time** in the paper's recorded demonstration.

These are results reported by the paper and project documentation, not new evaluations run for this repository.

## Author Contribution

The original paper states that **Yinan Pei, Shaohua Hu, and Junjia Cao contributed equally**. Junjia Cao confirmed contributions to model and code implementation, data processing and experiments, paper writing and revision, and project coordination and presentation. These are contributions within a co-first-author collaboration, not a claim of sole ownership of the model or dataset.

## Paper, Code, and Evidence

- **Official paper:** [DOI link](https://doi.org/10.1109/icc52391.2025.11161477)
- **Code and dataset:** [Canberra1111/Kitchen-Micro-Doppler-HAR-with-OD-GCResNet](https://github.com/Canberra1111/Kitchen-Micro-Doppler-HAR-with-OD-GCResNet)
- **PDF in this repository:** Not included.
- **Local implementation archive:** Model implementation and training/evaluation code are preserved locally. Two H5 checkpoints, approximately 109 MB each, are not uploaded because they exceed GitHub's single-file limit. Approximately 108 GB of datasets is also excluded; use the official project data link instead.
- **Evidence excluded:** Locally generated ablation plots that used `simulate_other_model_acc/loss` rather than actual training logs. Those plots are not treated as valid experimental evidence.
