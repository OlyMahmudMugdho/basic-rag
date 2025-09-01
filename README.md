# Basic Retrieval-Augmented Generation (RAG)
This is a basic RAG system that can be used to ask questions to GPT on custom data (PDF).

## How to run
1. Install the required packages:
   ```bash
   pip install -r requirements.txt
   ```
2. Set the environment variables
    ```bash
    export OPENAI_API_KEY="your_openai_api_key"
    export OPENAI_BASE_URI="your_openai_base_uri"
    ```

3. Store the embeddings:
    ```bash
    python store.py
    ```

4. Run the app:
    ```bash
    python app.py
    ```