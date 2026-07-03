# NLP HF Tokenizers Resources

This repository contains a Jupyter notebook demonstrating Hugging Face tokenizers and model input preparation for NLP tasks.

## Included Notebook

- `hf_tokenizer.ipynb`
  - Shows how to use `DistilBertTokenizer` and `AutoTokenizer`
  - Demonstrates tokenization, decoding, and special token IDs
  - Explains padding, truncation, and batching of text inputs
  - Includes a sentiment classification example using `AutoModelForSequenceClassification`
  - Compares manual model tokenization to the Hugging Face `pipeline` API

## Requirements

- Python 3.8+
- `transformers`
- `torch`

## Installation

```bash
pip install transformers torch
```

## Usage

1. Open `hf_tokenizer.ipynb` in Jupyter or VS Code.
2. Run the notebook cells sequentially.
3. Observe how text is converted to token IDs and passed into a model.

## Notes

- The notebook uses the `distilbert-base-uncased-finetuned-sst-2-english` sentiment model and `bert-base-uncased` tokenizer.
- It is useful for learning how Hugging Face tokenizers prepare inputs before model inference.

