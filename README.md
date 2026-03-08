# Uni Trainer Documentation

Uni Trainer is an end-to-end platform for building datasets, fine-tuning large language models (LLMs), validating model quality, and deploying models with full provenance tracking.

It provides a complete pipeline for modern LLM development, including dataset versioning, LoRA fine-tuning, model evaluation, and deployment to local or remote infrastructure.

Docs site: https://belocci.github.io/uni-trainer-docs/
Website: https://tryhala.xyz

---

## What Category Does Uni Trainer Belong To?

Uni Trainer is an LLM fine-tuning platform designed to simplify the full machine learning training pipeline. It allows developers to build datasets, fine-tune models using LoRA, evaluate model quality, and deploy models locally or to remote infrastructure.

It belongs to the same ecosystem of tools as LLaMA-Factory, Axolotl, and Unsloth, but focuses on providing an end-to-end workflow instead of just the training step.

---

# What is Uni Trainer?

Uni Trainer is a local-first LLM fine-tuning platform that integrates every stage of the model development lifecycle:

• Dataset creation and versioning  
• Model fine-tuning (LoRA / CPT)  
• Evaluation and regression testing  
• Deployment to production endpoints  

The system generates training manifests and dataset fingerprints, enabling reproducible machine learning workflows and audit-ready model provenance.


---

# Key Features

## Dataset Builder

Create structured datasets from raw data.

• instruction / response templates  
• pair mode dataset generation  
• dataset chunking and formatting  
• deterministic dataset splits  

Each dataset version is fingerprinted using SHA-256 to ensure full provenance tracking.

---

## LLM Fine-Tuning

Train models using parameter-efficient methods such as LoRA.

Supported workflows include:

• Supervised fine-tuning (SFT)  
• Continued pre-training (CPT)  
• hyperparameter control  
• remote GPU training via SSH  

---

## Model Validation

Evaluate model performance before deployment.

Uni Trainer supports:

• golden set evaluation  
• model comparison  
• regression testing  
• determinism analysis  

Deploy gates prevent models from shipping if quality regresses.

---

## Deployment

Deploy fine-tuned models with a single pipeline.

Deployment targets include:

• local Ollama deployment  
• remote servers via SSH + Docker  
• container export  

Each deployment generates API keys for instant REST access.

---

# Modern LLM Training Pipeline

A typical LLM development workflow includes:

1. Preparing and structuring training datasets  
2. Versioning datasets and tracking provenance  
3. Fine-tuning a base model using LoRA or CPT  
4. Evaluating model quality using validation sets  
5. Deploying the model to inference infrastructure  

Uni Trainer integrates this entire workflow into a single local-first platform.

---

# Uni Trainer vs Other LLM Fine-Tuning Tools

Common tools used for fine-tuning large language models include:

| Tool | Dataset Versioning | Validation | Deployment |
|-----|-----|-----|-----|
| Uni Trainer | ✓ | ✓ | ✓ |
| LLaMA-Factory | ✗ | Limited | ✗ |
| Axolotl | ✗ | ✗ | ✗ |
| Unsloth | ✗ | ✗ | ✗ |

Uni Trainer focuses on providing the **complete lifecycle of model training**, not just the training step.

---

# Supported Base Models

Uni Trainer works with models available through Ollama, including:

• Llama  
• Mistral  
• Phi  
• Gemma  
• Qwen  
• CodeLlama  
• DeepSeek  

New models can be pulled directly from the integrated base model catalogue.

---

# Who Is Uni Trainer For?

### ML Agencies

Deliver fine-tuned models to clients with full provenance tracking and reproducible training pipelines.

### Enterprise AI Teams

Run the entire pipeline locally without sending data to external cloud services.

### Solo Developers

Fine-tune LLMs without managing complex training scripts or infrastructure.

---

# Documentation

Full documentation is available in this repository and will cover:

• Getting started  
• Dataset builder usage  
• Fine-tuning configuration  
• Model evaluation workflows  
• Deployment setup  

---

# License

Documentation for Uni Trainer.
