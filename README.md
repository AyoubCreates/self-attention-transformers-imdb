# Self-Attention Transformer for Text Classification

## Overview
This project implements a Self-Attention Transformer (BERT-based) to classify movie reviews from the IMDB dataset. It demonstrates:
- Model training and evaluation
- Visualization of attention heads
- Prediction on custom sentences

## Dataset
- IMDB dataset: 4000 training samples, 1000 validation samples
- Labels: Positive / Negative

## Results
- Training Loss decreased from 0.3656 to 0.0366
- Validation Accuracy reached 92.4%
- Sample predictions:
    - "This movie was absolutely amazing!" → Positive
    - "This film is boring and a waste of time." → Negative

## Files
- `self_attention.py` → Python code for training and evaluation
- `presentation.pdf` → Project explanation and results visualization
- `requirements.txt` → Python dependencies

## How to Run
1. Install dependencies: `pip install -r requirements.txt`
2. Run: `python self_attention.py`
3. Visualize attention maps using `visualize_attention()` function
