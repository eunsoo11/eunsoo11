# PEEM

**PEEM: Prompt Engineering Evaluation Metrics for Interpretable Joint Evaluation of Prompts and Responses in LLMs**

Minki Hong, Eunsoo Lee, Sohyun Park, Jihie Kim

**IEEE Access · 2026**

[Paper](https://doi.org/10.1109/ACCESS.2026.3679809) · [Preprint PDF](https://arxiv.org/pdf/2603.10477v2)

- [About PEEM](#about-peem)
- [Evaluation Framework](#evaluation-framework)
- [Results](#results)
- [Citation](#citation)

<a name="about-peem"></a>

## 🔎 About PEEM

PEEM evaluates prompts and model responses together, using three prompt criteria and six response criteria. It returns a 1–5 score and an explanation for each criterion, providing feedback that can guide prompt rewriting.

<a name="evaluation-framework"></a>

## 📊 Evaluation Framework

<img src="https://arxiv.org/html/2603.10477v2/figure_2.png" alt="PEEM framework showing prompt evaluation and response evaluation with criterion-specific scores and explanations." width="900">

*Two-stage evaluation framework. Figure 2 from the [authors' preprint, v2](https://arxiv.org/html/2603.10477v2).*

<a name="results"></a>

## 🏆 Results

Prompt rewriting accuracy (%) with **Gemma-2-9B-IT** as the task model and **GPT-4o-mini** as the evaluator:

| Prompt | AG News | SST-2 | GSM8K |
| --- | ---: | ---: | ---: |
| Initial prompt | 59.0 | 73.9 | 57.1 |
| Rewritten using scores and rationales | **83.9** | **92.2** | **65.3** |

*Selected rows from Table 8 of the [authors' preprint, v2](https://arxiv.org/html/2603.10477v2).*

<a name="citation"></a>

## ✅ Citation

```bibtex
@article{hong2026peem,
  title = "{PEEM}: Prompt Engineering Evaluation Metrics for Interpretable Joint Evaluation of Prompts and Responses in {LLMs}",
  author = "Hong, Minki and Lee, Eunsoo and Park, Sohyun and Kim, Jihie",
  journal = "IEEE Access",
  volume = "14",
  pages = "53581--53600",
  year = "2026",
  doi = "10.1109/ACCESS.2026.3679809",
  url = "https://doi.org/10.1109/ACCESS.2026.3679809"
}
```
