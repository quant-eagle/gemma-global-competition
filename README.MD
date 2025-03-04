# Gemma Czech Adaptation

This repository focuses on adapting Gemma, a pre-trained language model, for the Czech language.
We will compile our own datasets from Hugging Face's datasets containing Czech data to fine-tune the model effectively.

This repository serves as our submission for the [Gemma Language Model Tuning Competition](https://www.kaggle.com/competitions/gemma-language-tuning/overview), where we aim to optimize Gemma's performance on Czech language tasks.

Take this repository's implementation as a proof of concept, for better results we'd need more structured data, optimize the hyperparams and scale the training which will require significantly more resources.

There's a still a possibility for more efficient fine tune (training) using RL techniques such PPO, TRPO, GRPO or alignment techniques such as DPO and maybe some transfer learning. 

## Objectives
- Fine-tune Gemma to improve its understanding of the Czech language.
- Evaluate the model's performance on tasks like translation, sentiment analysis, and natural language generation in Czech.
- Deploy the fine-tuned model for practical applications.

## Repository Structure
- **data/**: Directory for datasets used in training and evaluation.
- **models/**: Directory to save trained models and checkpoints.

## Usage
You can either run the poc (proof of concept) notebook or the final submission one.
Then monitor training progress and evaluate results on Czech-specific tasks.
