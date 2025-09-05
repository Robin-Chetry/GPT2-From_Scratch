# GPT2-From_Scratch

A project to implement GPT-2 from the ground up in Jupyter Notebooks, following the step-by-step approach outlined in *Build a Large Language Model (From Scratch)* by Sebastian Raschka.

## Overview

This repository guides you through building a GPT-2-style language model entirely from scratch—without relying on high-level LLM libraries. You’ll learn the nuts and bolts of:

- Tokenization and dataset preparation  
- Self-attention and multi-head attention mechanisms  
- Transformer block implementation  
- Pretraining on raw text data  

The project mirrors the structure of Raschka’s methodology to deepen conceptual understanding by building components yourself.

## Table of Contents

- `data/` — Raw text corpora and processed datasets for model training  
- `src/` — Core implementation scripts and notebooks:
  - `gpt2_custom.ipynb` — Building a Byte Pair Encoding (BPE) tokenizer  

- `experiments/` — tokenizer.ipynb, understanding_attention_mechanism.ipynb,  LLM_ARCHITECTURE.ipynb.
- `README.md` — This overview and usage guide  
- `LICENSE` — MIT License for this repository  

## Prerequisites

- **Python 3.8+**  
- **PyTorch**  
- Basic understanding of Python and neural networks  
- Recommended: GPU support for efficient model training

### Setup

```bash
git clone https://github.com/Robin-Chetry/GPT2-From_Scratch.git
cd GPT2-From_Scratch
