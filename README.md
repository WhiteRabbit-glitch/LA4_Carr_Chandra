# LA4 — Text Classification with Deep Learning

**Course:** CIS 509 — Unstructured Data Analytics
**Author:** Chandra Carr (cgcarr)
**Date:** February 23, 2026

## Overview

This lab assignment uses TF-Keras deep learning models to perform binary sentiment classification on the Yelp Arizona restaurant reviews dataset.

## Models Implemented

| Model | Representation |
|-------|---------------|
| ANN | TF-IDF (5000-d) |
| ANN | Word Embedding (50×300) |
| SimpleRNN | Word Embedding (50×300) |
| LSTM | Word Embedding (50×300) |

## Files

- `LA4_Carr_Chandra.ipynb` — Main notebook with all code and analysis

## Requirements

```
tensorflow
scikit-learn
pandas
numpy
matplotlib
pydot
graphviz
```

## Usage

1. Place `restaurant_reviews_az.csv` in the same directory as the notebook.
2. Open `LA4_Carr_Chandra.ipynb` in VS Code or Jupyter.
3. Run all cells in order.
