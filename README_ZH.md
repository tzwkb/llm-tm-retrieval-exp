# LLM Translation Memory Retrieval Experiments

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

[English](README.md) | 中文

## 概览

LLM 翻译记忆检索实验仓库，用于探索 TM 检索策略与实验结果。

## 主要能力

- 包含 Jupyter/Python 实验。
- 面向翻译记忆检索效果评估。
- 用于研究和对比，不是生产服务。

## 使用方式

按下方 notebook 或脚本说明准备数据并运行实验。

## 注意事项

实验结论应结合数据集和参数解释。

## 命令与配置参考

以下命令、路径和配置键保持原样，复制时请以实际环境为准。

```bash
pip install jupyter pandas numpy scikit-learn sentence-transformers openai
```

```bash
jupyter notebook LLM_TM_Retrieval_Translation_Exp.ipynb
```

## 对应技术覆盖

### Notebook 内容

`LLM_TM_Retrieval_Translation_Exp.ipynb` 是主要实验入口，用于验证翻译记忆检索、相似度排序和 LLM 上下文复用。

### 实验方向

- 检索增强翻译：从 TM 中找出相似句对作为 LLM 参考。
- 相似度评分：比较语义相似度和字面相似度对 TM 匹配的影响。
- Notebook 原型：在进入生产工具前快速验证检索策略。

### 运行方式

安装 Jupyter、数据处理和 embedding 相关依赖后，用 `jupyter notebook` 打开实验文件并逐格执行。
