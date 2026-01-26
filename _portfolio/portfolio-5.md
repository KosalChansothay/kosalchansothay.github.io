---
title: "LLM Fine-tuning: Qwen3 for Tax Q&A"
excerpt: "Fine-tuned Qwen3 4B model using LoRA and quantization for Khmer tax-related question answering"
collection: portfolio
date: 2025-12-01
---

## Project Overview

Research internship project at IDRI/CADT focusing on fine-tuning large language models for domain-specific question answering in the tax domain.

### Key Contributions

- **Model Selection**: Worked with Qwen3 4B-parameter model from Alibaba Group
- **Efficient Fine-tuning**: Implemented Low Rank Adaptation (LoRA) technique for parameter-efficient fine-tuning
- **Quantization**: Applied 4-bit integer quantization for resource-efficient deployment
- **Data Processing**: Processed dataset of 1,690 tax-related Q&A pairs extracted from GDT website PDFs
- **Resource Optimization**: Successfully deployed the fine-tuned model with minimal resources (Tesla T4 on Google Colab)

### Technologies Used

- Python
- PyTorch
- Hugging Face Transformers
- PEFT (Parameter-Efficient Fine-Tuning)
- bitsandbytes (Quantization)

### Resources

- [Slide Deck](https://kosalchansothay.github.io/Internship_Defense/#1)
