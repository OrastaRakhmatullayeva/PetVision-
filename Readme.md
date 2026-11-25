
# PetVision — Pet Breed Classification

A computer vision project exploring three approaches to 
pet breed classification using CLIP and Vision Transformers.

## Dataset

Oxford-IIIT Pet Dataset — 7,349 images across 37 cat and dog breeds.

## Methodology

- Zero-shot classification with CLIP
- Feature extraction with ViT and Logistic Regression
- Fine-tuning a pretrained Vision Transformer

## Results

| Model | Accuracy | Test Images |
|---|---:|---:|
| CLIP Zero-shot | 83.80% | 500 |
| ViT + Logistic Regression | 92.10% | 3,669 |
| Fine-tuned ViT | 92.12% | 3,669 |

CLIP achieved 99.80% accuracy on binary cat vs. dog classification.

The models were evaluated on different test set sizes, 
which limits direct comparison.

## Tech Stack

Python, PyTorch, Hugging Face, Scikit-learn, CLIP, ViT

## How to Run

Open the notebook in Google Colab, enable GPU, and run all cells.
