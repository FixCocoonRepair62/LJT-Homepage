---
permalink: /
title: "About"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

## 👋 About Me

I am a first-year PhD candidate in Computer Science at the **Hong Kong University of Science and Technology (HKUST)**, affiliated with the HKUST NLP Group. I am fortunate to be advised by [Prof. Junxian He](https://jxhe.github.io/), who has supervised me since my undergraduate days at Shanghai Jiao Tong University.

My research lies at the intersection of **Natural Language Processing** and **Machine Learning**, with a focus on making large language models more capable, truthful, and interpretable. I am especially interested in **LLM reasoning and reinforcement learning**, **hallucination in vision-language models**, and **LLM truthfulness and interpretability**.

---

## 🧠 Research Interests

- Large Language Model Reasoning and Reinforcement Learning
- Hallucination in Vision-Language Models (VLM)
- LLM Truthfulness and Interpretability

---

## 🎓 Education

| Degree | Institution | Period |
|--------|-------------|--------|
| **Ph.D.** | Hong Kong University of Science and Technology (HKUST) | 2024 – Present |
| **B.Eng.** | Shanghai Jiao Tong University (SJTU) | 2020 – 2024 |

---

## 💼 Research Experience

| Role | Institution / Company | Period | Advisor |
|------|----------------------|--------|---------|
| **Research Intern** | MINIMAX | Feb 2025 – Present | — |
| **Research Intern** | Tencent WXG | Jun 2024 – Sep 2024 | Zifei Shan |
| **Research Intern** | Shanghai AI Lab | Jun 2023 – Dec 2023 | Prof. Yu Cheng |

---

## 📄 Publications

{% assign sorted_pubs = site.publications | sort: "date" | reverse %}
{% for post in sorted_pubs %}
  <div style="margin-bottom: 1.2em;">
    <strong>{{ post.title }}</strong><br>
    <small>
      {% if post.authors %}{{ post.authors }}. {% endif %}
      {% if post.venue %}<em>{{ post.venue }}</em>{% endif %}
      {% if post.date %}({{ post.date | date: "%Y" }}){% endif %}
    </small><br>
    {% if post.paperurl %}<a href="{{ post.paperurl }}">Paper</a>{% endif %}
  </div>
{% endfor %}

---

## 🛠️ Skills

- **Research areas:** Natural Language Processing, Machine Learning, Large Language Models
- **Technical skills:** Python, PyTorch, model training and evaluation, data processing

---

## 🏆 Honors

- Zhiyuan Honor Scholarship, Shanghai Jiao Tong University

---

## 📫 Contact

- **Email:** [jliugi@connect.ust.hk](mailto:jliugi@connect.ust.hk)
- **GitHub:** [Vicent0205](https://github.com/Vicent0205)
- **Google Scholar:** [Profile](https://scholar.google.com/citations?hl=en&user=tbK9jl4AAAAJ&view_op=list_works&sortby=pubdate)
- **X / Twitter:** [@junteng88716710](https://twitter.com/junteng88716710)
