
# Hebrew Sentence BERT

This repository provides access to the final project in the NLP course at IDC, 2024. The project focuses on enhancing NLP capabilities for Hebrew by fine-tuning a Sentence BERT (SBERT) model using the Hebrew Natural Language Inference (NLI) dataset. The trained models are evaluated on Semantic Textual Similarity (STS) and Hebrew QA tasks.

## Project Overview

Natural Language Processing (NLP) has seen significant advancements with models like BERT. However, resources and tools for low-resource languages like Hebrew are still developing. This project aims to improve Hebrew NLP by fine-tuning Sentence BERT models using a newly released Hebrew NLI dataset. The fine-tuned models are tested on tasks such as semantic textual similarity (STS) and information retrieval.

Key components of the project include:
- Fine-tuning SBERT using pre-trained models like AlephBERT, mBERT, and DictaBERT.
- Evaluating the models on the Hebrew STS benchmark and a Hebrew QA dataset.
- Experimenting with different training strategies, including softmax classification and Multiple Negatives Ranking Loss (MNR) using triplets.

## Access the Colab Notebook

You can access and run the Colab notebook for this project using the following link:

[Open the Colab Notebook](https://colab.research.google.com/drive/1Ns1NKXu0xdpkyG9FBdLvZ5lAyAcm7cpb?usp=sharing)

## Project Report

For a detailed explanation of the project, including the methodology, experiments, and results, you can access the full project report here:

[Project Report](https://drive.google.com/file/d/16txG8kNw3rzgxxao_2YoHAlT3U41glC-/view?usp=sharing)

## Data

The datasets used in this project include:
- **Hebrew NLI Dataset**: Used for training the SBERT model.
- **Hebrew STS Test Dataset**: Used for evaluating semantic textual similarity.
- **Hebrew QA Dataset**: Used for evaluating question-answering capabilities.

The datasets are stored on Google Drive and can be downloaded directly within the notebook.

## Evaluation and Results

The evaluation includes:
- **Semantic Textual Similarity (STS)**: Comparing model-generated similarity scores with human-annotated scores.
- **Hebrew QA**: Matching questions with correct answers using sentence embeddings.

Results are documented in the notebook, highlighting the performance of different models and training strategies.

## Future Work

Future improvements could include:
- Refining the dataset using improved translation and paraphrasing techniques.
- Exploring additional training strategies to enhance performance on the Hebrew QA task.
- Extending the approach to other low-resource languages.
