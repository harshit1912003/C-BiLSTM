# Multi-Category Text Classification Project

This repository contains implementations and experiments for a multi-category text classification problem, as part of a Deep Learning assignment (AIL721, Assignment 3).

The project explores various neural network architectures to solve the given classification task.

## Problem Statement

The main goals of this assignment were:
*   Design and implement neural architectures combining CNN and LSTM (or variants).
*   Explore the use of self-attention mechanisms and dynamic meta-embedding.
*   Implement and analyze a Transformer-based text encoding model, considering the effect of the number of encoder blocks and positional embeddings.

## Approaches Explored

Several models and techniques were implemented and evaluated:
*   Custom CBOW word embeddings training.
*   CNN and LSTM (C-LSTM) architecture with custom word embeddings.
*   CNN and Bi-directional LSTM (C-BiLSTM) architecture with custom word embeddings.
*   Integration of a Self-Attention mechanism at the output level of the C-BiLSTM model.
*   Dynamic Meta Word Embeddings combining custom CBOW and pre-trained Word2Vec embeddings.
*   Combining both Meta Embeddings and Self-Attention approaches.
*   Transformer Encoder based models, with experiments on including positional embeddings and varying the number of encoder layers.

## References

Based on papers:
1.  Minyong Shi, Kaixiang Wang, and Chunfang Li. A c-lstm with word embedding model for news text classification. In 2019 IEEE/ACIS 18th International Conference on Computer and Information Science (ICIS), pages 253-257, 2019.
2.  Chunting Zhou, Chonglin Sun, Zhiyuan Liu, and Francis C. M. Lau. A c-lstm neural network for text classification, 2015.
