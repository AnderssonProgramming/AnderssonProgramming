<a id="top"></a>

<div align="center">

<!-- Hero: hand-built animated SVG, lives in this repo (no third-party service) -->
<a href="https://anderssonprogramming.github.io">
  <img src="./assets/hero.svg" width="100%" alt="Andersson David Sánchez Méndez — Full-Stack Developer · QA and Software Engineering at Accenture · Systems Engineering Student at ECI · Teaching and Research Assistant · Bogotá, Colombia"/>
</a>

<br/><br/>

<!-- Primary actions -->
<a href="https://anderssonprogramming.github.io"><img src="https://img.shields.io/badge/Portfolio-FF8C00?style=for-the-badge&logo=googlechrome&logoColor=white" alt="Portfolio"/></a>
<a href="https://www.linkedin.com/in/anderssonsm/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logoColor=white" alt="LinkedIn"/></a>
<a href="https://leetcode.com/u/ander14_73/"><img src="https://img.shields.io/badge/LeetCode-1F222E?style=for-the-badge&logo=leetcode&logoColor=FFA116" alt="LeetCode"/></a>
<a href="https://www.hackerrank.com/profile/ander14_73"><img src="https://img.shields.io/badge/HackerRank-1F222E?style=for-the-badge&logo=hackerrank&logoColor=00EA64" alt="HackerRank"/></a>
<a href="https://www.researchgate.net/profile/Andersson-Sanchez-Mendez"><img src="https://img.shields.io/badge/ResearchGate-1F222E?style=for-the-badge&logo=researchgate&logoColor=00CCBB" alt="ResearchGate"/></a>

<br/>

<!-- Social proof -->
<a href="https://github.com/AnderssonProgramming?tab=followers"><img src="https://img.shields.io/github/followers/AnderssonProgramming?style=flat-square&logo=github&logoColor=white&label=followers&color=A855F7&labelColor=1F222E" alt="Followers"/></a>
<a href="https://github.com/AnderssonProgramming?tab=repositories&sort=stargazers"><img src="https://img.shields.io/github/stars/AnderssonProgramming?style=flat-square&logo=github&logoColor=white&label=stars&color=FF8C00&labelColor=1F222E" alt="Stars"/></a>
<a href="https://github.com/AnderssonProgramming"><img src="https://komarev.com/ghpvc/?username=AnderssonProgramming&style=flat-square&color=FF3D81&label=profile+views" alt="Profile views"/></a>

<br/><br/>

<a href="#-about-me">About</a> ·
<a href="#-how-i-build">How I build</a> ·
<a href="#-tech-stack-universe">Stack</a> ·
<a href="#-featured-projects">Projects</a> ·
<a href="#-github-analytics">Analytics</a> ·
<a href="#-currently-learning--exploring">Learning</a> ·
<a href="#-lets-connect--collaborate">Connect</a>

</div>

<img src="./assets/divider.svg" width="100%" alt=""/>

## 🌟 About Me

I build products end to end — from the first Figma frame to the pipeline that ships it — and then I try to break them before production does. By day I work in **QA and custom software engineering at Accenture**; by night I'm finishing **Systems Engineering at ECI**, teaching the next cohort how to model databases and think in objects, and building **agentic AI systems** in the open.

<table>
<tr>
<td width="50%" valign="top">

### 💼 Professional Profile

💜 **Custom Software Engineering Associate**  
🧪 QA Support as Accenture intern

🎓 **Systems Engineering Student**  
📍 *Escuela Colombiana de Ingeniería Julio Garavito*

🧑‍🏫 **Teaching and Research Assistant**  
📊 Database Modeling & Object-Oriented Programming

🔍 Collaborative Development & Innovation

</td>
<td width="50%" valign="top">

### ⚡ Core Values

```typescript
const andersson = {
  values: ["Discipline", "Dedication", "Teamwork"],
  traits: ["Leadership", "Passion", "Communication"],
  lifestyle: {
    fitness: "Gym enthusiast 💪",
    sports: "Basketball player 🏀",
    endurance: "Long-distance runner 🏃",
    freedom: "Motorcycle rider 🏍️",
    party: "Dancer lover 🕺"
  }
};
```

</td>
</tr>
</table>

### 🧭 What I bring to a team

<table>
<tr>
<td width="25%" valign="top">

**🎨 Product-minded UI**

Interfaces that feel calm and obvious: design tokens, motion with purpose, responsive by default.

</td>
<td width="25%" valign="top">

**⚙️ Solid backends**

REST, microservices and serverless on Spring Boot, NestJS and FastAPI — secured with JWT, OAuth 2.0 and Auth0.

</td>
<td width="25%" valign="top">

**🤖 Agentic AI**

