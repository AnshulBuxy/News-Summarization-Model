# News Summarization Model

A deep learning-based project designed to generate concise and coherent summaries of news articles. This project leverages state-of-the-art natural language processing (NLP) models to process lengthy news articles into easy-to-read summaries, making information more accessible and manageable.

---

## Features

- **Automated Summarization**: Generates a summary of any given news article.
- **State-of-the-Art NLP Model**: Built using the Pegasus transformer model, specifically fine-tuned for summarization tasks.
- **Streamlined Workflow**: Accepts text input or uploads news articles for processing.
- **Efficient and Scalable**: Handles large datasets with ease, making it suitable for real-world applications.

---

## Technologies Used

- **Python**: The primary programming language used for implementation.
- **Transformers Library**: Utilized for the Pegasus model, enabling advanced summarization capabilities.
- **Hugging Face**: Framework for pre-trained model access and fine-tuning.
- **Streamlit**: (Optional) For building an interactive user interface (if implemented).

---

## How It Works

1. **Data Input**: Input can be provided in the form of plain text or a URL pointing to a news article.
2. **Preprocessing**: The text is tokenized and prepared for model input.
3. **Summarization**: The Pegasus model generates a concise summary of the input article.

---

## Setup and Installation

Follow these steps to set up the project on your local machine:

1. Clone the repository:
   ```bash
   git clone https://github.com/AnshulBuxy/News-Summarization-Model.git
   cd News-Summarization-Model
2. ```bash
   pip install -r requirements.txt
   pythob main.py

---
## Model Information
### **Base Model:** Pegasus (Fine-Tuned)
### **Dataset:** The model is fine-tuned using a Kaggle dataset containing various news articles.
