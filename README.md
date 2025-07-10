# 🧠 ArabicArticles_Qwen-Finetuning

Fine-tuning **Qwen2.5** on Arabic NLP tasks using **LLaMA-Factory**, **Pydantic**, and **vLLM** — powered by **PEFT**, **LoRA**, and open-source magic! 🚀

---

### In this Repo we will Implement :
- Structured Outputs
- Knowledge Distillation
- PEFT Finetuning
- Finetuning Solutions
- LLM Finetuning
- LLM Deploying
- Cost Estimation

---

## 📁 What’s Inside This Repository

This repo documents the full fine-tuning pipeline for Qwen2.5-1.5B on Arabic tasks such as **classification** and **translation**, using:

- 🧱 **LLaMA-Factory** for training LoRA adapters  
- ⚙️ **Pydantic** for defining structured outputs  
- ⚡ **vLLM** for fast and optimized inference  
- 🧪 **WandB** for experiment tracking  
- 🏷️ **Hugging Face Transformers** for model interfacing  

---

## 🚀 Key Features Implemented

### ✅ Setup & Preparation
- Set up your Colab / local GPU environment
- Choose a base model: [`Qwen/Qwen2.5-1.5B-Instruct`](https://huggingface.co/Qwen/Qwen2.5-1.5B-Instruct)

### 🧩 Task 1: Classification
- Structure outputs using `Pydantic`
- Evaluate base model zero-shot
- Finetune with LLaMA-Factory
- Compare post-tuning performance

### 🔁 Task 2: Arabic-English Translation
- Define translation schema with `Pydantic`
- Evaluate using OpenAI API and Qwen model

### 🏗️ Finetuning
- Prepare datasets with SFT format
- Configure training via `LLaMA-Factory` YAMLs
- Finetune using PEFT (LoRA)
- Track logs and performance with `Weights & Biases`

### ⚡ Deployment & Testing
- Deploy the fine-tuned model using `vLLM`
- Perform load testing with Locust
- Estimate token-based cost and performance

---

## 📚 Notebooks & Resources

- 🔗 **Colab Notebook**: [Link](https://colab.research.google.com/drive/16E0BtTY5ku1Jcq0_yNwnjn0PIxjFcef-?usp=sharing)
- 📂 **Datasets**: [Google Drive](https://drive.google.com/drive/folders/1dXNNFNg_RKMYC9nxF59d0LAt67-T4oDf)
- 🧠 **Qwen2.5-1.5B-Instruct Model**: [HuggingFace](https://huggingface.co/Qwen/Qwen2.5-1.5B-Instruct)

### 🔧 Tools Used
- [LLaMA-Factory](https://github.com/hiyouga/LLaMA-Factory)
- [Hugging Face](https://huggingface.co/)
- [Weights & Biases](https://wandb.ai/)
- [vLLM](https://github.com/vllm-project/vllm)

---

## 📺 Course Chapters by @alm3tasem

| Time | Chapter |
|------|---------|
| 00:00:00 | Welcome |
| 00:01:49 | Intro to Finetuning LLMs |
| 00:16:41 | Use Case Overview |
| 00:21:34 | Colab Setup |
| 00:29:31 | Choosing Base Model (Qwen2.5) |
| 00:36:04 | Pydantic - Classification Task |
| 01:02:12 | Base Model Evaluation |
| 01:14:58 | Pydantic - Translation Task |
| 01:22:11 | Evaluation via OpenAI API |
| 01:27:19 | Dataset Preparation |
| 01:55:45 | Finetuning Frameworks |
| 02:04:10 | Using LLaMA-Factory |
| 02:25:07 | YAML Configurations |
| 02:46:51 | Running Finetuning |
| 02:55:10 | Finetuned Model Evaluation |
| 03:02:25 | Cost Estimation |
| 03:11:23 | Deploying with vLLM |
| 03:24:27 | Load Testing |
| 03:41:36 | Recap |
| 03:47:45 | Outro |

---

## 👨‍💻 Who Is This repo For?

This repository is ideal for:

- 💼 **Machine Learning Engineers** fine-tuning LLMs
- 🌍 **NLP Practitioners** focusing on Arabic language tasks
- 🧠 **AI Researchers** exploring parameter-efficient tuning (PEFT, LoRA)
- ⚙️ **Developers** deploying real-world LLM applications

---

## 📌 Prerequisites

- ✅ Python & NLP basics
- ✅ Familiarity with Hugging Face Transformers
- ✅ Access to GPU (Colab or cloud-based)

---

## 🧠 Inspired By

> "Fine-Tuning Large Language Models: A Practical Guide"  
by Abo Bakr Soliman  
📺 [Watch the full course](https://www.youtube.com/watch?v=S9VHQhC3HPc)

---

## 📜 License

This project is licensed under the MIT License.

---

## 🌟 Give it a Star

If you find this useful, please ⭐ the repo and share it with others interested in LLMs and Arabic NLP!

