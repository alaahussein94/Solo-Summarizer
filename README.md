# Solo Summarizer

Solo Summarizer is a text summarization system based on fine-tuning Text-to-Text Transformer (T5) models. This project aims to develop an efficient text summarization system that generates coherent and concise summaries for long documents.

## Overview

This project consists of several phases:
1. Fine-tuning the T5-small model on the BillSum dataset and assessing its performance.
2. Fine-tuning and comparing the performance of T5-base and FLAN-T5-base models on the same dataset.
3. Investigating the factors influencing the text summarization capabilities of each model.
4. Exploring methods to improve the performance of the selected model and applying the system to other domains and datasets.

## Usage

Clone this repository, install the requirements, and then run the provided Jupyter Notebook to fine-tune the T5-small model on the BillSum dataset. The notebook will guide you through the entire process of data preprocessing, training, and generating summaries.

## Dependencies

This project uses the following libraries:
- Hugging Face Transformers
- Hugging Face Datasets
- PyTorch
- PyTorch Lightning
- Rouge Score

## Results

The initial fine-tuning of the T5-small model on the BillSum dataset yielded promising results, with a Rouge1 score of 0.1436, Rouge2 score of 0.0514, RougeL score of 0.1188, and RougeLsum score of 0.119 on the evaluation set.

## License

This project is licensed under the MIT License.

## Acknowledgements

- Hugging Face Summarization Tutorial
- Transformer models and the BillSum dataset from the Hugging Face Transformers library and Hugging Face Datasets
- Key papers: T5, FLAN-T5, ROUGE, BLEU, Attention is All You Need