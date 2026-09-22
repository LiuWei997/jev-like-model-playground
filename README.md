# System1

Template code for running lightweight System 1 (fast, intuitive) models locally on Apple Silicon Macs, powered by [MLX](https://github.com/ml-explore/mlx).

Partial models just do not support MLX, but still can work with mps. 😭

## Quickstart

```bash
python -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
```

## Overview

This project provides a collection of System 1 models that can run locally on Apple Silicon Macs. 
## Models

| Model | Runtime | Model Card |
|---|---|---|
| `Qwen3.5-4B-MLX-4bit` | MLX | [mlx-community/Qwen3.5-4B-MLX-4bit](https://huggingface.co/mlx-community/Qwen3.5-4B-MLX-4bit) |
| `laya-mlx` | MLX | [aac6fef/laya-mlx](https://huggingface.co/aac6fef/laya-mlx) |
| `bart-large-mnli` | PyTorch (MPS) | [facebook/bart-large-mnli](https://huggingface.co/facebook/bart-large-mnli) |