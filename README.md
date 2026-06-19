# ZenteIQ MaxText Assignment

Training runs and analysis for the ZenteIQ ML Engineer assignment — exploring MaxText's data pipelines, training Qwen3 dense models (0.6B and 1B) across CPU/GPU/TPU, and scaling down DeepSeek V2's MoE architecture to under 1B parameters.

The full writeup, parameter math, and results are in [`notebooks/ZenteIQ_Assignment_Notebook.ipynb`](notebooks/ZenteIQ_Assignment_Notebook.ipynb).

## Repo Structure

```
notebooks/          — assignment notebook (start here)
task2-qwen-dense/   — Qwen3 configs, training logs, metrics CSVs, comparison table
task3-deepseek-moe/ — DeepSeek sub-1B config, training logs, metrics CSVs, comparison table
```

Each task folder is organized by backend (`cpu/`, `gpu/`, `tpu/`) with raw training logs, per-step metrics, and plots per run.
