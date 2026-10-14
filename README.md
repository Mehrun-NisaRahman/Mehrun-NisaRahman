<div align="center">

<img src="banner.svg" alt="Mehrun-Nisa Rahman: human-in-the-loop, multi-agent, vision-language" width="100%">

</div>

## 👋 About me

Computer Science student who enjoys turning course concepts into working projects, from database-backed web apps and 3D games to machine-learning pipelines. My thesis work looks at how **AI agents and human researchers can work together** on multimodal data.

- 🎓 Studying Computer Science at BRAC University
- 🔬 Working on my B.Sc. thesis on human-in-the-loop multi-agent vision-language models
- 🌱 Getting better at software engineering, machine learning, and clean code
- 🤝 Open to collaborating on projects and research

## 🔬 Current research

### Human-in-the-Loop Multi-Agent Vision-Language Framework for Qualitative Coding

Qualitative coding is slow, and most AI tools only read text even though real data (product reviews, Airbnb listings) comes with images. My thesis team and I are testing whether a **human-in-the-loop, multi-agent vision-language framework** can produce qualitative codes that are **more accurate and more explainable** than a single-agent VLM, under a matched token budget.

Each agent has one job, and human researchers can accept, edit, or reject the output at key stages:

```mermaid
flowchart LR
    D([Text + images]) --> P[Preprocess]
    P --> C[Code]
    C --> L[Link text and image]
    L --> T[Themes]
    T --> V[Validate]
    V --> E[Explain]
    E --> R([Report])
    H{{Human review}}
    C -.-> H
    T -.-> H
    V -.-> H
    H -.->|accept / edit / reject| C
    classDef agent fill:#0b1020,stroke:#22d3ee,stroke-width:2px,color:#e0f2fe
    classDef human fill:#f59e0b,stroke:#b45309,color:#1c1917
    classDef io fill:#1a1f4a,stroke:#a78bfa,color:#ede9fe
    class P,C,L,T,V,E agent
    class H human
    class D,R io
```

`Multimodal AI` `Vision-Language Models` `Multi-Agent Systems` `Explainability` `Human-AI Collaboration`

## 🛠️ Tech I've worked with

![Python](https://img.shields.io/badge/Python-111633?style=for-the-badge&logo=python&logoColor=22d3ee)
![scikit-learn](https://img.shields.io/badge/scikit--learn-111633?style=for-the-badge&logo=scikitlearn&logoColor=22d3ee)
![Pandas](https://img.shields.io/badge/Pandas-111633?style=for-the-badge&logo=pandas&logoColor=22d3ee)
![OpenGL](https://img.shields.io/badge/OpenGL-111633?style=for-the-badge&logo=opengl&logoColor=22d3ee)
![JavaScript](https://img.shields.io/badge/JavaScript-111633?style=for-the-badge&logo=javascript&logoColor=a78bfa)
![PHP](https://img.shields.io/badge/PHP-111633?style=for-the-badge&logo=php&logoColor=a78bfa)
![MySQL](https://img.shields.io/badge/MySQL-111633?style=for-the-badge&logo=mysql&logoColor=a78bfa)
![Git](https://img.shields.io/badge/Git-111633?style=for-the-badge&logo=git&logoColor=fbbf24)
![GitHub](https://img.shields.io/badge/GitHub-111633?style=for-the-badge&logo=github&logoColor=fbbf24)

## 📂 Featured projects

### 🏨 [Hotel Booking Status Classification (CSE422, AI)](https://github.com/Mehrun-NisaRahman/cse422-project)
A machine-learning project that predicts whether a hotel booking ends in check-out, cancellation, or no-show. Compares KNN, Logistic Regression, Naive Bayes, and a neural network on 119K bookings, with K-Means clustering on top. Reached 83% accuracy and 0.91 AUC.
`Python` `scikit-learn` `pandas`

### 🏍️ [Traffic Rider (CSE423, Computer Graphics)](https://github.com/Mehrun-NisaRahman/cse423-project)
A 3D endless-runner game built with Python and PyOpenGL. Dodge rocks across three lanes, collect coins and fuel, and survive as the difficulty ramps up. Includes a day/night cycle, boost mode, and first- and third-person cameras.
`Python` `PyOpenGL` `GLUT`

### 🛒 [Online Inventory & Order Management (CSE370, Databases)](https://github.com/Mehrun-NisaRahman/CSE370-Project-Section-07)
A buyer/seller web platform with product listings, a shopping cart, checkout and payments, order memos, and a quiz that earns buyers a discount. Backed by a relational MySQL schema.
`PHP` `MySQL`

### 🔧 [FixIt (CSE470, Software Engineering)](https://github.com/Sahela-Khan/FixIt-A-Local-Home-Services-Booking-Platform)
A platform where homeowners can browse and book local service providers such as electricians, plumbers, and cleaners, and track job status in real time. Built as a team project.
`JavaScript`

## 📫 Get in touch

[![Email](https://img.shields.io/badge/Email-111633?style=for-the-badge&logo=gmail&logoColor=22d3ee)](mailto:mehrunnisarahmanety@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-111633?style=for-the-badge&logo=linkedin&logoColor=22d3ee)](https://www.linkedin.com/in/mehrun-nisa-rahman-a42566242/)
[![X](https://img.shields.io/badge/X-111633?style=for-the-badge&logo=x&logoColor=22d3ee)](https://x.com/mehrun_nisa_)
[![Facebook](https://img.shields.io/badge/Facebook-111633?style=for-the-badge&logo=facebook&logoColor=22d3ee)](https://www.facebook.com/mehrunnisarahman.ety)

---

<div align="center">⭐ Thanks for stopping by!</div>
