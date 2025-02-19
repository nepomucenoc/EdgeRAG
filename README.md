# Lightweight RAG Demo with Simulated LoRA & TinyLLM Optimizations

This project is a simple Python demonstration of a Retrieval-Augmented Generation (RAG) pipeline that integrates several advanced AI concepts in a lightweight setup. It simulates the application of:

- **LoRA (Low-Rank Adaptation):** A technique to fine-tune large language models efficiently by adapting only a subset of parameters.
- **TinyLLM Optimization:** Methods such as quantization and pruning to reduce model size and computational overhead for resource-constrained environments.
- **Transformer Embeddings:** Utilizes the RAG model (which incorporates transformer-based architectures like BERT, GPT, and LLaMA) to generate context-aware responses.
- **RAG (Retrieval-Augmented Generation):** Combines document retrieval with generation, using a dummy dataset for demonstration purposes.
- **Security Guardrails:** A simple mechanism to filter and secure the model's output.

## Features

- **Simulated Fine-Tuning:** Applies a placeholder for LoRA-based adjustments.
- **Model Optimization:** Simulates TinyLLM techniques to prepare the model for low-resource environments.
- **RAG-Based Response Generation:** Retrieves context and generates a response based on a query.
- **Security Filtering:** Ensures responses adhere to basic security policies.

## Requirements

- Python 3.7 or higher
- PyTorch (imported as `torch`)
- Hugging Face Transformers (`pip install transformers`)
- FAISS (install via `pip install faiss-cpu` for CPU or `pip install faiss-gpu` for GPU support)

## Usage

1. **Install Dependencies:**  
   ```bash
   pip install torch transformers faiss-cpu

