# LLM Translation Memory Retrieval Experiments

<!-- bilingual-readme:start -->

## 双语说明 / Bilingual Documentation

> 本节提供整篇 README 的中英双语维护说明；下方保留原始详细说明、命令、路径和配置示例。
> This section provides bilingual maintenance notes for the full README; the original detailed notes, commands, paths, and configuration examples are preserved below.

### 中文

**概览**：LLM 翻译记忆检索实验仓库，用于探索 TM 检索策略与实验结果。

**主要能力**：
- 包含 Jupyter/Python 实验。
- 面向翻译记忆检索效果评估。
- 用于研究和对比，不是生产服务。

**使用方式**：按下方 notebook 或脚本说明准备数据并运行实验。

**状态**：该仓库仍按当前 README 的说明维护或使用。

**注意事项**：实验结论应结合数据集和参数解释。

### English

**Overview**: Experimental repository for studying LLM translation-memory retrieval strategies and results.

**Key capabilities**:
- Contains Jupyter/Python experiments.
- Evaluates translation-memory retrieval behavior.
- Used for research and comparison, not as a production service.

**Usage**: Prepare data and run notebooks or scripts according to the notes below.

**Status**: This repository is maintained or used according to the current README notes.

**Notes**: Experimental conclusions should be interpreted with the dataset and parameters in mind.

<!-- bilingual-readme:end -->

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