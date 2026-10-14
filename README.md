<div align="center">

<img src="banner.svg" alt="Mehrun-Nisa Rahman: databases, AI, graphics and software engineering leading to a human-in-the-loop AI thesis" width="100%">

</div>

## 👋 About me

I'm a Computer Science student at BRAC University who learns by building. So far that means a database-backed marketplace, a machine-learning pipeline, a 3D game, and a team platform for booking home services. My thesis now brings those threads together: **AI agents that work with human researchers** on text and image data.

- 🎓 B.Sc. in Computer Science and Engineering, BRAC University
- 🔬 Writing my thesis on human-in-the-loop multi-agent vision-language models
- 🤝 I work well in teams. Most of my projects, and my thesis, are group work
- 🌱 Always improving at software engineering, machine learning, and clean code

## 🧭 From coursework to thesis

<div align="center">

<img src="journey.svg" alt="Databases, AI, graphics and software engineering projects feeding into a human-in-the-loop multi-agent vision-language thesis" width="100%">

</div>

**How I like to work**
- 🔍 **Check before trusting a number.** In my ML project I removed target-leakage columns and judged models on macro F1 and balanced accuracy, because accuracy alone hid how badly the rare class was handled.
- ⚖️ **Compare fairly.** My thesis tests the multi-agent framework against a single-agent baseline with the *same token budget*, so any gain comes from the design and not from extra compute.
- 🧑‍🤝‍🧑 **Keep people in control.** AI output should be reviewable, explainable, and easy to correct.

## 🔬 Thesis: Human-in-the-Loop Multi-Agent Vision-Language Framework for Qualitative Coding

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

## 🛠️ Tech I've worked with

![Python](https://img.shields.io/badge/Python-111633?style=for-the-badge&logo=python&logoColor=22d3ee)
![scikit-learn](https://img.shields.io/badge/scikit--learn-111633?style=for-the-badge&logo=scikitlearn&logoColor=22d3ee)
![Pandas](https://img.shields.io/badge/Pandas-111633?style=for-the-badge&logo=pandas&logoColor=22d3ee)
![OpenGL](https://img.shields.io/badge/OpenGL-111633?style=for-the-badge&logo=opengl&logoColor=f472b6)
![JavaScript](https://img.shields.io/badge/JavaScript-111633?style=for-the-badge&logo=javascript&logoColor=34d399)
![PHP](https://img.shields.io/badge/PHP-111633?style=for-the-badge&logo=php&logoColor=a78bfa)
![MySQL](https://img.shields.io/badge/MySQL-111633?style=for-the-badge&logo=mysql&logoColor=a78bfa)
![Git](https://img.shields.io/badge/Git-111633?style=for-the-badge&logo=git&logoColor=fbbf24)
![GitHub](https://img.shields.io/badge/GitHub-111633?style=for-the-badge&logo=github&logoColor=fbbf24)

## 📂 Featured projects

### 🏨 [Hotel Booking Status Classification](https://github.com/Mehrun-NisaRahman/cse422-project)
A machine-learning project that predicts whether a hotel booking ends in check-out, cancellation, or no-show. Compares KNN, Logistic Regression, Naive Bayes, and a neural network on 119K bookings, with K-Means clustering on top. Reached 83% accuracy and 0.91 AUC.
`Python` `scikit-learn` `pandas`

### 🏍️ [Traffic Rider](https://github.com/Mehrun-NisaRahman/cse423-project)
A 3D endless-runner game built with Python and PyOpenGL. Dodge rocks across three lanes, collect coins and fuel, and survive as the difficulty ramps up. Includes a day/night cycle, boost mode, and first- and third-person cameras.
`Python` `PyOpenGL` `GLUT`

### 🛒 [Online Inventory & Order Management](https://github.com/Mehrun-NisaRahman/CSE370-Project-Section-07)
A buyer/seller web platform with product listings, a shopping cart, checkout and payments, order memos, and a quiz that earns buyers a discount. Backed by a relational MySQL schema.
`PHP` `MySQL`

### 🔧 [FixIt](https://github.com/Sahela-Khan/FixIt-A-Local-Home-Services-Booking-Platform)
A platform where homeowners can browse and book local service providers such as electricians, plumbers, and cleaners, and track job status in real time. Built as a team project.
`JavaScript`

## 📫 Get in touch

Open to collaborating on projects and research, so feel free to reach out!

[![Email](https://img.shields.io/badge/Email-111633?style=for-the-badge&logo=gmail&logoColor=22d3ee)](mailto:mehrunnisarahmanety@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-111633?style=for-the-badge&logo=linkedin&logoColor=22d3ee)](https://www.linkedin.com/in/mehrun-nisa-rahman-a42566242/)
[![X](https://img.shields.io/badge/X-111633?style=for-the-badge&logo=x&logoColor=22d3ee)](https://x.com/mehrun_nisa_)
[![Facebook](https://img.shields.io/badge/Facebook-111633?style=for-the-badge&logo=facebook&logoColor=22d3ee)](https://www.facebook.com/mehrunnisarahman.ety)

---

<div align="center">⭐ Thanks for stopping by!</div>
