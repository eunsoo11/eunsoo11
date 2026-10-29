# TabBridge

**TabBridge: Bridging Structure and Context for Accurate Table Reasoning**

Jeongwoo Lee, Eunsoo Lee, Jihie Kim

**SURGeLLM 2026 · ACL Workshop · Best Paper Award**

[Paper](https://aclanthology.org/2026.surgellm-1.14/) · [PDF](https://aclanthology.org/2026.surgellm-1.14.pdf) · [Official Code](https://github.com/raylee0519/TabBridge)

- [About TabBridge](#about-tabbridge)
- [Method Overview](#method-overview)
- [Results](#results)
- [Citation](#citation)

<a name="about-tabbridge"></a>

## 🔎 About TabBridge

TabBridge helps language models answer questions over tables by connecting table structure with question context. It builds a textual Table Specification (TabSpec), checks it through table reconstruction, and uses the refined representation to guide SQL reasoning.

<a name="method-overview"></a>

## 📊 Method Overview

<img src="https://raw.githubusercontent.com/raylee0519/TabBridge/17f6234e4687d6324fcb6ea0539571839d58117c/method_overview.png" alt="TabBridge method overview: TabSpec generation, reconstruction-based evaluation, and SQL reasoning." width="900">

*Method overview from the [official implementation](https://github.com/raylee0519/TabBridge/blob/17f6234e4687d6324fcb6ea0539571839d58117c/method_overview.png).*

<a name="results"></a>

## 🏆 Results

TabBridge achieves **73.94% accuracy on WikiTableQuestions** in the paper's reported evaluation. Full benchmark comparisons and model settings are available in the [paper](https://aclanthology.org/2026.surgellm-1.14/).

<a name="citation"></a>

## ✅ Citation

```bibtex
@inproceedings{lee-etal-2026-tabbridge,
  title = "{T}ab{B}ridge: Bridging Structure and Context for Accurate Table Reasoning",
  author = "Lee, Jeongwoo and Lee, Eunsoo and Kim, Jihie",
  booktitle = "Proceedings of the First Workshop on Structured Understanding, Retrieval, and Generation in the {LLM} Era ({SURG}e{LLM} 2026)",
  month = jul,
  year = "2026",
  publisher = "Association for Computational Linguistics",
  pages = "219--240",
  doi = "10.18653/v1/2026.surgellm-1.14",
  url = "https://aclanthology.org/2026.surgellm-1.14/"
}
```
