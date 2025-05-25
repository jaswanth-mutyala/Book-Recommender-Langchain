# 📚 Book Recommender with LangChain & Gradio

A smart book recommendation system built using **LangChain**, **Hugging Face Transformers**, **Chroma vector DB**, and **Gradio**. This project allows users to input a book they love and get intelligent recommendations based on semantic similarity.

## 🧠 Tech Stack

- **LangChain**: For chaining LLM-compatible components
- **HuggingFaceEmbeddings**: For generating vector embeddings of text
- **Chroma DB**: For storing and querying vectorized data
- **Gradio**: For building the interactive dashboard
- **Pandas**: For data manipulation and processing

## 📁 Dataset
This project uses the **7K Books with Metadata** dataset from Kaggle:

🔗 [Kaggle Dataset](https://www.kaggle.com/datasets/dylanjcastillo/7k-books-with-metadata)

You can load the dataset programmatically using `kagglehub`:

## 🔧 Setup Instructions

1. **Clone the repo**
   ```bash
   git clone https://github.com/jaswanth-mutyala/Book-Recommender-Langchain.git
   cd Book-Recommender-Langchain
