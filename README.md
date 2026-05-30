<h1 align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=26&pause=1000&color=0E75B6&center=true&vCenter=true&width=620&lines=Hi%2C+I'm+Abdelghani+%F0%9F%91%8B;Software+Engineer+from+Algiers+%F0%9F%87%A9%F0%9F%87%BF;Turning+green+tea+into+code+%F0%9F%8D%B5+%E2%86%92+%F0%9F%92%BB" alt="Abdelghani Mahammedi" />
</h1>

<p align="center">
  <samp>I build <b>backend-heavy systems &amp; AI-assisted tools</b> — RAG pipelines · microservices · mobile apps</samp>
</p>

<p align="center">
  <a href="https://abdelghani-mahammedii.netlify.app/"><img src="https://img.shields.io/badge/Portfolio-0E75B6?style=for-the-badge&logo=netlify&logoColor=white" /></a>
  <a href="https://linkedin.com/in/abdelghani-mahammedi-9b329217a"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" /></a>
  <a href="https://stackoverflow.com/users/9180698/abdelghanymh"><img src="https://img.shields.io/badge/Stack_Overflow-F58025?style=for-the-badge&logo=stackoverflow&logoColor=white" /></a>
  <a href="https://drive.google.com/file/d/1kBJTVg34t_8tN2cCum9po8YGsklb5KAL/view?usp=sharing"><img src="https://img.shields.io/badge/Resume-4285F4?style=for-the-badge&logo=googledrive&logoColor=white" /></a>
  <a href="mailto:wboductqr@relay.firefox.com"><img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=maildotru&logoColor=white" /></a>
</p>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=abdelghanyMh&label=Profile%20views&color=0e75b6&style=flat-square" />
</p>

---

### 🧑‍💻 About Me

