# An improved RCBT model and its application to sentiment analysis of movie comments

**IEEE ISPCEM 2024 · Sole author: Cao Junjia**

[DOI: 10.1109/ISPCEM64498.2024.00180](https://doi.org/10.1109/ISPCEM64498.2024.00180) · Pages 1016–1023

## Overview

This paper presents an improved **RoBERTa-CNN-BiLSTM-Transformers (RCBT)** architecture for sentiment analysis of social-media comments. It combines pretrained contextual representations with local pattern extraction and long-range dependency modelling.

## Method

- **RoBERTa** for contextual text representation.
- **CNN** for local phrase and word-combination features.
- **BiLSTM** for sequential dependencies.
- **Transformer self-attention** for longer-range relationships and more efficient parallel computation.

The model is evaluated on the IMDB movie-review dataset and compared with other sentiment-classification approaches.

## Reported Results

The paper reports precision, recall, accuracy, and F1 of **99.80% on the training set**. On the test set, it reports **93.46% precision, 93.29% recall, 93.40% accuracy, and 93.37% F1**, the highest ACC and F1 among the compared models.

A recovered experiment log matches the training-loss values discussed in the paper and records **93.40% best test accuracy** and **99.80% final-epoch training accuracy**. That log does not contain the reported test precision, recall, or F1 values. A complete training run has **not been reproduced for this repository**.

## Author Contribution

Cao Junjia is the **sole author** of the paper and is responsible for the model design, experimental work, analysis, and manuscript.

## Paper and Code

- **Official paper:** [DOI link](https://doi.org/10.1109/ISPCEM64498.2024.00180)
- **Experiment archive:** Source code and logs have been recovered locally. They are not publicly released while upstream licensing, model-structure consistency, and reproducibility issues are reviewed.
- **Upstream attribution:** The recovered experiment tree extends [BeiCunNan/sentiment_analysis_Imdb](https://github.com/BeiCunNan/sentiment_analysis_Imdb); it is not presented as a from-scratch implementation.
- **PDF in this repository:** Not included. The IEEE Xplore download carries usage restrictions, so this page links to the official record rather than republishing that file.