Multi-agent pipelines, RAG and coding-agent harnesses with Claude, LangGraph, LangChain and local models.

</td>
<td width="25%" valign="top">

**🛡️ A QA mindset**

Tests first, DevSecOps always: SAST, DAST, threat modeling and CI gates that say no when they should.

</td>
</tr>
</table>

<img src="./assets/divider.svg" width="100%" alt=""/>

## 🔁 How I build

Every project follows the same loop — and the quality gate is not optional.

```mermaid
flowchart LR
    design(["🎨 Design<br/>Figma · UX flows"]) --> front["🖥️ Frontend<br/>React · Next.js · Angular"]
    front --> api["⚙️ APIs<br/>Spring Boot · NestJS · FastAPI"]
    api --> data[("🗄️ Data<br/>PostgreSQL · MongoDB · Redis")]
    api --> ai["🤖 AI layer<br/>LLM agents · RAG"]
    data --> cloud["☁️ Cloud<br/>AWS · Azure · Docker"]
    ai --> cloud
    cloud --> gate{{"🧪 Quality gate<br/>Tests · DevSecOps · CI/CD"}}
    gate -->|ship| prod([🚀 Production])
    gate -.->|feedback| design

    classDef orange fill:#FF8C00,stroke:#FF8C00,color:#0D1117,font-weight:bold
    classDef pink fill:#FF3D81,stroke:#FF3D81,color:#FFFFFF,font-weight:bold
    classDef purple fill:#8B3DF0,stroke:#8B3DF0,color:#FFFFFF,font-weight:bold
    classDef dark fill:#1F222E,stroke:#FF8C00,color:#FFFFFF
    class design,prod orange
    class front pink
    class api,data,ai,cloud purple
    class gate dark
```

<img src="./assets/divider.svg" width="100%" alt=""/>

## 🎨 Tech Stack Universe

The tools I reach for first, by layer. The complete inventory is one click below.

<table>
<tr>
<td width="18%"><b>🎯 Languages</b></td>
<td><img src="https://skillicons.dev/icons?i=ts,js,java,py,kotlin,c,r,haskell,bash,powershell" height="40" alt="TypeScript, JavaScript, Java, Python, Kotlin, C, R, Haskell, Bash, PowerShell"/></td>
</tr>
<tr>
<td><b>🖥️ Frontend</b></td>
<td><img src="https://skillicons.dev/icons?i=react,nextjs,angular,vite,tailwind,bootstrap,threejs,d3,html,css" height="40" alt="React, Next.js, Angular, Vite, Tailwind CSS, Bootstrap, Three.js, D3.js, HTML5, CSS3"/></td>
</tr>
<tr>
<td><b>⚙️ Backend</b></td>
<td><img src="https://skillicons.dev/icons?i=spring,nestjs,nodejs,fastapi,kafka,maven,gradle,jest,vitest,postman" height="40" alt="Spring, NestJS, Node.js, FastAPI, Kafka, Maven, Gradle, Jest, Vitest, Postman"/></td>
</tr>
<tr>
<td><b>🗄️ Data</b></td>
<td><img src="https://skillicons.dev/icons?i=postgres,mongodb,mysql,redis,supabase,dynamodb" height="40" alt="PostgreSQL, MongoDB, MySQL, Redis, Supabase, DynamoDB"/></td>
</tr>
<tr>
<td><b>☁️ Cloud & DevOps</b></td>
<td><img src="https://skillicons.dev/icons?i=aws,azure,docker,kubernetes,terraform,nginx,githubactions,vercel,netlify,linux" height="40" alt="AWS, Azure, Docker, Kubernetes, Terraform, Nginx, GitHub Actions, Vercel, Netlify, Linux"/></td>
</tr>
<tr>
<td><b>🤖 AI & ML</b></td>
<td><img src="https://skillicons.dev/icons?i=tensorflow,sklearn,grafana,prometheus" height="40" alt="TensorFlow, scikit-learn, Grafana, Prometheus"/> &nbsp;<code>Claude</code> <code>OpenAI</code> <code>LangChain</code> <code>LangGraph</code> <code>Ollama</code> <code>Groq</code></td>
</tr>
<tr>
<td><b>🛠️ Craft</b></td>
<td><img src="https://skillicons.dev/icons?i=git,github,vscode,idea,pycharm,androidstudio,eclipse,figma,notion,latex" height="40" alt="Git, GitHub, VS Code, IntelliJ IDEA, PyCharm, Android Studio, Eclipse, Figma, Notion, LaTeX"/></td>
</tr>
</table>

<details>
<summary><b>🧰 Open the full toolbox (100+ technologies)</b></summary>
<br>

