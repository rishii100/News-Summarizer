# News Summarizer

## Overview

This project is an implementation of a news summarizer using the T5 transformer model. The goal is to generate concise and informative summaries for news articles, providing users with a quick understanding of the content.

## Features

- **T5 Transformer Model:** Utilizes the T5 transformer model, a powerful architecture for sequence-to-sequence tasks.
- **News Article Summarization:** Given a news article, the model generates an abstractive summary.
- **Easy-to-Use Jupyter Notebook:** The implementation is presented in a Jupyter Notebook, making it accessible and easy to understand.

## Prerequisites

- Python 3.7 or higher
- Jupyter Notebook
- PyTorch and Hugging Face Transformers library

## Usage

1. **Clone the Repository:**

    ```
    git clone https://github.com/rishii100/News-Summarizer.git
    ```
    ```
    cd news-summarizer
    ```

2. **Install Dependencies:**

    ```
    pip install -r requirements.txt
    ```

3. **Open the Jupyter Notebook:**

    ```
    jupyter notebook News-Summarizer.ipynb
    ```

4. **Run the Notebook:**

    Execute each cell in the Jupyter Notebook to load the model, input a news article, and generate a summary.

## Model Details

This project employs the T5 transformer model, pretrained on a large corpus of text data. The model is fine-tuned for the specific task of news summarization.

## Results

The model's performance can be evaluated based on the generated summaries.

## License

This project is licensed under the [MIT License](LICENSE) file.

## Acknowledgments

- Special thanks to the [Hugging Face](https://huggingface.co/) community for providing the transformer models.
- Inspired by the work in abstractive text summarization.

