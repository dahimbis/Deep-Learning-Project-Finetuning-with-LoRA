# Project  – Text Classification Using LoRA

This project fine-tunes a transformer model on the AG News dataset using Low-Rank Adaptation (LoRA). It demonstrates how to adapt large language models efficiently using fewer trainable parameters.

## Key Features
- Applied LoRA for parameter-efficient finetuning
- Used Hugging Face Transformers and PEFT
- Classified AG News into 4 categories with high accuracy

## Dataset
- AG News (via Hugging Face Datasets)

## Requirements
- Python
- transformers
- peft
- accelerate

## How to Run
```bash
pip install transformers datasets peft accelerate
jupyter notebook LoRA_Text_Classification.ipynb
