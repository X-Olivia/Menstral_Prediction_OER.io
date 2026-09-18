# Menstrual Prediction Research OER

An open educational resource for people entering menstrual-cycle prediction from app development, AI / data science, or medicine.

This site does not treat menstrual prediction as a single forecasting task. It frames it as a biologically constrained, weakly labelled, deployment-sensitive research area, and helps readers start from their own background rather than from a wall of papers.

**Live site:** [https://x-olivia.github.io/Menstral_Prediction_OER.io/](https://x-olivia.github.io/Menstral_Prediction_OER.io/)

中文入口：[index_zh.html](index_zh.html)

## Who it is for

- **App developers** who need realistic product scope, public-data options, and claims that are scientifically safe
- **AI / DS researchers** who can build models but need physiological constraints, label realities, and evaluation pitfalls
- **Medical / clinical researchers** who understand the cycle clinically and need a fast translation into AI task framing, splits, and metrics

This OER is for education and research orientation. It is **not** clinical advice, a commercial blueprint, or a recommendation of one “best model”.

## What you will find

| Page | English | 中文 | Purpose |
| --- | --- | --- | --- |
| Start Here | [index.html](index.html) | [index_zh.html](index_zh.html) | Choose a path by role, then enter the field |
| Field Guide | [survey.html](survey.html) | [survey_zh.html](survey_zh.html) | Cycle basics, task definitions, methods, wearable signals, evaluation |
| Literature Map | [literature.html](literature.html) | [literature_zh.html](literature_zh.html) | Read by question and background, not only by year |
| Data & Code | [resources.html](resources.html) | [resources_zh.html](resources_zh.html) | Public datasets, starter paths, code, reproducibility checks |
| Research Case Study | [thesis.html](thesis.html) | [thesis_zh.html](thesis_zh.html) | Wearables and irregularity: a teaching-oriented research snapshot |
| Kaggle Teaching Case | [kaggle-p1.html](kaggle-p1.html) | [kaggle-p1_zh.html](kaggle-p1_zh.html) | Baseline workflow: cleaning, features, GroupKFold, result limits |
| About | [about.html](about.html) | [about_zh.html](about_zh.html) | Purpose, audience, and first-visit guidance |
| License | [license.html](license.html) | [license_zh.html](license_zh.html) | Reuse terms and citation |

## Run locally

This is a static site. Open `index.html` in a browser, or serve the folder:

```bash
# Python 3
python3 -m http.server 8000

# Node
npx serve .
```

Then visit `http://localhost:8000`.

## Suggested reading order

1. Start on [Start Here](index.html) and pick the path that matches your background.
2. Use the [Field Guide](survey.html) for shared foundations.
3. Move to [Data & Code](resources.html) when you are ready to work hands-on.
4. Use the [Literature Map](literature.html) to expand reading by question, not by recency alone.

## License and citation

Text content is released under [CC BY-NC 4.0](https://creativecommons.org/licenses/by-nc/4.0/). You may share and adapt it with attribution for non-commercial use.

**APA**

*Menstrual Prediction Research OER: A Guide for New Researchers.* (2026). Retrieved from https://x-olivia.github.io/Menstral_Prediction_OER.io/

**BibTeX**

```bibtex
@misc{menstrual_oer_2026,
  title = {Menstrual Prediction Research OER: A Guide for New Researchers},
  year = {2026},
  howpublished = {\url{https://x-olivia.github.io/Menstral_Prediction_OER.io/}},
  note = {Accessed: 2026-09-18}
}
```

---

# 月经预测研究开放教育资源

面向 App 开发者、AI / 数据科学研究者与医学研究者的月经预测入门 OER。

本站不把月经预测简化成单一时间序列任务，而是把它还原成一个受生理约束、标签不统一、部署条件复杂的交叉研究问题，并按读者背景提供不同入口。

**在线站点：** [https://x-olivia.github.io/Menstral_Prediction_OER.io/](https://x-olivia.github.io/Menstral_Prediction_OER.io/)

本资源用于教学与研究入门，**不能**替代医疗建议，也不提供现成商业方案或“最准模型”推荐。

## 建议阅读顺序

1. 从[开始这里](index_zh.html)按背景选择入口。
2. 需要共同基础时阅读[领域综述](survey_zh.html)。
3. 准备动手时进入[数据与代码](resources_zh.html)。
4. 按问题扩展阅读时使用[文献地图](literature_zh.html)。
