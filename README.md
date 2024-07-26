# Simple RAG with DSPy & ChromaDB

This project demonstrates a simple Retrieval-Augmented Generation (RAG) pipeline using DSPy and ChromaDB. The pipeline processes a PDF document, stores the text in a ChromaDB collection, and uses a language model to answer questions based on the retrieved context.

## Project Structure

- `pipeline.ipynb`: Jupyter notebook containing the code for the RAG pipeline.
- `data/tesla10K.pdf`: Sample PDF file used for text extraction and processing.

## Setup

1. **Clone the repository:**
    ```sh
    git clone https://github.com/marioyordanoff/dspy
    ```

2. **Create a virtual environment and activate it:**
    ```sh
    python -m venv venv
    source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
    ```

3. **Install the required packages:**
    ```sh
    pip install -r requirements.txt
    ```

4. **Create a `.env` file:**
    ```sh
    touch .env
    ```

5. **Add your environment variables to the `.env` file.** For example:
    ```env
    OPENAI_API_KEY=your_openai_api_key
    ```



## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgements

- [DSPy](https://github.com/dspy-ai/dspy)
- [ChromaDB](https://github.com/chroma-core/chroma)
- [OpenAI](https://openai.com/)