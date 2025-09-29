# Infosys_Springboard
Milestone 1: Text Summarization &amp; Paraphrasing using T5, BART, and Pegasus

Overview:

This project demonstrates text summarization and paraphrasing using pretrained transformer models from Hugging Face. Input text is taken from two online .txt files, processed, and then summarized and paraphrased. The outputs are compared using visualizations.

Objectives:

Load and clean input text from two online .txt files.

Implement summarization using:

T5 Base

BART Base

Pegasus XSUM

Implement paraphrasing using:

T5 Paraphrase

Pegasus (adapted for paraphrasing)

Compare model outputs and illustrate results with visualizations.

Methodology

Data Preparation: Text fetched from Project Gutenberg URLs and cleaned.

Summarization: Applied T5, BART, and Pegasus models.

Paraphrasing: Applied T5 and Pegasus models.

Comparison: Compared outputs by word length and visualized results using bar charts and heatmaps.

Results

T5 generated concise and well-balanced summaries.

BART produced longer, more detailed summaries.

Pegasus was highly abstractive, sometimes omitting details.

T5 paraphrasing was effective in producing natural variations.

Pegasus paraphrasing worked but was less reliable compared to T5.

Tools and Libraries:

Python, Google Colab

Hugging Face Transformers

Matplotlib, Seaborn

References:
Hugging Face Models: https://huggingface.co/models

Project Gutenberg: https://www.gutenberg.org/

Hugging Face Models: https://huggingface.co/models

Project Gutenberg: https://www.gutenberg.org/
