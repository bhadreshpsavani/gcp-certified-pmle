# gcp-certified-pmle
* TPUs are designed for training large models and are not always the best fit for serving models with high throughput requirements.
* GPUs are specifically designed to handle high-throughput, compute-heavy tasks, making them suitable for large models and low-latency predictions.
* Cloud Scheduler allows you to trigger periodic jobs such as model retraining at scheduled intervals.
* Cloud Composer is a general-purpose orchestration tool, not specifically optimized for ML workflows.
* A Git push event (e.g., new model code) can trigger Cloud Build to retrain the model based on new data.
* Dataflow is designed for stream processing and may not be the best choice for triggering retraining jobs.
* Cloud Functions can listen to events, such as new data arriving, and automatically trigger retraining.
* Vertex AI Pipelines is specifically designed to orchestrate end-to-end ML workflows on GCP.
* Vertex AI focuses on training and deployment, but it doesn't specifically handle data and model validation.
* Dataflow is an ETL service, not a dedicated ML pipeline orchestration tool.
* Kubeflow Pipelines is not GCP-native and may require additional setup for seamless integration with Vertex AI.
* Jenkins Pipelines is more suited for traditional software builds and may not directly address model retraining triggered by data changes.

## Links
* [vertex-ai-overview](https://cloud.google.com/vertex-ai/docs/start/introduction-unified-platform)
* [introduction-mlops-vertexai](https://cloud.google.com/vertex-ai/docs/start/introduction-mlops)
* [vertexai-training-methods](https://cloud.google.com/vertex-ai/docs/start/training-methods)
* [intro-to-tpu#when_to_use_tpus](https://cloud.google.com/tpu/docs/intro-to-tpu#when_to_use_tpus)
* [ml-on-gcp-best-practices#model-deployment-and-serving](https://cloud.google.com/architecture/ml-on-gcp-best-practices#model-deployment-and-serving)
* [mlops-continuous-delivery-and-automation-pipelines-in-machine-learning](https://cloud.google.com/architecture/mlops-continuous-delivery-and-automation-pipelines-in-machine-learning)
