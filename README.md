<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="banner-dark.svg">
  <img src="banner-light.svg" alt="Mehrun-Nisa Rahman: B.Sc. in Computer Science at BRAC University. AI, machine learning and software engineering. Open to work." width="100%">
</picture>

<picture><source media="(prefers-color-scheme: dark)" srcset="btn-status-dark.svg"><img src="btn-status-light.svg" alt="Status: open to work" height="44"></picture>
<a href="mailto:mehrunnisarahmanety@gmail.com"><picture><source media="(prefers-color-scheme: dark)" srcset="btn-email-dark.svg"><img src="btn-email-light.svg" alt="Email" height="44"></picture></a>
<a href="https://www.linkedin.com/in/mehrun-nisa-rahman-a42566242/"><picture><source media="(prefers-color-scheme: dark)" srcset="btn-linkedin-dark.svg"><img src="btn-linkedin-light.svg" alt="LinkedIn" height="44"></picture></a>
<a href="https://x.com/mehrun_nisa_"><picture><source media="(prefers-color-scheme: dark)" srcset="btn-x-dark.svg"><img src="btn-x-light.svg" alt="X" height="44"></picture></a>

</div>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="divider-dark.svg">
  <img src="divider-light.svg" alt="" width="100%">
</picture>

## About me

I'm **Mehrun-Nisa Rahman**, a Computer Science student at **BRAC University** who loves turning ideas into working software. I build things end to end: a **database-backed marketplace**, a **machine-learning pipeline on 119K records**, a **3D game**, and a **team platform for booking home services**. My thesis explores **AI agents that work alongside human researchers** on text and image data.

> [!IMPORTANT]
> **I'm open to work.** I'm looking for **internships and entry-level roles** in **AI / machine learning** and **software engineering**. The quickest way to reach me is [email](mailto:mehrunnisarahmanety@gmail.com) or [LinkedIn](https://www.linkedin.com/in/mehrun-nisa-rahman-a42566242/).

## What I'm looking for

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="roles-dark.svg">
  <img src="roles-light.svg" alt="Looking for roles in AI and machine learning, software engineering, and research assistance" width="100%">
</picture>

</div>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="divider-dark.svg">
  <img src="divider-light.svg" alt="" width="100%">
</picture>

## Projects

<p align="center">
  <a href="https://github.com/Mehrun-NisaRahman/cse422-project">
    <picture>
      <source media="(prefers-color-scheme: dark)" srcset="project-hotel-dark.svg">
      <img src="project-hotel-light.svg" width="49%" alt="Hotel Booking Status Classification: machine learning project comparing four models on 119K bookings, 83% accuracy and 0.91 AUC">
    </picture>
  </a>
  <a href="https://github.com/Mehrun-NisaRahman/CSE370-Project-Section-07">
    <picture>
      <source media="(prefers-color-scheme: dark)" srcset="project-market-dark.svg">
      <img src="project-market-light.svg" width="49%" alt="Online Inventory and Order Management: PHP and MySQL marketplace with an 11-table schema">
    </picture>
  </a>
  <a href="https://github.com/Mehrun-NisaRahman/cse423-project">
    <picture>
      <source media="(prefers-color-scheme: dark)" srcset="project-rider-dark.svg">
      <img src="project-rider-light.svg" width="49%" alt="Traffic Rider: 3D endless-runner game in Python and PyOpenGL">
    </picture>
  </a>
  <a href="https://github.com/Sahela-Khan/FixIt-A-Local-Home-Services-Booking-Platform">
    <picture>
      <source media="(prefers-color-scheme: dark)" srcset="project-fixit-dark.svg">
      <img src="project-fixit-light.svg" width="49%" alt="FixIt: team platform for booking local home services and tracking job status">
    </picture>
  </a>
</p>

<p align="center"><sub>Click any card to open the repository.</sub></p>

## Skills

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="skills-dark.svg">
  <img src="skills-light.svg" alt="Skills: Python, JavaScript, PHP, SQL, scikit-learn, pandas, NumPy, matplotlib, seaborn, classification, K-Means, neural networks, MySQL, OpenGL, Git, GitHub, Jupyter. Exploring vision-language models, multi-agent systems, and explainable AI." width="100%">
</picture>

</div>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="divider-dark.svg">
  <img src="divider-light.svg" alt="" width="100%">
</picture>

## From coursework to thesis

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="journey-dark.svg">
  <img src="journey-light.svg" alt="Databases, machine learning, graphics and software engineering projects feeding into a human-in-the-loop multi-agent vision-language thesis" width="100%">
</picture>

</div>

## Thesis: Human-in-the-Loop Multi-Agent Vision-Language Framework

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
    classDef agent fill:#E4DEFC,stroke:#7B68E0,stroke-width:2px,color:#26213F
    classDef human fill:#FBE3C6,stroke:#D98A2B,stroke-width:2px,color:#26213F
    classDef io fill:#CFF1E6,stroke:#3FAE8C,stroke-width:2px,color:#26213F
    class P,C,X,T,V,E agent
    class H1,H2 human
    class D,R io
```

**How it will be evaluated** (on public multimodal data such as Amazon reviews with images, Yelp, and Airbnb listings)

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="thesis-eval-dark.svg">
  <img src="thesis-eval-light.svg" alt="Evaluation plan: fair baselines, agreement with human coders, explainability and usability, ablations and ethics" width="100%">
</picture>

</div>

`Multimodal AI` `Vision-Language Models` `Multi-Agent Systems` `Explainability` `Human-AI Collaboration`

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="divider-dark.svg">
  <img src="divider-light.svg" alt="" width="100%">
</picture>

## How I work

> [!TIP]
> - **I check before I trust a number.** Leakage, class imbalance, and the right metrics come before any accuracy claim.
> - **I compare fairly.** Matched budgets and proper baselines, so gains come from the design.
> - **I keep people in control.** AI output should be reviewable, explainable, and easy to correct.

## Let's talk

If you're hiring or want to collaborate, I'd love to hear from you.

<p>
<a href="mailto:mehrunnisarahmanety@gmail.com"><picture><source media="(prefers-color-scheme: dark)" srcset="btn-email-dark.svg"><img src="btn-email-light.svg" alt="Email" height="44"></picture></a>
<a href="https://www.linkedin.com/in/mehrun-nisa-rahman-a42566242/"><picture><source media="(prefers-color-scheme: dark)" srcset="btn-linkedin-dark.svg"><img src="btn-linkedin-light.svg" alt="LinkedIn" height="44"></picture></a>
<a href="https://x.com/mehrun_nisa_"><picture><source media="(prefers-color-scheme: dark)" srcset="btn-x-dark.svg"><img src="btn-x-light.svg" alt="X" height="44"></picture></a>
<a href="https://www.facebook.com/mehrunnisarahman.ety"><picture><source media="(prefers-color-scheme: dark)" srcset="btn-facebook-dark.svg"><img src="btn-facebook-light.svg" alt="Facebook" height="44"></picture></a>
</p>

<!-- To add your resume, delete the comment markers around the next line and replace YOUR_RESUME_LINK:
[![Resume](https://img.shields.io/badge/Resume-0E7470?style=for-the-badge&logo=readthedocs&logoColor=white)](YOUR_RESUME_LINK)
-->

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="divider-dark.svg">
  <img src="divider-light.svg" alt="" width="100%">
</picture>

<div align="center">Thanks for stopping by.</div>