- 💼 **Software Engineer @ ENAGEO** — maintaining & optimizing core financial systems
- ⚙️ I build **backend-heavy systems and AI-assisted tools** — RAG pipelines, microservices & mobile apps
- 🧠 Currently going deep on **RAG systems**, **Python** & **Spring Boot**
- 🟢 **Open to backend / AI-engineering roles & collaborations**
- 🌐 Portfolio → **[abdelghani-mahammedii.netlify.app](https://abdelghani-mahammedii.netlify.app/)**
- ⚡ Fun fact: I respond faster than my API calls

---

### 🚀 Featured Projects

#### 🧠 Argo — Document-Intelligence RAG Platform

> A microservices **Retrieval-Augmented Generation** platform to search and chat over documents.

- 🔎 **Hybrid retrieval** — **PostgreSQL + pgvector** (semantic / embeddings) **+ OpenSearch** (keyword / BM25)
- 🤖 **Multi-LLM** RAG service — **OpenAI**, **Anthropic** & **Ollama** (local) behind a single interface
- 🧩 **FastAPI** microservices (`auth` · `document` · `ingestion` · `rag` · `tasks`) behind an **API gateway**
- 🗄️ **MinIO** object storage · **JWT** auth · fully **Dockerized** with health checks

<details>
<summary>🏗️ <b>Architecture</b> (click to expand)</summary>

<br/>

```mermaid
flowchart LR
    U([User]) --> FE[Web Frontend]
    FE --> GW[API Gateway]

    GW --> AUTH[Auth Service]
    GW --> DOC[Document Service]
    GW --> ING[Ingestion Service]
    GW --> RAG[RAG Service]
    GW --> TASK[Tasks Service]

    DOC --> S3[(MinIO<br/>Object Store)]
    ING --> S3
    ING --> OS[(OpenSearch<br/>Keyword / BM25)]
    ING --> PG[(PostgreSQL<br/>+ pgvector)]
    RAG --> PG
    RAG --> LLM{{LLM Providers}}
    LLM --> OAI[OpenAI]
    LLM --> ANT[Anthropic]
    LLM --> OLL[Ollama · local]
```

</details>

#### 📱 Rahma — Cross-Platform Pharmacy App

> A modern mobile app built on a fully typed Expo stack.

| Layer | Tech |
| --- | --- |
| **Core** | Expo (SDK 53) · React Native 0.79 · React 19 · TypeScript |
| **UI / Nav** | Expo Router · NativeWind · Tailwind CSS v4 · `@rn-primitives` |
| **State / Data** | TanStack Query · Zustand · React Hook Form |
| **More** | i18n (expo-localization) · MMKV · Reanimated · EAS Build · Jest |

---

### 🛠️ Tech Stack

**AI Engineering & Tooling**

<p>
  <img src="https://img.shields.io/badge/RAG-4F46E5?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Vector%20Databases-FF6B6B?style=for-the-badge" />
  <img src="https://img.shields.io/badge/OpenAI%20API-412991?style=for-the-badge&logo=openai&logoColor=white" />
  <img src="https://img.shields.io/badge/Anthropic%20API-D97757?style=for-the-badge&logo=anthropic&logoColor=white" />
  <img src="https://img.shields.io/badge/Ollama-000000?style=for-the-badge&logo=ollama&logoColor=white" />
  <img src="https://img.shields.io/badge/Claude%20Code-D97757?style=for-the-badge&logo=anthropic&logoColor=white" />
  <img src="https://img.shields.io/badge/GitHub%20Copilot-181717?style=for-the-badge&logo=githubcopilot&logoColor=white" />
  <img src="https://img.shields.io/badge/Cursor-000000?style=for-the-badge&logo=cursor&logoColor=white" />
</p>

**Languages**

<p>
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white" />
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" />
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/PHP-777BB4?style=for-the-badge&logo=php&logoColor=white" />
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" />
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" />
</p>

**Frontend & Mobile**

<p>
  <img src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" />
  <img src="https://img.shields.io/badge/React_Native-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" />
  <img src="https://img.shields.io/badge/Expo-000020?style=for-the-badge&logo=expo&logoColor=white" />
  <img src="https://img.shields.io/badge/Angular-DD0031?style=for-the-badge&logo=angular&logoColor=white" />
  <img src="https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white" />
</p>

**Backend**

<p>
  <img src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white" />
  <img src="https://img.shields.io/badge/Spring%20Boot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white" />
  <img src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white" />
  <img src="https://img.shields.io/badge/Express-000000?style=for-the-badge&logo=express&logoColor=white" />
  <img src="https://img.shields.io/badge/Laravel-FF2D20?style=for-the-badge&logo=laravel&logoColor=white" />
  <img src="https://img.shields.io/badge/Odoo-714B67?style=for-the-badge&logo=odoo&logoColor=white" />
</p>

**Data & Infrastructure**

<p>
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white" />
  <img src="https://img.shields.io/badge/pgvector-4169E1?style=for-the-badge&logo=postgresql&logoColor=white" />
  <img src="https://img.shields.io/badge/OpenSearch-005EB8?style=for-the-badge&logo=opensearch&logoColor=white" />
  <img src="https://img.shields.io/badge/MinIO-C72E49?style=for-the-badge&logo=minio&logoColor=white" />
  <img src="https://img.shields.io/badge/Oracle-F80000?style=for-the-badge&logo=oracle&logoColor=white" />
  <img src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white" />
  <img src="https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" />
</p>

**Tools & IDEs**

<p>
  <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" />
  <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" />
  <img src="https://img.shields.io/badge/GitLab-FC6D26?style=for-the-badge&logo=gitlab&logoColor=white" />
  <img src="https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black" />
  <img src="https://img.shields.io/badge/IntelliJ%20IDEA-000000?style=for-the-badge&logo=intellijidea&logoColor=white" />
  <img src="https://img.shields.io/badge/VS%20Code-007ACC?style=for-the-badge&logo=visualstudiocode&logoColor=white" />
  <img src="https://img.shields.io/badge/Figma-F24E1E?style=for-the-badge&logo=figma&logoColor=white" />
</p>

---

### 📊 GitHub Stats

<p align="center">
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=abdelghanyMh&show_icons=true&count_private=true&hide_border=true&theme=tokyonight" alt="Abdelghani's GitHub stats" />
  <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs?username=abdelghanyMh&layout=compact&hide_border=true&theme=tokyonight&langs_count=8" alt="Top languages" />
</p>

<p align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=abdelghanyMh&hide_border=true&theme=tokyonight" alt="GitHub streak" />
</p>

---

<p align="center">
  <i>📫 Reach me at <b>wboductqr@relay.firefox.com</b> — I'll get back faster than a cold start. ❄️</i>
</p>
