# Getting Started with Uni Trainer

Uni Trainer is an end-to-end platform for building datasets, fine-tuning large language models (LLMs), validating model quality, and deploying models with full provenance tracking.

This guide walks through the basic workflow from installation to deployment.

---

# Installation

Download the latest release from the official website:

https://tryhala.xyz

Install the application and launch Uni Trainer.

The application runs locally and does not require cloud infrastructure.

---

# Core Workflow

A typical Uni Trainer workflow includes five stages:

1. Import or build a dataset
2. Configure model training
3. Fine-tune a base model
4. Validate model performance
5. Deploy the trained model

Uni Trainer integrates this entire pipeline into a single interface.

---

# Supported Base Models

Uni Trainer works with models available through Ollama, including:

- Llama
- Mistral
- Phi
- Gemma
- Qwen
- CodeLlama
- DeepSeek

Base models can be pulled directly through the built-in model catalogue.

---

# Training Methods

Uni Trainer currently supports:

- **Supervised Fine-Tuning (SFT)**
- **Continued Pre-Training (CPT)**
- **LoRA (Low-Rank Adaptation)**

These methods allow efficient training even on limited GPU hardware.

---

# Local and Remote Training

Training can run:

- locally on your machine
- on remote GPU servers via SSH

Remote training allows large models to be trained without moving your dataset off the local system.

---

# Next Steps

Continue with the following guides:

- Dataset Builder
- Fine-Tuning Configuration
- Model Validation
- Deployment
