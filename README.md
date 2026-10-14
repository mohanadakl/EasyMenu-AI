# EasyMenu AI

**Deep Learning-Based Intelligent Restaurant Management System**

EasyMenu AI is a graduation project currently in planning and development. It aims to integrate customized Deep Learning modules into a restaurant management system.

> **Status:** The three modules and technologies below are proposed and have not been implemented or validated yet. This repository currently contains project documentation; no trained models, working application, or benchmark results are claimed.

## Planned modules

### 1. Menu Extractor
Extract menu categories, products, descriptions, and prices from images and PDF documents using Computer Vision, OCR, and document understanding. Extracted fields should be reviewed before saving them to the restaurant system.

### 2. Text-to-SQL Analytics Chatbot
Help restaurant managers ask business questions in natural language. A proposed language-model pipeline would generate SQL, validate it against the database schema, execute permitted read-only queries, and summarize the results. Access controls and query validation are requirements for future implementation.

### 3. Food Image Generator
Generate illustrative food images from product names and descriptions using diffusion models. Optional fine-tuning may improve visual consistency. Images should be reviewed and labeled as AI-generated illustrations; they do not establish the appearance of an actual dish.

## Proposed technologies

| Area | Candidates to evaluate |
| --- | --- |
| Development and training | Python, PyTorch or TensorFlow |
| Detection and OCR | YOLO, PaddleOCR |
| Document understanding | LayoutLMv3 |
| Text-to-SQL and language models | Qwen or Llama |
| Image generation | Stable Diffusion XL, optional LoRA fine-tuning |

These are candidates, not installed dependencies or completed integrations. Final choices depend on experiments, compute, data quality, and model/data licensing.

## Roadmap

- Define requirements, datasets, metrics, and integration interfaces.
- Build and evaluate a baseline for each module.
- Compare models and document reproducible experiments.
- Integrate reviewed outputs into the restaurant management system.
- Test the complete workflow and document limitations.

## Getting started

There is no runnable implementation or installation procedure yet. Setup instructions will be added with the first working module. See [CONTRIBUTING.md](CONTRIBUTING.md) for the team workflow.

## Data and experiments

Keep credentials, private restaurant/customer data, datasets, model weights, and large experiment artifacts out of Git. Use approved external storage and document data provenance, access requirements, and licenses. Report measured results only after experiments are completed.

**Project status: Graduation Project — Planning & Development.**
