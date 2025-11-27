# Dify GPT-4 Workflow: Sentiment Analysis (Indonesian)

This repository contains a low-code Dify workflow for performing sentiment analysis on Indonesian text using GPT-4. It was developed as part of a research case study on analyzing protest-related tweets without task-specific fine-tuning.

## 📂 File
- `sentiment-analysis.yml`: Exported Dify workflow with structured prompt logic and routing for aggregated and per-category sentiment output.

## 🧠 Features
- Few-shot inference using GPT-4-turbo and GPT-4o-mini
- JSON-based structured sentiment output
- Supports both holistic and aspect-based sentiment modes
- No-code deployment via [Dify](https://github.com/langgenius/dify)

## 📝 Usage
To use this workflow:
1. Import `sentiment-analysis.yml` into your Dify instance.
2. Upload a CSV file with columns `input_text`, `Multisentiment`, and optional `Categories`.
3. Run batch mode and collect structured sentiment outputs in JSON.

## 🔗 Related Publication
This workflow was used in our paper:
> *"Low-Code GPT-4 Workflow for Indonesian Sentiment Analysis with Dify" (ACM ICPS 2025)*  
> [View the full prompt here](https://github.com/esqlite/dify-workflow/blob/main/sentiment-analysis.yml)

## 📜 License
MIT License.
