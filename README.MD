# Gemma Czech Adaptation

This repository focuses on adapting Gemma, a pre-trained language model, for the Czech language.
We will compile our own datasets from Hugging Face's datasets containing Czech data to fine-tune the model effectively.

This repository serves as our submission for the [Gemma Language Model Tuning Competition](https://www.kaggle.com/competitions/gemma-language-tuning/overview), where we aim to optimize Gemma's performance on Czech language tasks.

## Objectives
- Fine-tune Gemma to improve its understanding of the Czech language.
- Evaluate the model's performance on tasks like translation, sentiment analysis, and natural language generation in Czech.
- Deploy the fine-tuned model for practical applications.

## Repository Structure
- **notebooks/**: Contains Jupyter notebooks for data preprocessing, model training, evaluation, and analysis.
- **data/**: Directory for datasets used in training and evaluation.
- **models/**: Directory to save trained models and checkpoints.
- **scripts/**: Python scripts for repetitive tasks like data cleaning and format conversion.

## Requirements
- Python 3.10+
- Jupyter Notebook
- Transformers library (Hugging Face)
- PyTorch or TensorFlow
- scikit-learn
- pandas
- numpy
- matplotlib / seaborn

## Installation
1. Clone the repository:
    ```bash
    git clone https://github.com/quant-eagle/gemma-global-competition.git
    cd gemma-global-competition
    ```
2. Setup Poetry
    For more information see [here](https://python-poetry.org/docs/getting-started/)

3. Install the required packages:
    ```bash
    poetry shell
    poetry install
    ```
4. Compile datasets from Hugging Face and place them in the `data/` directory.

## Usage
- Run the initial notebook in `notebooks/` to preprocess the dataset and begin fine-tuning.
- Monitor training progress and evaluate results on Czech-specific tasks.
