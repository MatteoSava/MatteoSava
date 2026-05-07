# Hi, I'm Matteo 👋

AI Engineer focused on **agentic systems**, **cloud automation** and **practical AI workflows**.

Currently working again on [canalitelegram.it](https://canalitelegram.it/) — an Italian crawler and search engine for Telegram channels.

## Some random projects

### [Claude Makerplace](https://github.com/MatteoSava/claude-makerplace)

A Claude Code plugin marketplace that packages reusable agent workflows into installable plugins.  
The core pattern is a **skill autoresearch loop** — when a skill produces a wrong result, the agent updates the skill itself so the mistake doesn't repeat. Ships 23 self-improving skills across 5 plugins, with runtime hooks, subagents and CI validation.

`Claude Code` · `Python` · `GitHub Actions`

### [lmcomplete](https://github.com/MatteoSava/lmcomplete)

A context-aware shell command helper written in Rust.  
It turns natural-language requests into shell command suggestions, enriching prompts with the current directory, shell type, git state and recent command history. Commands are printed but never auto-executed. Includes secret redaction before prompts leave the machine and an `audit` mode to inspect prompt bundles locally.

`Rust` · `OpenRouter API` · `zsh`

### [genetic-perplexity-optimizer](https://github.com/MatteoSava/genetic-perplexity-optimizer)

A genetic algorithm for Kaggle's Santa 2024 Perplexity Permutation Puzzle.  
It reorders bags of words into sentences that minimize perplexity as scored by Gemma-2-9B, using duplicate-safe ordered crossover, adaptive mutation pressure and Bayesian hyperparameter sweeps. Runs on H100 GPUs via Modal.

`Python` · `PyTorch` · `Modal` · `W&B`

### [pixelart-lora](https://github.com/MatteoSava/pixelart-lora)

LoRA fine-tuning for constrained grayscale pixel-art generation on SDXL/FLUX.  
Training uses a custom preprocessing transform (grayscale → downscale → nearest-neighbor upsample → gray quantization) so the diffusion loss directly learns the target style. Ships with a Gradio UI backed by Modal GPU inference.

`Python` · `Diffusers` · `LoRA` · `Modal` · `Gradio`

### [TinyHarness](https://github.com/MatteoSava/TinyHarness)

Benchmark harness for coding-agent experiments on Terminal-Bench 2.0.  
It runs a Claude-Code-style SDK agent against a Modal-hosted Qwen gateway, uses DSPy/GEPA to optimize the agent's system prompt, and logs structured metrics to MLflow.

`Python` · `DSPy` · `Modal` · `MLflow` · `Anthropic Agent SDK`

### [leonardo-challenge-2024](https://github.com/MatteoSava/leonardo-challenge-2024)

Multimodal classification challenge with Leonardo Company S.p.A. (2nd place).  
The solution fuses ViT visual features with GPT-2 text embeddings to classify hidden context from image + text pairs.

`Python` · `PyTorch` · `ViT` · `GPT-2`

### [cicd-actions](https://github.com/MatteoSava/cicd-actions)

Reusable GitHub Actions for Docker-based CI/CD pipelines.  
Composable actions for monorepo change detection, smart image tagging, environment promotion (dev → staging → prod) and automatic image cleanup with retention policies.

`GitHub Actions` · `Docker` · `GHCR`

### [zmk-config-totem](https://github.com/MatteoSava/zmk-config-totem)

Personal keymap configuration for the TOTEM, a 38-key column-staggered split keyboard I assembled from scratch.  
Push to GitHub and the firmware `.uf2` files are built automatically via Actions — just drag and drop to flash.

`ZMK` · `DIY Split Keyboard` · `GitHub Actions`

## What I work with

```text
Python · Rust · Java · Go · TypeScript
LangGraph · LangChain · PyTorch · Diffusers
Terraform · Docker · Kubernetes · GitOps
Azure · AWS · Azure DevOps · GitHub Actions
Kafka · REST APIs · Microservices
Claude Code · Agentic Workflows · LLM Tooling
```
