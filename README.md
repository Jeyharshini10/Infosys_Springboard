Project Overview:
This project explores text summarization and paraphrasing using powerful transformer-based models from Hugging Face. The idea is simple: we take text from two online sources, clean it up, and then run it through different models to see how they summarize and rephrase the content. Finally, we compare the results and visualize the differences.

Objectives:
Load and clean input text from two online .txt files.

Perform summarization with:

T5 Base
BART Base
Pegasus XSUM

Perform paraphrasing with:
T5 Paraphrase
Pegasus (adapted for paraphrasing)
Compare the outputs of different models and present the results with visualizations.

Methodology:
Data Preparation – Text was fetched from Project Gutenberg and preprocessed (removing unwanted symbols and formatting).
Summarization – Applied T5, BART, and Pegasus to condense the input text.
Paraphrasing – Used T5 and Pegasus to generate alternative phrasings of the same content.
Comparison & Visualization – Compared the model outputs in terms of length and style, and illustrated the results using bar charts and heatmaps.

Results:
T5 created short and balanced summaries.
BART gave longer, more detailed summaries.
Pegasus produced highly abstractive summaries, sometimes leaving out specific details.
T5 Paraphrase generated natural and fluent variations.
Pegasus Paraphrase worked but was less consistent compared to T5.

Tools & Libraries:
Python (Google Colab)
Hugging Face Transformers
Matplotlib & Seaborn for visualization

References:
Hugging Face Models: https://huggingface.co/models
Project Gutenberg: https://www.gutenberg.org/
