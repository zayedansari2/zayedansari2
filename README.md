<div align="center">

<!-- Hero: animated glass banner -->
<img src="https://cdn.jsdelivr.net/gh/zayedansari2/zayedansari2@main/assets/banner.svg" width="100%" alt="Zayed Ansari — Backend Engineer"/>

<br/><br/>

<!-- Typing animation -->
<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=22&duration=2800&pause=800&color=38BDF8&center=true&vCenter=true&width=720&lines=SDE+Intern+%40+AWS+EC2+Health;Building+systems+that+scale;Fine-tuning+LLMs+%7C+RAG+%7C+LangChain;Distributed+backtesting+%7C+Step+Functions;Backend+%7C+infra+%7C+concurrency;" alt="Typing animation"/>

<br/><br/>

<!-- Social badges -->
<a href="https://linkedin.com/in/zayedansari"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white&labelColor=0A66C2"/></a>
<a href="https://github.com/zayedansari2"><img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white&labelColor=181717"/></a>
<a href="https://zayedansariportfolio.vercel.app/"><img src="https://img.shields.io/badge/Portfolio-000000?style=for-the-badge&logo=vercel&logoColor=white&labelColor=111827"/></a>

<br/><br/>

<img src="https://raw.githubusercontent.com/zayedansari2/zayedansari2/main/assets/divider.png" width="85%" alt=""/>

</div>

