<div align="center">

<img src="banner.svg" alt="Mehrun-Nisa Rahman: CS student, AI/ML and software engineering, open to work" width="100%">

![Status](https://img.shields.io/badge/STATUS-OPEN%20TO%20WORK-22c55e?style=for-the-badge&labelColor=0b1020)
[![Email](https://img.shields.io/badge/Email-111633?style=for-the-badge&logo=gmail&logoColor=22d3ee)](mailto:mehrunnisarahmanety@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-111633?style=for-the-badge&logo=linkedin&logoColor=22d3ee)](https://www.linkedin.com/in/mehrun-nisa-rahman-a42566242/)
[![X](https://img.shields.io/badge/X-111633?style=for-the-badge&logo=x&logoColor=22d3ee)](https://x.com/mehrun_nisa_)

</div>

## 👋 Hi, I'm Mehrun-Nisa

Computer Science student at **BRAC University** focused on **machine learning and software engineering**. I build things end to end: a database-backed marketplace, an ML pipeline on 119K records, a 3D game, and a team platform for booking home services. My thesis explores **AI agents that work alongside human researchers** on text and image data.

## 🎯 Open to

| Looking for | Where I can help |
| --- | --- |
| **AI / ML roles** | Data preparation, model training and fair evaluation, working with imbalanced data |
| **Software engineering roles** | Full-stack features, relational database design, working in a team |
| **Research assistant roles** | Multimodal AI, vision-language models, human-AI collaboration |

I'm available for internships and entry-level positions. The fastest way to reach me is by [email](mailto:mehrunnisarahmanety@gmail.com) or [LinkedIn](https://www.linkedin.com/in/mehrun-nisa-rahman-a42566242/).

## ⚡ Highlights

- 🧠 **Machine learning:** compared 4 models on 119K hotel bookings, reaching 83% accuracy and 0.91 AUC. I removed target-leakage columns and judged models on macro F1 and balanced accuracy, because only 1% of the data was the rare class.
- 🗄️ **Databases:** designed an 11-table relational MySQL schema for a buyer/seller marketplace with a cart, checkout, payments, and a quiz-based discount engine.
- 🎮 **Graphics:** built a 3D endless-runner game in Python and PyOpenGL with collisions, fuel and coin mechanics, a day/night cycle, and two camera modes.
- 👥 **Teamwork:** worked in teams on a home-services booking platform and on my thesis.
- 🔬 **Research:** designing a human-in-the-loop multi-agent vision-language framework, evaluated against a single-agent baseline with matched token budgets.

## 🧭 From coursework to thesis

<div align="center">

<img src="journey.svg" alt="Databases, machine learning, graphics and software engineering projects feeding into a human-in-the-loop multi-agent vision-language thesis" width="100%">

</div>

## 🛠️ Skills

| Area | Tools and techniques |
| --- | --- |
| **Languages** | Python · JavaScript · PHP · SQL |
| **ML and data** | scikit-learn · pandas · NumPy · matplotlib · seaborn |
| **Modelling** | Classification · K-Means clustering · neural networks (MLP) · ROC-AUC and macro F1 on imbalanced data |
| **Web and databases** | MySQL schema design · PHP back end · JavaScript |
| **Graphics** | OpenGL through PyOpenGL |
| **Tools** | Git · GitHub · Jupyter / Colab |
| **Exploring now** | Vision-language models · multi-agent systems · explainable AI |

![Python](https://img.shields.io/badge/Python-111633?style=for-the-badge&logo=python&logoColor=22d3ee)
![scikit-learn](https://img.shields.io/badge/scikit--learn-111633?style=for-the-badge&logo=scikitlearn&logoColor=22d3ee)
![Pandas](https://img.shields.io/badge/Pandas-111633?style=for-the-badge&logo=pandas&logoColor=22d3ee)
![OpenGL](https://img.shields.io/badge/OpenGL-111633?style=for-the-badge&logo=opengl&logoColor=f472b6)
![JavaScript](https://img.shields.io/badge/JavaScript-111633?style=for-the-badge&logo=javascript&logoColor=34d399)
![PHP](https://img.shields.io/badge/PHP-111633?style=for-the-badge&logo=php&logoColor=a78bfa)
![MySQL](https://img.shields.io/badge/MySQL-111633?style=for-the-badge&logo=mysql&logoColor=a78bfa)
![Git](https://img.shields.io/badge/Git-111633?style=for-the-badge&logo=git&logoColor=fbbf24)
![GitHub](https://img.shields.io/badge/GitHub-111633?style=for-the-badge&logo=github&logoColor=fbbf24)

## 📂 Projects

| Project | What it does | Results and highlights | Stack |
| --- | --- | --- | --- |
| [**Hotel Booking Status Classification**](https://github.com/Mehrun-NisaRahman/cse422-project) | Predicts whether a hotel booking ends in check-out, cancellation, or no-show | 119K bookings, 4 models plus K-Means, 83% accuracy, 0.91 AUC, leakage and class imbalance handled | `Python` `scikit-learn` `pandas` |
| [**Online Inventory & Order Management**](https://github.com/Mehrun-NisaRahman/CSE370-Project-Section-07) | Buyer/seller marketplace with products, cart, checkout, payments, and order memos | 11-table relational schema, role-based dashboards, quiz-based discount engine | `PHP` `MySQL` |
| [**Traffic Rider**](https://github.com/Mehrun-NisaRahman/cse423-project) | 3D endless-runner game with lanes, obstacles, coins, and fuel | Day/night cycle, boost mode, first- and third-person cameras | `Python` `PyOpenGL` |
| [**FixIt**](https://github.com/Sahela-Khan/FixIt-A-Local-Home-Services-Booking-Platform) | Platform for booking local electricians, plumbers, and cleaners and tracking job status | Built as a team project with real-time job tracking | `JavaScript` |

## 🔬 Thesis: Human-in-the-Loop Multi-Agent Vision-Language Framework

Qualitative coding is slow, and most AI tools only read text even though real data (product reviews, Airbnb listings) comes with images. My thesis team and I are investigating whether a **human-in-the-loop, multi-agent vision-language framework** can produce qualitative codes that are **more accurate and more explainable** than a single-agent VLM, under a matched token budget.

Seven specialised agents each have one job. Human researchers review the output after coding and after theme extraction, and can accept, edit, or reject it. Every code and theme points back to its text and image evidence.

```mermaid
flowchart LR
    D([Text + images]) --> P[Preprocess]
    P --> C[Code]
    C --> H1{{Human review}}
    H1 --> X[Cross-modal reasoning]
    X --> T[Theme extraction]
    T --> H2{{Human review}}
    H2 --> V[Validate]
    V --> E[Explain]
    E --> R([Report])
    H1 -.->|reject / edit| C
    H2 -.->|reject / edit| T
    classDef agent fill:#0b1020,stroke:#22d3ee,stroke-width:2px,color:#e0f2fe
    classDef human fill:#f59e0b,stroke:#b45309,color:#1c1917
    classDef io fill:#1a1f4a,stroke:#a78bfa,color:#ede9fe
    class P,C,X,T,V,E agent
    class H1,H2 human
    class D,R io
```

**How it will be evaluated**
- Compared against a **single-agent VLM** with the same codebook and the **same token budget**, and against a **classical ML baseline** trained on CLIP features
- Agreement with human coders: Cohen's κ, Krippendorff's α, and F1-score
- Explanation quality rated by experts, plus efficiency (runtime, token cost, review time) and usability (SUS)
- Ablation studies to see which parts really help, and an ethics analysis of bias, transparency, accountability, and over-trust in AI
- Data: public multimodal datasets such as Amazon product reviews with images, Yelp, and Airbnb listings

`Multimodal AI` `Vision-Language Models` `Multi-Agent Systems` `Explainability` `Human-AI Collaboration`

## 🤝 How I work

- 🔍 **I check before I trust a number.** Leakage, class imbalance, and the right metrics come before any accuracy claim.
- ⚖️ **I compare fairly.** Matched budgets and proper baselines, so gains come from the design.
- 🧑‍🤝‍🧑 **I keep people in control.** AI output should be reviewable, explainable, and easy to correct.

## 📫 Let's talk

I'm open to internships and entry-level roles in AI/ML and software engineering. If you're hiring or want to collaborate, I'd love to hear from you.

[![Email](https://img.shields.io/badge/Email-111633?style=for-the-badge&logo=gmail&logoColor=22d3ee)](mailto:mehrunnisarahmanety@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-111633?style=for-the-badge&logo=linkedin&logoColor=22d3ee)](https://www.linkedin.com/in/mehrun-nisa-rahman-a42566242/)
[![X](https://img.shields.io/badge/X-111633?style=for-the-badge&logo=x&logoColor=22d3ee)](https://x.com/mehrun_nisa_)
[![Facebook](https://img.shields.io/badge/Facebook-111633?style=for-the-badge&logo=facebook&logoColor=22d3ee)](https://www.facebook.com/mehrunnisarahman.ety)

<!-- To add your resume, delete this line's comment markers and replace YOUR_RESUME_LINK:
[![Resume](https://img.shields.io/badge/Resume-111633?style=for-the-badge&logo=readthedocs&logoColor=fbbf24)](YOUR_RESUME_LINK)
-->

---

<div align="center">⭐ Thanks for stopping by!</div>
