# PipelineIQ Dashboard API

Independent repository staging folder for the PipelineIQ dashboard API.

## Build

```bash
docker build -t nimeshsv814/pipelineiq-dashboard-api:v1.0.0 -f services/dashboard-api/Dockerfile .
```

## Run

This service expects PipelineIQ environment variables from Kubernetes ConfigMap and Key Vault secrets.
