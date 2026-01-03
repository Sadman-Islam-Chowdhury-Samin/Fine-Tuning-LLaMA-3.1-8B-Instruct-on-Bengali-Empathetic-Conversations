# Fine-Tuning-LLaMA-3.1-8B-Instruct-on-Bengali-Empathetic-Conversations

This repository contains code to fine-tune LLaMA 3.1-8B-Instruct on a Bengali empathetic conversation dataset using parameter-efficient methods (Unsloth/LoRA). The goal is to generate empathetic responses in Bengali while efficiently using limited GPU resources.

Features:

1 .Dataset preprocessing and tokenization for full-sequence LLaMA training
2 .Parameter-efficient fine-tuning using Unsloth (memory-friendly) or LoRA
3. Evaluation metrics: Perplexity, BLEU, ROUGE
4. Human evaluation generation for qualitative assessment
5. Logging of training and evaluation metrics for reproducibility

Getting Started:

1. Clone the repository
2. Install dependencies: transformers, unsloth, datasets, evaluate, accelerate, bitsandbytes
3. Add your HuggingFace token for model access
4.Run the notebook to preprocess data, fine-tune the model, and evaluate

Results:

1. Trained model generates empathetic Bengali responses
2. Metrics and sample outputs are saved for analysis

Notes:

1. Designed to run efficiently on Kaggle free GPUs
2. Supports gradient checkpointing and mixed precision for large model training
