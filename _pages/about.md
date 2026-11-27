
---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

# 👋🏻 About Me

Hello! I am **Qing Liu (刘庆)**, an M.S. student in Artificial Intelligence at the **Hangzhou Institute for Advanced Study, University of Chinese Academy of Sciences (UCAS)**. I received my bachelor's degree in Data Science and Big Data Technology from **Beijing Sport University**.

My research interests include **LLM post-training, knowledge editing, and efficient inference**. I focus on improving the effectiveness, reliability, and efficiency of large language models through data-centric fine-tuning, knowledge editing, and inference optimization.

My research has been published at **NeurIPS, ACL, EMNLP, and Neurocomputing**.

I am currently seeking **internship opportunities in LLM algorithms** and future opportunities in algorithm engineering. Please feel free to contact me via email ([liuqing25@mails.ucas.ac.cn](mailto:liuqing25@mails.ucas.ac.cn)).

[Google Scholar](https://scholar.google.com/citations?user=Yzqz7woAAAAJ&hl=zh-CN) · [GitHub](https://github.com/luciabcd)

# 🔬 Research Interests

- **LLM Post-training:** Data-centric fine-tuning, sample weighting, and adaptation-stability trade-offs.
- **Knowledge Editing:** Reliable model editing under conflicting and inconsistent knowledge.
- **Efficient Inference:** Memory-efficient LLM inference and KV cache optimization.

# 🔥 News

- *2026*: 🎉 **"DRIVE: Fine-tuning via Data Contribution- and Diversity-aware Weighting with Prior Regularization"** was accepted at **NeurIPS 2026**.
- *2026*: 🎉 **"AlphaToken: Decoupling Adaptation and Stability for Path-Aware Response Token Valuation in LLM Post-Training"** was accepted at **EMNLP 2026**.
- *2026*: 🎉 **"AlphaEdit+: Model Editing in the Presence of Conflicting and Inconsistent Knowledge"** was accepted at **ACL 2026**.
- *2026*: 🎉 **"R²Edit: Mastering Relation Replacement Editing via Target-Smoothed Forgetting and Self-Paced Learning"** was accepted at **EMNLP 2026**.
- *2025*: 🎉 Published the first-author paper **"Low-rank tensor recovery via jointing the non-convex regularization and deep prior"** in **Neurocomputing**.

# 📝 Publications

<div class='paper-box'>
<div class='paper-box-image'>
<img src='images/drive.png' alt="DRIVE framework" width="100%">
</div>
<div class='paper-box-text' markdown="1">

**DRIVE: Fine-tuning via Data Contribution- and Diversity-aware Weighting with Prior Regularization** (<span style="color: #d93025; font-weight: bold;">NeurIPS 2026, CCF-A, Accepted, First Author</span>)

**Q. Liu**, X. Chen, et al.

**Keywords:** Data-centric Fine-tuning · Diversity-aware Weighting · Knowledge Retention

- Proposed **DRIVE**, a data-weighting framework that combines Shapley-based contribution decomposition, covariance-based diversity modeling, and KL prior regularization to balance task adaptation and knowledge retention.
- On MetaMathQA, DRIVE improves the aggregate scores of three models by **1.43–1.68 percentage points** over their respective strongest baselines.

</div>
</div>

<div class='paper-box'>
<div class='paper-box-image'>
<img src='images/alphatoken.png' alt="AlphaToken framework" width="100%">
</div>
<div class='paper-box-text' markdown="1">

**AlphaToken: Decoupling Adaptation and Stability for Path-Aware Response Token Valuation in LLM Post-Training** (<span style="color: #d93025; font-weight: bold;">EMNLP 2026, CCF-B, Accepted, First Author</span>)

**Q. Liu**, O. Wu, et al.

**Keywords:** Token Valuation · LLM Post-training · Model Stability

- Proposed **AlphaToken**, a path-aware response-token valuation framework that jointly models direct gradient effects and downstream causal effects in autoregressive generation.
- Introduced a pretrained-model-anchored Fisher drift proxy to evaluate model stability without retained training data, and extended Ghost Dot-Product for efficient token-level valuation.
- Achieved aggregate score improvements of **1.54, 2.80, and 2.51 percentage points** on Llama, Gemma, and Qwen, respectively.

</div>
</div>

<div class='paper-box'>
<div class='paper-box-image'>
<img src='images/alphaedit.png' alt="AlphaEdit+ framework" width="100%">
</div>
<div class='paper-box-text' markdown="1">

**AlphaEdit+: Model Editing in the Presence of Conflicting and Inconsistent Knowledge** (<span style="color: #d93025; font-weight: bold;">ACL 2026, CCF-A, Accepted, Co-first Author</span>)

**Q. Liu**<sup>‡</sup>, J. Zhang<sup>‡</sup>, et al.

**Keywords:** Knowledge Editing · Knowledge Conflicts · Model Reliability

- Proposed a knowledge-editing framework combining **null-space constraint relaxation, historical editing constraint weighting, and target smoothing** to improve editing robustness under conflicting and inconsistent knowledge.
- On LLaMA3, the editing success rate increases from **87.75% to 95.55%**, achieving a **7.80 percentage-point improvement**.

</div>
</div>

<div class='paper-box'>
<div class='paper-box-image'>
<img src='images/r2-edit.png' alt="R2Edit framework" width="100%">
</div>
<div class='paper-box-text' markdown="1">

**R²Edit: Mastering Relation Replacement Editing via Target-Smoothed Forgetting and Self-Paced Learning** (<span style="color: #d93025; font-weight: bold;">EMNLP 2026, CCF-B, Accepted, Third Author</span>)

X. Cao, X. Chen, **Q. Liu**, et al.

**Keywords:** Knowledge Editing · Relation Replacement · Self-Paced Learning

- Constructed **ReEditBench**, a benchmark for relation-replacement editing, and proposed a two-stage framework combining target-smoothed forgetting and self-paced learning.
- The method first suppresses obsolete relations and then progressively introduces new relations from easy to difficult samples.
- Compared with AlphaEdit, the relation-replacement success rate on LLaMA3 increases from **52.18% to 81.71%**, while the old-relation retention rate on GPT2-XL decreases from **91.31% to 48.78%**.

</div>
</div>

### Journal Publications

**Low-rank tensor recovery via jointing the non-convex regularization and deep prior** (<span style="color: #d93025; font-weight: bold;">Neurocomputing, 648:130610, 2025, JCR Q1, First Author</span>)

**Q. Liu**, et al.

**Keywords:** Low-rank Tensor Recovery · Non-convex Regularization · Deep Prior

---

<sup>‡</sup> Equal contribution.

# 📖 Education

- **2025.09 – 2028.06 (Expected):** M.S. in Artificial Intelligence, **University of Chinese Academy of Sciences (UCAS)**, Hangzhou Institute for Advanced Study.
- **2021.09 – 2025.06:** B.S. in Data Science and Big Data Technology, **Beijing Sport University**, School of Sports Engineering.

# 🏅 Honors and Awards

- **National Encouragement Scholarship**.
- **Third Prize**, Computer Design Competition.

# 💻 Technical Skills

- **Programming:** Python, PyTorch, Linux, and Git.
- **LLM Post-training:** SFT, DPO, GRPO, and FSDP-based distributed training.
- **Training Frameworks:** LLaMAFactory and DeepSpeed.
- **Model Experience:** Training and fine-tuning LLaMA, Qwen, and Gemma models.
- **Development Tools:** Codex-assisted programming.
- **English Proficiency:** CET-4: 575; CET-6: 485.
