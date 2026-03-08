# Deployment

After training and validation, Uni Trainer allows models to be deployed for inference.

Deployment converts trained checkpoints into usable inference endpoints.

---

# Deployment Targets

Uni Trainer supports three deployment methods.

## Local Deployment

Models can be deployed locally using Ollama.

Uni Trainer automatically generates the required Modelfile.

---

## Remote Deployment

Models can be deployed to remote servers using:

- SSH
- Docker containers

This allows scalable inference infrastructure.

---

## Docker Export

Models can also be exported as Docker images for custom environments.

This allows integration with existing infrastructure.

---

# API Access

When deployed, Uni Trainer generates API keys for accessing the model.

These endpoints can be used for:

- chat applications
- backend services
- evaluation pipelines

---

# Deployment History

Uni Trainer maintains deployment history for each model.

This includes:

- dataset version
- training configuration
- model checkpoint
- deployment metadata

This ensures full training lineage and auditability.

---

# Production Considerations

When deploying models to production:

- monitor inference latency
- validate model outputs
- maintain dataset provenance
- track deployment versions

These practices ensure reliable AI systems.

---

# Next Steps

Refer to the **documentation index** for advanced configuration guides.
