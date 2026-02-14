# Data Mining Project — MovieLens 25M

## Project Goal
Select a dataset and build a semester-long data mining project using course techniques (graph mining / similarity recommenders) and a beyond-course method (matrix factorization).

## Dataset
MovieLens 25M (GroupLens). 25M ratings, 62K movies, 162K users. Released 12/2019.
- Dataset page + README: see citations in notebook.
- Note: This repo does not redistribute raw data; it downloads from the official source.

## Checkpoint 1 Contents
- Candidate dataset comparison (MovieLens vs Amazon vs Yelp)
- EDA: rating distribution, sparsity, popularity/user activity long-tail, temporal patterns
- Course baseline: item-item similarity recommender (cosine)
- Beyond-course: matrix factorization (SVD) baseline

## How to run
Open `Project_Checkpoint_1.ipynb ` in Colab and run all cells.

## Collaboration Declaration
See bottom of the notebook.

## Citations:
- F. Maxwell Harper and Joseph A. Konstan. 2015. The MovieLens Datasets: History and Context. ACM Transactions on Interactive Intelligent Systems (TiiS) 5, 4: 19:1–19:19. https://doi.org/10.1145/2827872
- Justifying recommendations using distantly-labeled reviews and fined-grained aspects. - Jianmo Ni, Jiacheng Li, Julian McAuley Empirical Methods in Natural Language Processing (EMNLP), 2019
- Xiang Zhang, Junbo Zhao, Yann LeCun. Character-level Convolutional Networks for Text Classification. Advances in Neural Information Processing Systems 28 (NIPS 2015).
