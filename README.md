# AI-ML-NLP-TextGeneration Repository

This repository contains two Jupyter notebook projects focused on text summarization using various NLP techniques.

## Project 1: Text Summarization using Hugging Face Transformers

- **Notebook:** [Text-Summarization-using-HuggingFace-BERT-T5-GPT2-XLNet.ipynb](https://colab.research.google.com/github/vrajeshtrichy/AI-ML-NLP-TextSummarization/blob/master/Text-Summarization-using-HuggingFace-BERT-T5-GPT2-XLNet/Text-Summarization-using-HuggingFace-BERT-T5-GPT2-XLNet.ipynb)

### Data

The data used for this project is sourced from the file `SachinEssay.txt`. This file contains the text of an essay that we aim to summarize using different NLP models.

### Models

- **BERT (Extractive Summarizer):** Utilizes the Hugging Face Transformers library for extractive summarization.
- **GPT-2:** Employs the Hugging Face Transformers library for abstractive summarization.
- **XLNet:** Uses the Hugging Face Transformers library for abstractive summarization.
- **T5:** Utilizes the T5 model from the Transformers library for abstractive summarization.

### Training

The models used in this project are pretrained and fine-tuned models, and the training details are not covered in this repository. You can refer to the respective documentation for training information for these models.

### Results

The notebook provides examples of summarization using the mentioned models. It loads the essay from the file, summarizes it using each model, and prints the results. You can explore the notebook for detailed examples and results.

## Project 2: Text Summarization using Tf-Idf

- **Notebook:** [Text-Summarization-using-Tf-Idf.ipynb](https://colab.research.google.com/github/vrajeshtrichy/AI-ML-NLP-TextSummarization/blob/master/Text-Summarization-using-ScikitLearn-Tf-Idf/Text-Summarization-using-Tf-Idf.ipynb)

### Data

The data used for this project is sourced from the file `SachinEssay.txt`. This file contains the text of an essay that we aim to summarize using the Tf-Idf (Term Frequency-Inverse Document Frequency) approach.

### Models

The main technique used in this project is the Tf-Idf approach for extractive summarization. It involves the following steps:

- Cleaning punctuations from the text.
- Calculating the Tf-Idf scores for each word in the essay.
- Building a similarity matrix between sentences using these scores.
- Ranking sentences based on similarity using the PageRank algorithm.
- Selecting the top-ranked sentences to generate the summary.

### Training

The Tf-Idf approach doesn't require training as it's based on the frequency of words in the document.

### Results

The notebook provides an implementation of text summarization using the Tf-Idf approach. It reads the essay from the file, calculates sentence similarity using Tf-Idf, ranks sentences to generate a summary, and prints the results. You can explore the notebook for detailed examples and results.

---

Feel free to explore each project's notebook for in-depth information and usage examples. If you have any questions or suggestions, please don't hesitate to open an issue or reach out to the repository owner.
