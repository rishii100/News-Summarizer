# News Summarizer

## Overview

News Summarizer is an abstractive text summarization project leveraging the T5 transformer model. Built in a Jupyter Notebook, it efficiently condenses news articles, offering concise and informative summaries. The implementation includes the T5 model fine-tuned for news summarization. Users can input news articles and witness the model's generation of abstractive summaries. With clear instructions and detailed steps, the project provides an accessible and insightful tool for extracting key information from news content. Explore the power of transformer models in natural language processing with this easy-to-use news summarization solution.

## Model Architecture

![Model Architecture](https://github.com/rishii100/News-Summarizer/assets/98979613/537de912-1739-491d-9d1c-0c8f7c5843a1)


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

![Accuracy](https://github.com/rishii100/News-Summarizer/assets/98979613/4c70b3ce-eb5a-4452-b462-0c414bdf9d0a)

( Accuracy= 97% )

## User Flow
![user flow](https://github.com/rishii100/News-Summarizer/assets/98979613/de3255c5-ea83-4e88-9f93-7bc01ac2f1fb)

## Contributors

- [Aneerban Saha](https://github.com/rishii100)
- [K. Krishna Koushika](https://github.com/koushika6)
- [Akshita Jain](https://github.com/Akshita132)

## License

This project is licensed under the [MIT License](LICENSE) file.

## Acknowledgments

- Special thanks to the [Hugging Face](https://huggingface.co/) community for providing the transformer models.
- Inspired by the work in abstractive text summarization.

