# Chitti 🔥
> Fine-tuned 7B coding assistant built for security researchers 
> and professional developers.

## Status
🚧 **Active Development** — Core model trained and benchmarked. 
Platform, API, and enterprise features in progress.

## What is Chitti?
I wanted a coding assistant built specifically for security research 
workflows — so I built one from scratch.

Chitti is fine-tuned from Qwen2.5-Coder-7B-Instruct with abliteration 
applied for unrestricted security research use. Full pipeline built solo 
on MoLab (Marimo) — dataset curation → LoRA fine-tuning → 
benchmarking → deployment.

## Benchmark Results
| Benchmark | Chitti | Reference | Status |
|---|---|---|---|
| HumanEval+ | **76.83%** | DeepSeek-Coder-7B: 73% | ✅ Beats reference |
| MultiPL-E avg | **67.49%** | Qwen2.5-Coder-7B: 65% | ✅ Beats reference |
| LiveCodeBench | 23.5% | ~28% | ✅ Credible |

## Training Pipeline
- **Base**: Qwen2.5-Coder-7B-Instruct
- **Abliteration**: Refusal direction removal across all 28 layers (alpha=2.0)
- **Fine-tuning**: LoRA on OpenCodeInstruct via Unsloth + TRL
- **Merge**: LoRA fused into abliterated base — single clean 7.62B model
- **Platform**: Built entirely on MoLab (Marimo) — RTX PRO 6000 Blackwell, 102GB VRAM

## Capabilities
- Strong algorithmic coding — beats DeepSeek-Coder-7B on HumanEval+
- Multilingual — Python, Java, C++, Rust, C#, Go
- Security-focused format: Warning → Code → Detection/Cleanup
- No refusals on legitimate security research tasks

## Tech Stack
`Python` `PyTorch` `Unsloth` `HuggingFace` `PEFT` `TRL` `Gradio`

## Roadmap
- [x] Base model fine-tuning
- [x] Abliteration pipeline
- [x] Benchmark evaluation (HumanEval+, MultiPL-E, LiveCodeBench)
- [x] Model merge and deployment
- [ ] REST API / FastAPI gateway
- [ ] Platform with intelligent model routing
- [ ] Enterprise deployment package
- [ ] SRE-specialized variant (Chitti SRE)

## Model Card
🤗 [huggingface.co/K1shan/Chitti](https://huggingface.co/K1shan/Chitti)

## Contact & Licensing
Available for enterprise licensing and partnerships.

📧 kkishann4@gmail.com
💼 [LinkedIn](https://linkedin.com/in/kkishann)

---
*Built by Kishan N*
