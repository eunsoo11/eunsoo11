# ERCP

**Machine learning prediction of common bile duct stones using synthetic data to guide emergency ERCP decisions**

Sungmin Kang, Namyoung Park, Il Sang Shin, Eunsoo Lee, Sieun Choi, Jiyun Jung, Jun Kyu Lee, Yun Nah Lee, Jong Ho Moon, Kwang Ro Joo, Jihie Kim, Joo Seong Kim

**Scientific Reports · 2026**

[Paper](https://www.nature.com/articles/s41598-026-45014-1) · [PDF](https://www.nature.com/articles/s41598-026-45014-1.pdf)

- [About the Study](#about-the-study)
- [Study Design](#study-design)
- [Results](#results)
- [Citation](#citation)

<a name="about-the-study"></a>

## 🔎 About the Study

This retrospective multicenter study predicts common bile duct stones using 11 routinely available clinical variables. An ExtraTrees model combines SMOTE augmentation with LLM-generated synthetic training data to support ERCP risk stratification.

<a name="study-design"></a>

## 📊 Study Design

<img src="https://media.springernature.com/full/springer-static/image/art%3A10.1038%2Fs41598-026-45014-1/MediaObjects/41598_2026_45014_Fig1_HTML.png" alt="Study flowchart showing patient selection, training-data augmentation, internal hold-out testing, and independent external validation." width="900">

*Patient selection and validation design. Figure 1 from [Kang et al. (2026)](https://www.nature.com/articles/s41598-026-45014-1).*

<a name="results"></a>

## 🏆 Results

| Evaluation cohort | Patients | AUROC (95% CI) |
| --- | ---: | ---: |
| Internal hold-out test | 88 | **0.982** (0.952–1.000) |
| Independent external validation | 348 | **0.957** (0.937–0.974) |

*Reported results from Table 2. The 733-patient development cohort was split into 513 training, 132 validation, and 88 hold-out test cases.*

<a name="citation"></a>

## ✅ Citation

```bibtex
@article{kang2026ercp,
  title = "Machine learning prediction of common bile duct stones using synthetic data to guide emergency {ERCP} decisions",
  author = "Kang, Sungmin and Park, Namyoung and Shin, Il Sang and Lee, Eunsoo and Choi, Sieun and Jung, Jiyun and Lee, Jun Kyu and Lee, Yun Nah and Moon, Jong Ho and Joo, Kwang Ro and Kim, Jihie and Kim, Joo Seong",
  journal = "Scientific Reports",
  volume = "16",
  pages = "10585",
  year = "2026",
  doi = "10.1038/s41598-026-45014-1",
  url = "https://doi.org/10.1038/s41598-026-45014-1"
}
```
