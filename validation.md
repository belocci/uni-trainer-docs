# Model Validation

Model validation ensures a fine-tuned model performs correctly before deployment.

Uni Trainer provides evaluation tools designed for LLM workflows.

---

# Golden Set Evaluation

A golden set is a curated evaluation dataset.

It represents expected model behavior across important tasks.

Uni Trainer can run trained models against the golden set to measure performance.

---

# Model Comparison

Uni Trainer supports side-by-side comparison between models.

This allows teams to compare:

- baseline models
- newly fine-tuned models
- different training runs

Comparisons highlight regressions and improvements.

---

# Regression Detection

Fine-tuning can sometimes reduce model performance.

Regression testing detects performance drops compared to previous model versions.

Uni Trainer can automatically flag these issues.

---

# Determinism Testing

LLM outputs can vary across runs.

Determinism testing measures output variance and identifies unstable behavior.

This helps ensure reliable model performance.

---

# Deploy Gates

Deploy gates prevent models from being deployed if validation scores fall below defined thresholds.

This protects production systems from regressions.

---

# Next Steps

After validation, proceed to **Deployment**.
