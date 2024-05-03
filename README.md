# Augmented GPT-2 Language Model for Advanced QA System

This repository contains code for a question-answering project utilizing the GPT2 language model fine-tuned on the Stanford Question-answering Dataset (SQuAD). The model is extended to predict answer locations within a given context based on input questions.

## Overview

Question answering (QA) is a natural language processing task where the model generates answers to questions posed on a given context. The Augmented GPT-2 Language Model presented here enhances GPT2's capabilities for QA by fine-tuning it on the SQuAD dataset. This enables the model to predict answer locations within the context based on input questions.

## Features

- **GPT2 Extension**: The model extends GPT2's architecture to predict answer locations.
- **Fine-tuning**: The model is fine-tuned on the SQuAD dataset to adapt it to the QA task.

## Usage

To use the Augmented GPT-2 Language Model for your QA tasks, follow these steps:

1. **Clone Repository**: Clone this repository to your local machine.

2. **Open Jupyter Notebook**: Open the provided Jupyter notebook (`augmented_gpt2_qa.ipynb`) to explore and run the code.

3. **Fine-tuning**: If you wish to fine-tune the model further or experiment with different parameters, you can modify the notebook accordingly.

## Caveats and Future Improvements

- **Limited Training**: Please note that the provided notebook was trained for only 30 minutes due to space and time constraints. However, even with limited training, the accuracy achieved is promising but still not satisfactory.
- **Continual Improvement**: I am actively working on designing fine-tuning strategies to further improve the model's performance, so please keep in mind that this project is still a work in progress. These enhancements will be pushed to the repository in future updates.

## References

- [Stanford Question-answering Dataset (SQuAD)](https://rajpurkar.github.io/SQuAD-explorer/)
- [Transformers Library](https://huggingface.co/transformers/)

Feel free to explore the notebook and adapt it to your specific QA tasks!

