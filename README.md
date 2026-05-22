# enterprise-project-1

## Enterprise 1 — Fraud Detection System (Batch + Real-time)
- Why: popular enterprise problem with streaming & ML.
- Combine: Kafka, Spark, Python model serving, Spring Boot for admin microservices.
- Core deliverables
  1. Feature engineering modules (batch & streaming)
  2. Model training + explainability module
  3. Real-time scoring pipeline + alerting
  4. Admin UI for flagged transactions

- Key checkpoints
  1. Offline model & evaluation
  2. Real-time stream scored & stored
  3. Admin UI for triage

### MVOs covered
  - Enterprise DS/ML/DL MVO
  - DevOps streaming MVO (reuses DevOps Project B)
  - Backend & frontend admin UI (for triage)
  
### Minimal artifacts to include
  - Feature engineering notebooks (batch + streaming) with documented math.
  - Model training notebook + evaluation metrics.
  - Streaming scoring demo (Kafka + consumer) + serving API.
  - Tests + CI + Docker + k8s manifests.
  - Demo README + video.
