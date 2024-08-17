# RAG vs GPT-2 Fine-Tuning

## Project Overview

This project explores the performance of Retrieval-Augmented Generation (RAG) and fine-tuned GPT-2 models on the Stanford Question Answering Dataset (SQuAD). The goal is to compare the results of RAG and GPT-2 in answering questions based on the provided context.

## Code Structure

- `train_gpt2.py`: Contains the code for fine-tuning the GPT-2 model on the SQuAD dataset.
- `setup_rag.py`: Sets up the RAG pipeline and performs comparisons between RAG and GPT-2.

## Data

- The project uses the Stanford Question Answering Dataset (SQuAD) from Hugging Face's `datasets` library.
https://huggingface.co/datasets/rajpurkar/squad

## Installation

To set up the project environment, install the required packages listed in `requirements.txt`.

```bash
pip install -r requirements.txt
