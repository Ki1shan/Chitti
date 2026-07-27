# 🚀 Chitti

> **Enterprise-grade Coding Assistant built for Security Researchers and Professional Developers**

[![Python](https://img.shields.io/badge/Python-3.10+-blue.svg)]()
[![License](https://img.shields.io/badge/License-Research-green.svg)]()
[![Base Model](https://img.shields.io/badge/Base-Qwen2.5--Coder--7B--Instruct-orange.svg)]()
[![Status](https://img.shields.io/badge/Status-Active%20Development-success.svg)]()

---

## ✨ Overview

Chitti is a fine-tuned coding assistant designed for **secure software development**, **cybersecurity research**, and **professional engineering workflows**.

Built upon **Qwen2.5-Coder-7B-Instruct**, Chitti combines abliteration and LoRA fine-tuning to deliver strong coding performance while remaining practical for legitimate security research.

The complete training and evaluation pipeline was built independently using **MoLab (Marimo)** on NVIDIA RTX PRO 6000 Blackwell GPUs.

---

# 🏆 Highlights

- 🚀 Fine-tuned from **Qwen2.5-Coder-7B-Instruct**
- 🧠 Built entirely on **MoLab (Marimo)**
- ⚡ HumanEval+ **76.83%**
- 🌍 Multilingual programming support
- 🛡 Optimized for security-focused development
- 📈 Beats DeepSeek-Coder-7B on HumanEval+

---

# 📊 Benchmark Results

| Benchmark | Chitti | Reference | Result |
|-----------|--------:|----------:|:------:|
| HumanEval+ | **76.83%** | DeepSeek-Coder-7B (73%) | ✅ |
| MultiPL-E Average | **67.49%** | Qwen2.5-Coder-7B (65%) | ✅ |
| LiveCodeBench | **23.5%** | Competitive | ✅ |

---

# 🎯 Designed For

Chitti is built to assist with:

- Secure Software Development
- Cybersecurity Research
- Code Understanding
- Algorithm Design
- Code Refactoring
- Debugging
- Technical Documentation
- Professional Development Workflows

---

# ⚙️ Training Pipeline

```
Qwen2.5-Coder-7B-Instruct
            │
            ▼
      Abliteration
            │
            ▼
     LoRA Fine-Tuning
            │
            ▼
      Model Merging
            │
            ▼
 Benchmark Evaluation
            │
            ▼
      Final Deployment
```

---

# 🌐 Supported Languages

- Python
- Java
- C++
- C#
- Go
- Rust
- JavaScript
- TypeScript
- SQL
- Bash

---

# 🛠 Technology Stack

- Python
- PyTorch
- Hugging Face Transformers
- PEFT
- TRL
- Unsloth
- Gradio
- CUDA

---

# 📈 Current Status

| Component | Status |
|-----------|--------|
| Base Model | ✅ Complete |
| Fine-tuning | ✅ Complete |
| Abliteration Pipeline | ✅ Complete |
| Benchmark Evaluation | ✅ Complete |
| Model Merge | ✅ Complete |
| Public Model Card | ✅ Available |
| Platform Integration | 🚧 In Progress |

---

# 🗺 Roadmap

### Completed

- ✅ Base model selection
- ✅ Abliteration pipeline
- ✅ LoRA fine-tuning
- ✅ Benchmark evaluation
- ✅ Model merging
- ✅ Public release

### In Progress

- 🚧 Platform integration
- 🚧 REST API
- 🚧 Enhanced inference pipeline

### Future

- Enterprise Edition
- Community Edition
- Expanded model family
- Performance optimization
- Additional evaluation benchmarks

---

# 🤗 Model Card

**Hugging Face**

https://huggingface.co/K1shan/Chitti

---

# 📄 License

This repository contains the publicly available Chitti model.

Enterprise deployment capabilities, advanced orchestration, and commercial features are **not included** in this repository.

For enterprise licensing or research collaborations, please get in touch.

---

# 📬 Contact

**Kishan N**

📧 Email: kkishann4@gmail.com

💼 LinkedIn: https://www.linkedin.com/in/kishann

---

> *Building AI systems for secure software engineering and cybersecurity research.*
