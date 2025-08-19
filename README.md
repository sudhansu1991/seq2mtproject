# Seq2 MT Project

This repository contains my previous PhD experiments with **sequence-to-sequence machine translation**  
using PyTorch and TorchText on the German → English Multi30k dataset.

## Contents
- `seq2.ipynb` — Jupyter notebook implementing Seq2Seq with LSTMs
- `requirements.txt` — dependencies to run the notebook
- `.gitignore` — ignore cache, data, and virtual environments
- `LICENSE` — usage terms (MIT)

## Features
- Encoder–decoder with LSTM layers
- Teacher forcing during training
- Trains on **Multi30k** parallel dataset
- Reports training/validation loss and perplexity

## Quick start
Clone the repo and run the notebook:

```bash
git clone https://github.com/sudhansu1991/seq2mtproject.git
cd seq2mtproject

# Create and activate virtual environment
python -m venv .venv
source .venv/bin/activate   # (on Windows use `.venv\Scripts\activate`)

# Install dependencies
pip install -r requirements.txt

# Launch Jupyter
jupyter notebook seq2.ipynb