<b>🎯 Languages & Markup</b>
<br><br>

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white)
![Python](https://img.shields.io/badge/Python-14354C?style=for-the-badge&logo=python&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![Kotlin](https://img.shields.io/badge/Kotlin-0095D5?style=for-the-badge&logo=kotlin&logoColor=white)
![C](https://img.shields.io/badge/C-00599C?style=for-the-badge&logo=c&logoColor=white)
![R](https://img.shields.io/badge/R-276DC3?style=for-the-badge&logo=r&logoColor=white)
![Haskell](https://img.shields.io/badge/Haskell-5e5086?style=for-the-badge&logo=haskell&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=for-the-badge&logo=gnu-bash&logoColor=white)
![Shell](https://img.shields.io/badge/Shell-89e051?style=for-the-badge&logo=gnu-bash&logoColor=white)
![PowerShell](https://img.shields.io/badge/PowerShell-5391FE?style=for-the-badge&logo=powershell&logoColor=white)
![Markdown](https://img.shields.io/badge/Markdown-000000?style=for-the-badge&logo=markdown&logoColor=white)
![LaTeX](https://img.shields.io/badge/LaTeX-008080?style=for-the-badge&logo=latex&logoColor=white)
![JSON](https://img.shields.io/badge/JSON-000000?style=for-the-badge&logo=json&logoColor=white)
![XML](https://img.shields.io/badge/XML-E34F26?style=for-the-badge&logo=xml&logoColor=white)
![YAML](https://img.shields.io/badge/YAML-CB171E?style=for-the-badge&logo=yaml&logoColor=white)
![Windows](https://img.shields.io/badge/Windows-0078D6?style=for-the-badge&logo=windows&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)

<br><br>
<b>⚡ Frameworks & Libraries</b>
<br><br>

![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=next.js&logoColor=white)
![Angular](https://img.shields.io/badge/Angular-DD0031?style=for-the-badge&logo=angular&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-0F172A?style=for-the-badge&logo=tailwindcss&logoColor=38BDF8)
![Framer Motion](https://img.shields.io/badge/Framer_Motion-0055FF?style=for-the-badge&logo=framer&logoColor=white)
![Zustand](https://img.shields.io/badge/Zustand-443E38?style=for-the-badge&logo=react&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-43853D?style=for-the-badge&logo=node.js&logoColor=white)
![Spring](https://img.shields.io/badge/Spring-6DB33F?style=for-the-badge&logo=spring&logoColor=white)
![NestJS](https://img.shields.io/badge/NestJS-E0234E?style=for-the-badge&logo=nestjs&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![Bootstrap](https://img.shields.io/badge/Bootstrap-563D7C?style=for-the-badge&logo=bootstrap&logoColor=white)
![Three.js](https://img.shields.io/badge/Three.js-000000?style=for-the-badge&logo=three.js&logoColor=white)
![D3.js](https://img.shields.io/badge/D3.js-F9A03C?style=for-the-badge&logo=d3.js&logoColor=white)
![JUnit](https://img.shields.io/badge/JUnit-25A162?style=for-the-badge&logo=junit5&logoColor=white)
![Jest](https://img.shields.io/badge/Jest-C21325?style=for-the-badge&logo=jest&logoColor=white)
![Vitest](https://img.shields.io/badge/Vitest-6E9F18?style=for-the-badge&logo=vitest&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![SQLAlchemy](https://img.shields.io/badge/SQLAlchemy-D71F00?style=for-the-badge&logo=sqlalchemy&logoColor=white)
![Pydantic](https://img.shields.io/badge/Pydantic-E92063?style=for-the-badge&logo=pydantic&logoColor=white)
![Uvicorn](https://img.shields.io/badge/Uvicorn-499848?style=for-the-badge&logo=gunicorn&logoColor=white)
![Gradle](https://img.shields.io/badge/Gradle-02303A?style=for-the-badge&logo=gradle&logoColor=white)
![JWT](https://img.shields.io/badge/JWT-000000?style=for-the-badge&logo=json-web-tokens&logoColor=white)
![Auth0](https://img.shields.io/badge/Auth0-EB5424?style=for-the-badge&logo=auth0&logoColor=white)
![Bcrypt](https://img.shields.io/badge/Bcrypt-338833?style=for-the-badge&logo=lock&logoColor=white)
![Apache Kafka](https://img.shields.io/badge/Apache_Kafka-231F20?style=for-the-badge&logo=apachekafka&logoColor=white)
![gRPC](https://img.shields.io/badge/gRPC-244C5A?style=for-the-badge&logo=grpc&logoColor=white)
![WebSockets](https://img.shields.io/badge/WebSockets-010101?style=for-the-badge&logo=socketdotio&logoColor=white)

<br><br>
<b>🗄️ Databases & Cloud</b>
<br><br>

![MongoDB](https://img.shields.io/badge/MongoDB-4EA94B?style=for-the-badge&logo=mongodb&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-00000F?style=for-the-badge&logo=mysql&logoColor=white)
![Oracle](https://img.shields.io/badge/Oracle-F00000?style=for-the-badge&logo=oracle&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3ECF8E?style=for-the-badge&logo=supabase&logoColor=white)
![DynamoDB](https://img.shields.io/badge/DynamoDB-4053D6?style=for-the-badge&logo=amazondynamodb&logoColor=white)
![Pinecone](https://img.shields.io/badge/Pinecone-000000?style=for-the-badge&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-025E8C?style=for-the-badge&logo=database&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazon-aws&logoColor=white)
![Azure](https://img.shields.io/badge/Azure-0078D4?style=for-the-badge&logo=microsoft-azure&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white)
![Netlify](https://img.shields.io/badge/Netlify-00C7B7?style=for-the-badge&logo=netlify&logoColor=white)
![Render](https://img.shields.io/badge/Render-000000?style=for-the-badge&logo=render&logoColor=white)
![Railway](https://img.shields.io/badge/Railway-0B0D0E?style=for-the-badge&logo=railway&logoColor=white)
![GitHub Pages](https://img.shields.io/badge/GitHub_Pages-222222?style=for-the-badge&logo=github&logoColor=white)
![Red Hat](https://img.shields.io/badge/Red_Hat-EE0000?style=for-the-badge&logo=red-hat&logoColor=white)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=for-the-badge&logo=nginx&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-844FBA?style=for-the-badge&logo=terraform&logoColor=white)

<br><br>
<b>🤖 AI & Machine Learning</b>
<br><br>

![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white)
![XGBoost](https://img.shields.io/badge/XGBoost-1A6FB5?style=for-the-badge&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=for-the-badge&logo=openai&logoColor=white)
![Claude](https://img.shields.io/badge/Claude-CC9B7A?style=for-the-badge&logo=anthropic&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white)
![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=for-the-badge&logo=langgraph&logoColor=white)
![Hugging Face](https://img.shields.io/badge/Hugging_Face-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black)
![Ollama](https://img.shields.io/badge/Ollama-000000?style=for-the-badge&logo=ollama&logoColor=white)
![Groq](https://img.shields.io/badge/Groq_API-F55036?style=for-the-badge&logo=groq&logoColor=white)

<br><br>
<b>🛠️ Tools & DevOps</b>
<br><br>

![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)
![GitHub Desktop](https://img.shields.io/badge/GitHub_Desktop-8034A9?style=for-the-badge&logo=github&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2671E5?style=for-the-badge&logo=github-actions&logoColor=white)
![VS Code](https://img.shields.io/badge/VS_Code-007ACC?style=for-the-badge&logo=visual-studio-code&logoColor=white)
![IntelliJ IDEA](https://img.shields.io/badge/IntelliJ_IDEA-000000?style=for-the-badge&logo=intellij-idea&logoColor=white)
![PyCharm](https://img.shields.io/badge/PyCharm-000000?style=for-the-badge&logo=pycharm&logoColor=white)
![Android Studio](https://img.shields.io/badge/Android_Studio-3DDC84?style=for-the-badge&logo=android-studio&logoColor=white)
![Eclipse](https://img.shields.io/badge/Eclipse-2C2255?style=for-the-badge&logo=eclipse&logoColor=white)
![Maven](https://img.shields.io/badge/Maven-C71A36?style=for-the-badge&logo=apache-maven&logoColor=white)
![Poetry](https://img.shields.io/badge/Poetry-60A5FA?style=for-the-badge&logo=poetry&logoColor=white)
![Postman](https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white)
![Swagger](https://img.shields.io/badge/Swagger-85EA2D?style=for-the-badge&logo=swagger&logoColor=black)
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=for-the-badge&logo=prometheus&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=for-the-badge&logo=grafana&logoColor=white)
![Semgrep](https://img.shields.io/badge/Semgrep-1B2F3D?style=for-the-badge&logo=semgrep&logoColor=white)
![Trivy](https://img.shields.io/badge/Trivy-1904DA?style=for-the-badge&logo=trivy&logoColor=white)
![OWASP ZAP](https://img.shields.io/badge/OWASP_ZAP-00549E?style=for-the-badge&logo=zap&logoColor=white)
![n8n](https://img.shields.io/badge/n8n-EA4B71?style=for-the-badge&logo=n8n&logoColor=white)
![Cisco](https://img.shields.io/badge/Cisco-1BA0D7?style=for-the-badge&logo=cisco&logoColor=white)
![Notion](https://img.shields.io/badge/Notion-000000?style=for-the-badge&logo=notion&logoColor=white)
![Figma](https://img.shields.io/badge/Figma-F24E1E?style=for-the-badge&logo=figma&logoColor=white)
![Canva](https://img.shields.io/badge/Canva-00C4CC?style=for-the-badge&logo=canva&logoColor=white)
![Photopea](https://img.shields.io/badge/Photopea-18A497?style=for-the-badge&logo=photopea&logoColor=white)
![OBS Studio](https://img.shields.io/badge/OBS_Studio-302E31?style=for-the-badge&logo=obs-studio&logoColor=white)
![Opera](https://img.shields.io/badge/Opera-FF1B2D?style=for-the-badge&logo=opera&logoColor=white)
![Brave](https://img.shields.io/badge/Brave-FB542B?style=for-the-badge&logo=brave&logoColor=white)
![Unsplash](https://img.shields.io/badge/Unsplash-000000?style=for-the-badge&logo=unsplash&logoColor=white)
![Stack Overflow](https://img.shields.io/badge/Stack_Overflow-FE7A16?style=for-the-badge&logo=stack-overflow&logoColor=white)
![Slack](https://img.shields.io/badge/Slack-4A154B?style=for-the-badge&logo=slack&logoColor=white)
![SonarLint](https://img.shields.io/badge/SonarLint-CB2029?style=for-the-badge&logo=sonarlint&logoColor=white)
![Oh My Posh](https://img.shields.io/badge/Oh_My_Posh-4AB5F1?style=for-the-badge&logo=windows-terminal&logoColor=white)
![Neon](https://img.shields.io/badge/Neon-00E599?style=for-the-badge&logo=neon&logoColor=white)

</details>

<img src="./assets/divider.svg" width="100%" alt=""/>

## 🚀 Featured Projects

### 💎 Personal Projects

<table>
<tr>
<td width="50%" valign="top">

#### 🛡️ [Agentic Security Auditor](https://github.com/AnderssonProgramming/agentic-security-auditor)

A multi-agent security auditor for Node.js/TypeScript repos. It scans with npm audit, Trivy, Semgrep and Gitleaks, triages by CVSS, **auto-patches and validates the fixes**, then gates deployment in CI.

<code>Python</code> <code>LangGraph</code> <code>Claude</code> <code>DevSecOps</code> <code>GitHub Actions</code>

</td>
<td width="50%" valign="top">

#### 🎧 [Macenplast Voice Picking](https://github.com/AnderssonProgramming/macenplast-voice-picking)

Voice-guided warehouse picking: spoken Spanish instructions over a Bluetooth headset, barcode confirmation with **Poka-Yoke blocking**, and an offline-capable PWA.

<code>FastAPI</code> <code>PostgreSQL</code> <code>React</code> <code>TypeScript</code> <code>ElevenLabs</code>

</td>
</tr>
<tr>
<td width="50%" valign="top">

#### ✨ [TwitterLite Microservices & Auth0](https://github.com/AnderssonProgramming/secure-twitter-like-microservice-auth0)

An architectural evolution from a **Spring Boot monolith to a serverless AWS Lambda ecosystem**, secured with Auth0 and backed by DynamoDB and API Gateway.

<code>Java 17</code> <code>Spring Boot 3</code> <code>AWS Lambda</code> <code>DynamoDB</code> <code>Auth0</code>

</td>
<td width="50%" valign="top">

#### ⭐ [Enterprise-grade RAG System](https://github.com/AnderssonProgramming/rag-langchain-openai-pinecone)

A modular LangChain pipeline with **HuggingFace local embeddings** and Pinecone vector storage.

<code>Python</code> <code>LangChain</code> <code>OpenAI</code> <code>Pinecone</code> <code>HuggingFace</code>

</td>
</tr>
<tr>
<td width="50%" valign="top">

#### 👁️ [Digital Wellbeing Cloud Architecture](https://github.com/AnderssonProgramming/digital-wellbeing-cloud-architecture)

A distributed, event-driven platform to mitigate Computer Vision Syndrome: Kotlin edge ingestion, **Kafka streaming**, FastAPI microservices and XGBoost inference, provisioned with Terraform.

<code>Kafka</code> <code>FastAPI</code> <code>Kotlin</code> <code>XGBoost</code> <code>Terraform</code> <code>EKS</code>

</td>
<td width="50%" valign="top">

#### 💪 [Gym MVP — 3D Fitness App](https://github.com/AnderssonProgramming/gym-mvp)

Explore exercises by selecting body zones on an **interactive 3D model**, with sets, reps and media guides. Built by someone who actually goes to the gym.

<code>Next.js</code> <code>React Three Fiber</code> <code>Tailwind CSS</code> <code>TypeScript</code>

</td>
</tr>
<tr>
<td width="50%" valign="top">

#### 🍲 [Cocina para Uno — Dynamic Recipes](https://github.com/AnderssonProgramming/cda-front-developer)

Designed for solo cooks, it supports CRUD recipes — create, edit and favorite them with **real-time search**, category filters and local persistence. No backend required.

<code>HTML5</code> <code>CSS3</code> <code>JavaScript</code> <code>localStorage</code>

</td>
<td width="50%" valign="top">

#### ☁️ [Stock Products — Tracking with Maven](https://github.com/AnderssonProgramming/stock-products)

A stock tracking system that uses the **Observer pattern** for real-time notifications on stock changes.

<code>Java</code> <code>Maven</code> <code>Design Patterns</code>

</td>
</tr>
</table>

<details>
<summary><b>🔭 More to explore — agents, security, ML and product experiments</b></summary>
<br>

| Area | Project | What it is |
|:--|:--|:--|
| 🤖 Agents | [agentic-harness](https://github.com/AnderssonProgramming/agentic-harness) | Compass, an onboarding assistant for junior devs, built under an AI harness where the coding agent works to a written contract |
| 🤖 Agents | [UI-Physician](https://github.com/AnderssonProgramming/UI-Physician) | Agent skill that diagnoses and repairs Android layout crashes from a Logcat dump, with a bounded self-correction loop |
| 🤖 Agents | [agentState-Orchestrator](https://github.com/AnderssonProgramming/agentState-Orchestrator) | State management and orchestration plan for a lead agent and three sub-agents under context-window limits |
| 🤖 Agents | [agent-constitution](https://github.com/AnderssonProgramming/agent-constitution) | A CLAUDE.md "constitution" defining an AI coding agent's identity, rules and slash commands |
| 🤖 Agents | [local-ai-harness](https://github.com/AnderssonProgramming/local-ai-harness) | Stress test of how far Phi-3-mini on CPU-only Ollama can go before context limits break multi-file reasoning |
| 🛡️ Security | [devsecops-threat-monitor](https://github.com/AnderssonProgramming/devsecops-threat-monitor) | Shift-left and shift-right lifecycle with Falco, OWASP ZAP, Prometheus, Grafana and Loki |
| 🛡️ Security | [automated-recon-toolkit](https://github.com/AnderssonProgramming/automated-recon-toolkit) | Asyncio port scanner, Nmap XML parsing and 3-sigma log anomaly detection |
| 🛡️ Security | [secure-application-design](https://github.com/AnderssonProgramming/secure-application-design) | Split-server architecture on AWS EC2 with end-to-end HTTPS and BCrypt authentication |
| 🔬 ML & Science | [exoplanet-ml-classifier](https://github.com/AnderssonProgramming/exoplanet-ml-classifier) | Reproducible pipeline that vets NASA Kepler Objects of Interest with Scikit-Learn and XGBoost |
| 🔬 ML & Science | [cnn-architectural-aws-ai](https://github.com/AnderssonProgramming/cnn-architectural-aws-ai) | CNN vs. dense networks for Mars surface classification, run on AWS SageMaker |
| 🔬 ML & Science | [quantum-observables-simulation](https://github.com/AnderssonProgramming/quantum-observables-simulation) | Simulations of quantum observables, measurements and unitary evolution |
| 🧪 Product | [voxcesta-commerce](https://github.com/AnderssonProgramming/voxcesta-commerce) | Voice-ordering kiosk MVP where shoppers order groceries by speaking Colombian Spanish |
| 🧪 Product | [state-machine-bridge-test](https://github.com/AnderssonProgramming/state-machine-bridge-test) | Serverless order-processing state machine with 11 states and an expandable rules engine |
| 🎨 Design | [exoplanet-ml-classifier-design-system](https://github.com/AnderssonProgramming/exoplanet-ml-classifier-design-system) | Zero-dependency design system: tokens, 13 pure HTML/CSS components and a 20-slide deck |
| 🌐 Portfolio | [AnderssonProgramming.github.io](https://github.com/AnderssonProgramming/AnderssonProgramming.github.io) | My portfolio, built with React 19, TypeScript, Tailwind CSS v4 and Framer Motion |

</details>

<div align="center">
<br>
<a href="https://github.com/AnderssonProgramming?tab=repositories&sort=stargazers">
<img src="https://custom-icon-badges.demolab.com/badge/-View%20All%20Projects-FF8C00?style=for-the-badge&logoColor=white&logo=repo" alt="View all projects"/>
</a>
</div>

### 🤝 Collaborative Projects

<table>
<tr>
<td width="33%" valign="top">

<h4 align="center">Elysium Platform</h4>
<div align="center">
<a href="https://github.com/AnderssonProgramming/Elysium-Back">
<img src="https://img.shields.io/badge/Backend-6DB33F?style=for-the-badge&logo=spring&logoColor=white" alt="Elysium backend"/>
</a>
<a href="https://github.com/AnderssonProgramming/Elysium-Front-React">
<img src="https://img.shields.io/badge/Frontend-61DAFB?style=for-the-badge&logo=react&logoColor=black" alt="Elysium frontend"/>
</a>
</div>
</td>

<td width="33%" valign="top">

<h4 align="center">Prometeo System</h4>
<div align="center">
<a href="https://github.com/AnderssonProgramming/Prometeo-Back">
<img src="https://img.shields.io/badge/Backend-6DB33F?style=for-the-badge&logo=spring&logoColor=white" alt="Prometeo backend"/>
</a>
<a href="https://github.com/AnderssonProgramming/ECI-Bienestar-Front">
<img src="https://img.shields.io/badge/Frontend-61DAFB?style=for-the-badge&logo=react&logoColor=black" alt="ECI Bienestar frontend"/>
</a>
</div>
</td>

<td width="33%" valign="top">

<h4 align="center">More Projects</h4>
<div align="center">
<a href="https://github.com/AnderssonProgramming/Puzzle">
<img src="https://img.shields.io/badge/Puzzle-FF6C37?style=for-the-badge&logo=github&logoColor=white" alt="Puzzle"/>
</a>
<a href="https://github.com/AnderssonProgramming/Delizia">
<img src="https://img.shields.io/badge/Delizia-E92063?style=for-the-badge&logo=github&logoColor=white" alt="Delizia"/>
</a>
<a href="https://github.com/AnderssonProgramming/POOB-VS-Zombies">
<img src="https://img.shields.io/badge/POOB--VS--Zombies-6DB33F?style=for-the-badge&logo=github&logoColor=white" alt="POOB VS Zombies"/>
</a>
</div>
</td>
</tr>
</table>

### 📚 Coursework in the open

I keep my university labs public so the next student has a head start:
[**ARSW**](https://github.com/AnderssonProgramming/ARSW) · Software Architecture —
[**AREP**](https://github.com/AnderssonProgramming/AREP) · Enterprise Architecture —
[**SPTI**](https://github.com/AnderssonProgramming/SPTI) · IT Security & Privacy —
[**MLEA_M**](https://github.com/AnderssonProgramming/MLEA_M) · Machine Learning

<img src="./assets/divider.svg" width="100%" alt=""/>

## 📊 GitHub Analytics

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://github-stats-extended.vercel.app/api?username=AnderssonProgramming&show_icons=true&include_all_commits=true&count_private=true&hide_border=true&bg_color=0D1117&title_color=FF8C00&icon_color=A855F7&text_color=C9D1D9&ring_color=FF3D81"/>
  <source media="(prefers-color-scheme: light)" srcset="https://github-stats-extended.vercel.app/api?username=AnderssonProgramming&show_icons=true&include_all_commits=true&count_private=true&hide_border=true&bg_color=FFFFFF&title_color=D96F00&icon_color=8B3DF0&text_color=24292F&ring_color=E6266E"/>
  <img height="180" src="https://github-stats-extended.vercel.app/api?username=AnderssonProgramming&show_icons=true&include_all_commits=true&count_private=true&hide_border=true&bg_color=0D1117&title_color=FF8C00&icon_color=A855F7&text_color=C9D1D9&ring_color=FF3D81" alt="GitHub stats"/>
</picture>
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://github-stats-extended.vercel.app/api/top-langs/?username=AnderssonProgramming&layout=compact&langs_count=10&hide_border=true&bg_color=0D1117&title_color=FF8C00&text_color=C9D1D9&hide=Jupyter%20Notebook"/>
  <source media="(prefers-color-scheme: light)" srcset="https://github-stats-extended.vercel.app/api/top-langs/?username=AnderssonProgramming&layout=compact&langs_count=10&hide_border=true&bg_color=FFFFFF&title_color=D96F00&text_color=24292F&hide=Jupyter%20Notebook"/>
  <img height="180" src="https://github-stats-extended.vercel.app/api/top-langs/?username=AnderssonProgramming&layout=compact&langs_count=10&hide_border=true&bg_color=0D1117&title_color=FF8C00&text_color=C9D1D9&hide=Jupyter%20Notebook" alt="Most used languages"/>
</picture>

<br/>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://streak-stats.demolab.com/?user=AnderssonProgramming&hide_border=true&background=0D1117&ring=FF8C00&fire=FF3D81&currStreakNum=F0F6FC&sideNums=F0F6FC&currStreakLabel=FF8C00&sideLabels=C9D1D9&dates=8B949E&stroke=30363D"/>
  <source media="(prefers-color-scheme: light)" srcset="https://streak-stats.demolab.com/?user=AnderssonProgramming&hide_border=true&background=FFFFFF&ring=D96F00&fire=E6266E&currStreakNum=24292F&sideNums=24292F&currStreakLabel=D96F00&sideLabels=57606A&dates=6E7781&stroke=D0D7DE"/>
  <img src="https://streak-stats.demolab.com/?user=AnderssonProgramming&hide_border=true&background=0D1117&ring=FF8C00&fire=FF3D81&currStreakNum=F0F6FC&sideNums=F0F6FC&currStreakLabel=FF8C00&sideLabels=C9D1D9&dates=8B949E&stroke=30363D" alt="GitHub streak"/>
</picture>

<br/><br/>

<!-- Generated twice a day by .github/workflows/profile-assets.yml into the `output` branch -->
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/AnderssonProgramming/AnderssonProgramming/output/profile-night-rainbow.svg"/>
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/AnderssonProgramming/AnderssonProgramming/output/profile-season-animate.svg"/>
  <img width="100%" src="https://raw.githubusercontent.com/AnderssonProgramming/AnderssonProgramming/output/profile-night-rainbow.svg" alt="3D contribution calendar"/>
</picture>

<img src="https://trophy.ryglcloud.net/?username=AnderssonProgramming&theme=radical&no-frame=true&column=7&margin-w=10&margin-h=10&no-bg=true" alt="Trophies"/>

<br/><br/>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/AnderssonProgramming/AnderssonProgramming/output/snake-dark.svg"/>
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/AnderssonProgramming/AnderssonProgramming/output/snake.svg"/>
  <img width="100%" src="https://raw.githubusercontent.com/AnderssonProgramming/AnderssonProgramming/output/snake-dark.svg" alt="Snake eating my contribution graph"/>
</picture>

</div>

<img src="./assets/divider.svg" width="100%" alt=""/>

## 🎓 Currently Learning & Exploring

<table>
<tr>
<td width="50%" valign="top">

🤖 **Large Language Models (LLMs)**  
*Building conversational AI agents for automation*

📱 **Android Development with Kotlin**  
*Hybrid backend integration for mobile games*

🌐 **WebSockets & Real-Time Systems**  
*Concurrent and parallel application architecture*

</td>
<td width="50%" valign="top">

🧠 **Gemini 3 Pro Integration**  
*Multimodal AI with advanced reasoning capabilities*

🎮 **Unity Game Development**  
*C# physics engines and interactive experiences*

🔗 **n8n Workflow Automation**  
*Low-code integrations and event-driven pipelines*

</td>
</tr>
</table>

<img src="./assets/divider.svg" width="100%" alt=""/>

<div align="center">

## 🎯 Let's Connect & Collaborate!

Have an idea, a role, or a bug that refuses to die? My inbox is open.

<a href="https://www.linkedin.com/in/anderssonsm/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logoColor=white" alt="LinkedIn"/></a>
<a href="https://anderssonprogramming.github.io"><img src="https://img.shields.io/badge/Portfolio-FF8C00?style=for-the-badge&logo=googlechrome&logoColor=white" alt="Portfolio"/></a>
<a href="https://github.com/AnderssonProgramming"><img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white" alt="GitHub"/></a>
<a href="https://leetcode.com/u/ander14_73/"><img src="https://img.shields.io/badge/LeetCode-1F222E?style=for-the-badge&logo=leetcode&logoColor=FFA116" alt="LeetCode"/></a>
<a href="https://www.hackerrank.com/profile/ander14_73"><img src="https://img.shields.io/badge/HackerRank-1F222E?style=for-the-badge&logo=hackerrank&logoColor=00EA64" alt="HackerRank"/></a>
<a href="https://www.researchgate.net/profile/Andersson-Sanchez-Mendez"><img src="https://img.shields.io/badge/ResearchGate-1F222E?style=for-the-badge&logo=researchgate&logoColor=00CCBB" alt="ResearchGate"/></a>

<br/><br/>

**💡 Open to collaborations · 🚀 Always learning · 🎯 Problem solver at heart**

<sub>Family, sports, music, life and everything 💜 ADSM</sub>

<br/>

<sub>README inspired by [DenverCoder1](https://github.com/DenverCoder1) · Contribution art by [Platane/snk](https://github.com/Platane/snk) and [yoshi389111](https://github.com/yoshi389111/github-profile-3d-contrib) · <a href="#top">Back to top ↑</a></sub>

<img src="./assets/footer.svg" width="100%" height="110" alt=""/>

</div>
