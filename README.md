# End-to-End Advanced RAG Project using Open Source LLM Models such as Mistral with Groq Inferencing Engine

This project leverages Retrieval-Augmented Generation (RAG) with advanced, open-source Large Language Models (LLMs), specifically Mistral, for efficient inferencing on the Groq hardware platform. The RAG system combines the power of contextually relevant information retrieval with language model generation to create accurate, detailed responses.

## Project Objectives

- **Develop a robust RAG pipeline** that can retrieve and generate contextually rich responses.
- **Implement Mistral** with Groq to ensure efficient, scalable inferencing for low latency.
- **Leverage Ollama embeddings** for optimized text representation and retrieval performance.
- **Create a user-friendly interface** using Streamlit to allow seamless interaction with the RAG pipeline.

## Key Features

1. **Retrieval-Augmented Generation (RAG) Pipeline**  
   - Combines information retrieval with Mistral for enhanced response accuracy.
   - Uses a knowledge base to retrieve relevant content before generating responses.

2. **Groq Inferencing Engine Optimization**  
   - Optimized for handling LLM workloads with low latency and high throughput.
   - Integrated with Mistral to balance efficiency and response quality.

3. **Advanced Embedding and Document Retrieval**  
   - **Ollama Embeddings** for generating high-quality, dense vectors for document retrieval.
   - **WebBasedLoader for Data Extraction**: Extracted information from the LangSmith website using WebBasedLoader, enhancing the knowledge base with domain-specific content.
  
4. **Interactive Web Application with Streamlit**  
   - Provides a Streamlit-based front end for user interactions.
   - Allows users to enter queries, view retrieved context, and see generated responses seamlessly.

## Architecture Overview

1. **Data Extraction and Pre-Processing**  
   - Extracted domain-specific content from the LangSmith website using WebBasedLoader.
   - Applied pre-processing steps such as text cleaning, tokenization, and embedding generation.

2. **Embedding and Vector Storage**  
   - Utilized Ollama embeddings to generate dense representations of the knowledge base.
   - Stored these embeddings in a vector database, enhancing retrieval speed and accuracy.

3. **Contextual Retrieval and RAG Pipeline**  
   - Retrieves relevant documents based on input queries.
   - Uses retrieved documents as context for Mistral’s generation process.

4. **LLM Inferencing with Groq**  
   - Leverages Groq’s optimized hardware for low-latency and high-performance model inferencing.
   - Processes contextual input from the RAG pipeline to generate accurate responses.

5. **Streamlit Web Application**  
   - Provides a user interface for querying and viewing responses.
   - Displays retrieved context along with Mistral’s generated output.

## Setup and Installation

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/hmairaj94/RAG-Groq-Mistral.git
   cd RAG-Groq-Mistral
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

### Running the Project

To start the RAG pipeline and launch the Streamlit application:
   ```bash
   streamlit run app.py
   ```

## Evaluation and Metrics

1. **Inference Speed**: Compare Groq vs. other hardware for model efficiency.
2. **Accuracy and Relevance**: Evaluate response relevance using metrics like BLEU, ROUGE.
3. **User Latency**: Measure query response time for real-time applications.

## Potential Use Cases

- **Customer Support**: Real-time, accurate responses with contextual relevance.
- **Knowledge Management**: Fast retrieval and generation from extensive knowledge bases.
- **Content Creation**: Assists in creating summaries or generating answers from documents.

## Contributing

Contributions are welcome! Please create an issue or a pull request for proposed changes.


## Screenshot

![Screenshot (64)](https://github.com/user-attachments/assets/7ae570e9-1ce3-4e91-84f6-b3c6e077a1ae)

