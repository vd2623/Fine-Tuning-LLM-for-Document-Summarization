# Fine-Tuning-LLM-for-Document-Summarization

## Overview
This project fine-tunes a `T5 Transformer` model to summarize legal and research documents.

## Features
- Uses `Hugging Face` Transformers (`T5`)
- Fine-tuned on `CNN/DailyMail` dataset
- Optimized for `document summarization`

## Installation
```bash
pip install transformers datasets torch

## training
python train_summarization.py

## Future Enhancements
Improve model performance with domain-specific datasets
Deploy as a REST API using FastAPI