<!-- Glass morphism + motion styles -->
<style>
  @keyframes fadeUp {
    from { opacity: 0; transform: translateY(18px); }
    to   { opacity: 1; transform: translateY(0); }
  }
  @keyframes shimmer {
    0%   { background-position: 200% center; }
    100% { background-position: -200% center; }
  }
  @keyframes float {
    0%, 100% { transform: translateY(0); }
    50%      { transform: translateY(-4px); }
  }
  @keyframes glowPulse {
    0%, 100% { box-shadow: 0 0 0 rgba(56, 189, 248, 0); }
    50%      { box-shadow: 0 0 24px rgba(56, 189, 248, 0.15); }
  }

  .glass-card {
    background: linear-gradient(135deg, rgba(255,255,255,0.08) 0%, rgba(255,255,255,0.02) 100%);
    border: 1px solid rgba(255, 255, 255, 0.12);
    border-radius: 16px;
    padding: 20px 22px;
    animation: fadeUp 0.9s ease forwards, glowPulse 4s ease-in-out infinite;
    transition: transform 0.35s cubic-bezier(0.34, 1.56, 0.64, 1), border-color 0.3s ease;
  }
  .glass-card:hover {
    transform: translateY(-6px) scale(1.01);
    border-color: rgba(56, 189, 248, 0.35);
  }

  .section-title {
    font-size: 1.35em;
    font-weight: 700;
    background: linear-gradient(90deg, #e0f2fe, #38bdf8, #a78bfa, #e0f2fe);
    background-size: 200% auto;
    -webkit-background-clip: text;
    background-clip: text;
    color: transparent;
    animation: shimmer 6s linear infinite;
  }

  .stat-wrap {
    display: inline-block;
    padding: 12px;
    border-radius: 20px;
    background: rgba(255, 255, 255, 0.04);
    border: 1px solid rgba(255, 255, 255, 0.1);
    animation: float 5s ease-in-out infinite;
  }

  .code-block {
    background: linear-gradient(160deg, rgba(15, 37, 87, 0.6) 0%, rgba(2, 6, 23, 0.8) 100%);
    border: 1px solid rgba(56, 189, 248, 0.2);
    border-radius: 14px;
    padding: 18px 22px;
    animation: fadeUp 1s ease forwards;
  }

  .exp-meta {
    color: #64748b;
    font-size: 0.9em;
    margin-bottom: 10px;
  }
</style>

<br/>

## <span class="section-title">🖥️ About</span>

<div class="code-block">

```typescript
const zayed = {
  school:     "University of Washington — B.S. CS & Data Science, June 2027",
  coursework: ["DSA", "Systems Programming", "Databases & SQL", "HW/SW Interface"],
  experience: ["SDE Intern @ AWS EC2 Health", "CionSystems", "HeyMilo AI"],
  swe:        ["distributed systems", "backend infra", "databases", "concurrency"],
  ai:         ["LLM fine-tuning", "RAG pipelines", "agentic AI", "LangChain"],
  languages:  ["Java", "Python", "C/C++", "TypeScript", "SQL", "R"],
  location:   "Seattle, WA",
  portfolio:  "https://zayedansariportfolio.vercel.app/",
};
```

</div>

<div align="center">
  <img src="https://raw.githubusercontent.com/zayedansari2/zayedansari2/main/assets/divider.png" width="85%" alt=""/>
</div>

<br/>

## <span class="section-title">💼 Experience</span>

<table width="100%">
<tr>
<td width="100%" valign="top">

<div class="glass-card">

**Amazon Web Services (AWS)** · Software Development Engineer Intern, EC2 Health Analytics

<div class="exp-meta">Seattle, WA · June 2026 – Sep. 2026</div>

- Reduced Scaled Backtesting execution time by **over 95%** (10+ hours → under 30 min) across **200K+** historical EC2 failure events by rearchitecting into a distributed, event-driven pipeline
- Enabled massively parallel rule evaluation across **60+ days** of production failure data using **Step Functions (Distributed Map), SQS, Lambda, ECS Fargate, ECR**, with **OpenSearch** and **Redshift**
- Built a frontend dashboard and CLI with interactive visualizations to automate backtests, monitor distributed workflows, and surface classification diffs against production baselines

![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonaws&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Step Functions](https://img.shields.io/badge/Step_Functions-FF9900?style=flat-square&logo=amazonaws&logoColor=white)
![Lambda](https://img.shields.io/badge/Lambda-FF9900?style=flat-square&logo=awslambda&logoColor=white)

</div>

</td>
</tr>
<tr>
<td width="50%" valign="top">

<div class="glass-card">

**CionSystems** · Software Engineering Intern

<div class="exp-meta">Redmond, WA · June 2025 – Sep. 2025</div>

- Architected a multi-tenant **Microsoft 365** compliance platform in **ASP.NET Core** via **Microsoft Graph API**, processing **1,000+** policy resources per snapshot
- Engineered a property-level **JSON diff engine** reducing manual audit time by **80%** and enabling automated configuration drift detection
- Built async background services with cron scheduling for daily snapshot collection across production tenants, saving **10+ hours/week**

![ASP.NET](https://img.shields.io/badge/ASP.NET_Core-512BD4?style=flat-square&logo=dotnet&logoColor=white)
![Microsoft Graph](https://img.shields.io/badge/Microsoft_Graph-0078D4?style=flat-square&logo=microsoft&logoColor=white)

</div>

</td>
<td width="50%" valign="top">

<div class="glass-card">

**HeyMilo AI** · Software Engineer Intern

<div class="exp-meta">New York, NY · June 2024 – Sep. 2024</div>

- Developed Python modules for a multilingual **AI voice agent** supporting **500+** automated interviews/month across **10+** locales
- Optimized transcription and NLP pipelines via profiling and algorithmic improvements, reducing latency by **25%** and improving WER by **5%**

[![Repo](https://img.shields.io/badge/Code-AIVoiceAgent-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/zayedansari2/AIVoiceAgent)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![NLP](https://img.shields.io/badge/NLP-412991?style=flat-square&logo=openai&logoColor=white)

</div>

</td>
</tr>
</table>

<div align="center">
  <img src="https://raw.githubusercontent.com/zayedansari2/zayedansari2/main/assets/glass-frame.png" width="60%" alt=""/>
</div>

<br/>

## <span class="section-title">🚀 Projects</span>

<table width="100%">
<tr>
<td width="50%" valign="top">

<div class="glass-card">

**[📱 AI-Powered Product Intelligence Mobile App](https://github.com/zayedansari2/cf_ai_ZayedsApp)**

![React Native](https://img.shields.io/badge/React_Native-61DAFB?style=flat-square&logo=react&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Computer Vision](https://img.shields.io/badge/Computer_Vision-FF6B35?style=flat-square&logoColor=white)

Built full-stack mobile app with **React Native**, **Node.js**, auth, payments, and **PostgreSQL**; integrated computer vision and LLM pipelines for real-time product insights on environmental impact and supply chain transparency.

Led end-to-end startup execution — system design, AI validation, and business planning — advancing to the **UW Dempsey Startup Competition** (out of 200+ teams).

</div>

</td>
<td width="50%" valign="top">

<div class="glass-card">

**[🏎️ Formula 1 AI Retrieval & LLM Assistant](https://github.com/zayedansari2/F1-FinetunedLLM)**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![LLaMA](https://img.shields.io/badge/LLaMA-0467DF?style=flat-square&logo=meta&logoColor=white)
![ChromaDB](https://img.shields.io/badge/ChromaDB-FF6B35?style=flat-square&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)

Designed a **RAG pipeline** using **ChromaDB** and **LangChain** over structured and unstructured F1 data, improving answer relevance by **40%** over keyword-only baseline.

Fine-tuned a **LLaMA-based model** on a curated F1 dataset, reducing hallucination rate by **30%** on domain-specific factual queries vs. the base model.

</div>

</td>
</tr>
<tr>
<td width="100%" valign="top">

<div class="glass-card">

**🔍 Mini Search Engine**

![C](https://img.shields.io/badge/C-A8B9CC?style=flat-square&logo=c&logoColor=black)
![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![POSIX](https://img.shields.io/badge/POSIX_Threads-222222?style=flat-square)

Engineered a scalable search engine over **10,000+ documents** using inverted indexing, achieving sub-**12ms** query latency and sustaining **200+ concurrent connections** under load.

Built a multithreaded HTTP server with POSIX thread pooling and lock contention optimization, improving throughput **3×** over single-threaded baseline.

</div>

</td>
</tr>
</table>

<div align="center">
  <img src="https://raw.githubusercontent.com/zayedansari2/zayedansari2/main/assets/divider.png" width="85%" alt=""/>
</div>

<br/>

## <span class="section-title">🛠️ Tech Stack</span>

<div align="center">

<div class="glass-card" style="max-width: 920px; margin: 0 auto;">

**Languages**

![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![C/C++](https://img.shields.io/badge/C/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white)
![R](https://img.shields.io/badge/R-276DC3?style=flat-square&logo=r&logoColor=white)

<br/><br/>

**Frameworks & Backend**

[![React](https://skillicons.dev/icons?i=react)](https://react.dev)
[![Nextjs](https://skillicons.dev/icons?i=nextjs)](https://nextjs.org)
[![Nodejs](https://skillicons.dev/icons?i=nodejs)](https://nodejs.org)
[![FastAPI](https://skillicons.dev/icons?i=fastapi)](https://fastapi.tiangolo.com)
[![Spring](https://skillicons.dev/icons?i=spring)](https://spring.io)
![ASP.NET Core](https://img.shields.io/badge/ASP.NET_Core-512BD4?style=flat-square&logo=dotnet&logoColor=white)
![React Native](https://img.shields.io/badge/React_Native-61DAFB?style=flat-square&logo=react&logoColor=black)

<br/><br/>

**AI / ML**

![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white)
![Transformers](https://img.shields.io/badge/Transformers-FFD21E?style=flat-square&logo=huggingface&logoColor=black)
![RAG](https://img.shields.io/badge/RAG-7C3AED?style=flat-square&logoColor=white)
![LLM Fine-Tuning](https://img.shields.io/badge/LLM_Fine--Tuning-412991?style=flat-square&logo=openai&logoColor=white)
[![PyTorch](https://skillicons.dev/icons?i=pytorch)](https://pytorch.org)
[![TensorFlow](https://skillicons.dev/icons?i=tensorflow)](https://tensorflow.org)

<br/><br/>

**Tools & Infra**

[![Docker](https://skillicons.dev/icons?i=docker)](https://docker.com)
[![Kubernetes](https://skillicons.dev/icons?i=kubernetes)](https://kubernetes.io)
[![Linux](https://skillicons.dev/icons?i=linux)](https://kernel.org)
[![Git](https://skillicons.dev/icons?i=git)](https://git-scm.com)
[![AWS](https://skillicons.dev/icons?i=aws)](https://aws.amazon.com)
[![Azure](https://skillicons.dev/icons?i=azure)](https://azure.microsoft.com)
![Cursor](https://img.shields.io/badge/Cursor-000000?style=flat-square&logoColor=white)
![MCP](https://img.shields.io/badge/MCP-38bdf8?style=flat-square&logoColor=white)

</div>

</div>

<div align="center">
  <img src="https://raw.githubusercontent.com/zayedansari2/zayedansari2/main/assets/divider.png" width="85%" alt=""/>
</div>

<br/>

## <span class="section-title">📊 Stats</span>

<div align="center">

<div class="stat-wrap">
  <img src="https://github-readme-stats.vercel.app/api?username=zayedansari2&show_icons=true&hide_border=true&bg_color=020617&title_color=38bdf8&icon_color=a78bfa&text_color=94a3b8&ring_color=38bdf8&include_all_commits=true&count_private=true" height="170" alt="GitHub stats"/>
</div>
&nbsp;&nbsp;
<div class="stat-wrap" style="animation-delay: 0.5s;">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=zayedansari2&layout=compact&hide_border=true&bg_color=020617&title_color=38bdf8&text_color=94a3b8&langs_count=8" height="170" alt="Top languages"/>
</div>

<br/><br/>

<div class="stat-wrap">
  <img src="https://streak-stats.demolab.com?user=zayedansari2&theme=dark&hide_border=true&background=020617&ring=38bdf8&fire=a78bfa&currStreakLabel=38bdf8&sideLabels=94a3b8&dates=475569&sideNums=e0f2fe" width="520" alt="GitHub streak"/>
</div>

<br/><br/>

<img src="https://github-readme-activity-graph.vercel.app/graph?username=zayedansari2&theme=react-dark&hide_border=true&area=true&point=38bdf8&line=a78bfa&color=38bdf8" width="96%" alt="Contribution graph"/>

</div>

<br/>

<div align="center">

![Views](https://komarev.com/ghpvc/?username=zayedansari2&color=38bdf8&style=flat-square&label=profile+views)

<br/><br/>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:1e3a5f,50:0f2557,100:020617&height=100&section=footer&animation=fadeIn" width="100%" alt="Footer wave"/>

<br/>

<sub>✦ <a href="https://zayedansariportfolio.vercel.app/">portfolio</a> · Seattle, WA ✦</sub>

</div>
