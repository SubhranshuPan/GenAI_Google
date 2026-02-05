# Machine Learning with TensorFlow and Vertex AI

## Overview
This project demonstrates how to create a Vertex AI Workbench instance to develop a TensorFlow model. It covers the end-to-end workflow including model training, creating input data pipelines, deploying to an endpoint, and generating predictions.

## Architecture
- **Framework:** TensorFlow (End-to-end open source platform for ML)
- **Platform:** Google Cloud Vertex AI (Unified API for AutoML and custom training)
- **Data Services:** Integration with BigQuery and Google Cloud Storage

## Objectives
1. **Workbench Deployment:** Deploy Vertex AI Workbench instance.
2. **Data Preparation:** Create minimal training and validation data.
3. **Pipeline:** Create the input data pipeline.
4. **Modeling:** Create and train a TensorFlow model.
5. **Deployment:** Deploy the model to Vertex AI and Explainable AI.
6. **Inference:** Make predictions from the model endpoint.

## Prerequisites
- Google Cloud Platform account with Vertex AI API enabled.
- Python 3.7+
- System dependency: `graphviz` (Install via `sudo apt install graphviz -y`)

## Usage
1. Install dependencies:
   ```bash
   pip install -r requirements.txt
