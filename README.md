# Agentic RAG for Evidence-Based Question Answering

This project compares Direct, Single RAG, Fixed Multi-query RAG, and Adaptive RAG on HotpotQA.
The implementation and experiment results are in [`project.ipynb`](project.ipynb).

## Setup

Requires Python 3.11+.

```bash
python -m pip install -r requirements.txt
jupyter lab project.ipynb
```
Local generation requires Ollama with `qwen3:8b`.

Set `RUN_EXPERIMENT=False` to load saved results or `True` to run/resume the experiment.

