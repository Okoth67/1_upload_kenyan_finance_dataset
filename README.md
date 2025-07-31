# Kenyan Finance Q&A Dataset

This repository contains curated, locally accurate instruction–response pairs focused on common personal finance and investment questions asked by Kenyans in 2025.

The dataset is stored in `.jsonl` format and is designed for use in training or fine-tuning instruction-based language models such as Mistral, LLaMA, or GPT-style models.

## 📘 Notebook(s)

### 1. `01_upload_kenyan_finance_dataset.ipynb`
This notebook loads and previews the dataset:
- Loads the `.jsonl` file line by line.
- Parses it into a Python list of dictionaries.
- Handles empty or invalid lines gracefully.
- Prints the first few entries for inspection.

## 📁 Dataset

- **File**: `01_upload_kenyan_finance_dataset.jsonl`
- **Format**: JSONL (`{"instruction": "...", "response": "..."}` per line)
- **Language**: English (Kenyan context)
- **Size**: 10 instruction–response pairs (expandable)

## 🧠 Topics Covered

- Money market funds
- Government bonds
- SACCOs
- Stock market investing
- Real estate
- Budgeting in Nairobi
- Pensions & retirement
- Insurance
- Loans & inflation
- Small business support

## 🔧 Future Work

- Fine-tuning LLMs on this dataset
- Adding Alpaca/ChatML formats
- Expanding to 100+ Q&A pairs
- Uploading to Hugging Face Datasets

