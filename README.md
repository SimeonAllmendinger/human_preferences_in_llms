# **Human Preferences in Large Language Model Latent Space: A Technical Analysis on the Reliability of Synthetic Data in Voting Outcome Prediction**

## 📄 Overview
This repository contains our paper **"Human Preferences in Large Language Model Latent Space: A Technical Analysis on the Reliability of Synthetic Data in Voting Outcome Prediction."**
The study examines the reliability of large language models (LLMs) in predicting electoral outcomes by comparing AI-generated political preferences with real-world survey data.
Our methodology goes beyond simple token-based analysis and instead probes the internal structures of LLMs to extract **value vectors** for different political parties,
revealing systematic biases and distortions in AI-generated responses.

## 📊 Key Findings
- **LLMs fail to capture real-world political diversity.** AI-generated responses were overly uniform compared to human survey data.
- **Systematic bias in AI-generated political preferences.** Base models tended to skew toward right-wing populist parties, while aligned models (trained with RLHF) leaned toward establishment parties.
- **Prompt sensitivity and instability.** Small changes in question phrasing led to significant variations in LLM responses.
- **Entropy as a diversity measure.** We use entropy to quantify how AI-generated political opinions cluster around dominant choices instead of reflecting a broad spectrum of views.
