# Fine-Tuning Models

Uni Trainer allows you to fine-tune large language models using parameter-efficient training techniques.

Fine-tuning adapts a base model to a specific domain, task, or dataset.

---

# Training Methods

Uni Trainer supports two main training modes:

## Supervised Fine-Tuning (SFT)

SFT trains a model using instruction/response datasets.

This is the most common method for adapting models to specific tasks.

---

## Continued Pre-Training (CPT)

CPT trains a model further on domain-specific text.

This improves model knowledge without requiring instruction formatting.

---

# LoRA Training

Uni Trainer uses **LoRA (Low-Rank Adaptation)** to enable efficient fine-tuning.

LoRA updates a small subset of model parameters rather than retraining the entire model.

Benefits include:

- lower GPU memory requirements
- faster training
- smaller model checkpoints

---

# Hyperparameter Configuration

Training parameters include:

- learning rate
- batch size
- training epochs
- LoRA rank
- gradient accumulation

Default values are provided, but all parameters can be customized.

---

# Local vs Remote Training

Training can run:

- locally on a machine with a GPU
- remotely on a GPU server via SSH

Remote training allows large models to be trained without moving the UI environment.

---

# Training Metrics

During training, Uni Trainer tracks:

- loss
- training progress
- step metrics

These metrics allow monitoring model convergence.

---

# Next Steps

After training completes, evaluate the model using **Validation**.
