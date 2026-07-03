# LLM Translation Memory Retrieval Experiments

English | [中文](README_ZH.md)


[![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange.svg)](https://jupyter.org/)
[![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)](https://www.python.org/)
[![License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

Experimental notebooks exploring the use of Large Language Models for translation memory retrieval and reuse.

## Contents

| Notebook | Description |
|----------|-------------|
| `LLM_TM_Retrieval_Translation_Exp.ipynb` | Main experiment pipeline covering retrieval-augmented generation, similarity scoring, and TM match ranking |

## Experiments

- **Retrieval-Augmented Translation** — Query translation memory to provide contextual examples to LLMs
- **Similarity Scoring Benchmarks** — Evaluate semantic vs. lexical similarity metrics for TM matching
- **Notebook-Based Prototyping** — Rapid iteration on retrieval strategies before production

## Requirements

```bash
pip install jupyter pandas numpy scikit-learn sentence-transformers openai
```

## Usage

```bash
jupyter notebook LLM_TM_Retrieval_Translation_Exp.ipynb
```

## License

[MIT](LICENSE)
