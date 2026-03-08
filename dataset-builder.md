# Dataset Builder

The Dataset Builder allows you to convert raw data into structured datasets suitable for LLM fine-tuning.

Uni Trainer supports instruction datasets, conversational datasets, and raw text datasets.

---

# Supported Input Formats

You can import data from:

- `.txt`
- `.csv`
- `.json`
- `.jsonl`
- Markdown files

The dataset builder converts these sources into structured training samples.

---

# Dataset Templates

Uni Trainer includes templates for common dataset formats:

- instruction → response
- question → answer
- conversational messages
- summarization datasets

Templates allow consistent dataset structure across training runs.

---

# Pair Mode

Pair mode allows automatic generation of instruction/response pairs from raw documents.

Example transformation:

Input text → structured prompt/response training sample.

This is useful for converting documentation or articles into training datasets.

---

# Dataset Chunking

Large documents can be split into smaller chunks.

Chunking improves training stability and ensures each training example fits within the model context window.

---

# Deterministic Dataset Splits

Uni Trainer generates reproducible dataset splits:

- training set
- validation set
- test set

The split process is deterministic, meaning the same dataset will always produce the same partitions.

---

# Dataset Fingerprinting

Each dataset version receives a **SHA-256 fingerprint**.

This ensures:

- reproducibility
- provenance tracking
- training auditability

Fingerprinting allows teams to verify exactly which dataset produced a given model.

---

# Next Steps

Once your dataset is ready, proceed to the **Fine-Tuning guide**.
