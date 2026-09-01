<div align="center">

<img src="./logo_me.png" width="180px" alt="BrayanDevZN Logo"/>

# Olá, eu sou o Brayan 👋

### Backend Developer | AI Engineer | Data Analytics

Construindo sistemas, APIs e soluções com foco em **arquitetura, performance e escalabilidade**.

<br/>

![Profile Views](https://komarev.com/ghpvc/?username=BrayanDevZN\&style=for-the-badge\&color=blueviolet)

[![GitHub followers](https://img.shields.io/github/followers/BrayanDevZN?style=for-the-badge\&color=blueviolet)](https://github.com/BrayanDevZN)

</div>

---

## 🚀 Tech Stack

<div align="center">

### 🤖 IA & Agentes

![OpenAI](https://img.shields.io/badge/OpenAI_API-412991?style=for-the-badge\&logo=openai\&logoColor=white)
![AI Agents](https://img.shields.io/badge/AI_Agents-000000?style=for-the-badge\&logo=robotframework\&logoColor=white)
![Automation](https://img.shields.io/badge/Automation-FF6F00?style=for-the-badge\&logo=python\&logoColor=white)

### ⚙️ Backend

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge\&logo=python\&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge\&logo=fastapi\&logoColor=white)
![Pydantic](https://img.shields.io/badge/Pydantic-E92063?style=for-the-badge\&logo=pydantic\&logoColor=white)
![SQLAlchemy](https://img.shields.io/badge/SQLAlchemy-D71F00?style=for-the-badge\&logo=sqlalchemy\&logoColor=white)

### 🗄️ Databases & Cache

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge\&logo=postgresql\&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge\&logo=redis\&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=for-the-badge\&logo=sqlite\&logoColor=white)

### 📊 Dados

![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge\&logo=pandas\&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge\&logo=numpy\&logoColor=white)
![Polars](https://img.shields.io/badge/Polars-CD792C?style=for-the-badge\&logo=polars\&logoColor=white)
![Apache Spark](https://img.shields.io/badge/Apache_Spark-E25A1C?style=for-the-badge\&logo=apachespark\&logoColor=white)

### 🐳 Infraestrutura & Ferramentas

![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge\&logo=docker\&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge\&logo=linux\&logoColor=black)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge\&logo=git\&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge\&logo=github\&logoColor=white)

</div>

---

## 👨‍💻 Sobre mim

Sou desenvolvedor com foco em **Backend Engineering**, trabalhando principalmente com **Python** e desenvolvimento de APIs.

Gosto de entender o que acontece por trás das abstrações: arquitetura de sistemas, HTTP, autenticação, caching, bancos de dados, processamento assíncrono e infraestrutura.

Além de backend, tenho experiência com **desenvolvimento de agentes de IA** usando a API da OpenAI, engenharia e processamento de dados, e automações.

* 🤖 Desenvolvo **agentes de IA** e integrações com LLMs (OpenAI API)
* 🔭 Atualmente aprofundando conceitos de **sistemas distribuídos** e infraestrutura
* 🌱 Sempre estudando novas formas de escalar e otimizar sistemas
* 💬 Pergunte-me sobre Python, APIs, arquitetura de backend, IA e dados
* ⚡ Fun fact: gosto de entender o "porquê" por trás de cada abstração

---

## 🧠 O que estou estudando

```text id="lilxfw"
Backend Engineering & AI
│
├── API Design (FastAPI, Pydantic)
├── AI Agents & LLM Integration (OpenAI API)
├── Authentication & Security
├── Caching
├── Background Processing
├── Concurrency
├── System Design
└── Distributed Systems
```

---

## 🛠️ Como eu trabalho

Gosto de construir sistemas pensando primeiro no **problema e na arquitetura**, e só depois nas ferramentas.

No backend, procuro separar responsabilidades entre entrada de dados, regras de negócio, persistência, cache e integrações externas.

```text id="rdm8ka"
Request
   │
   ▼
┌───────────────┐
│    FastAPI    │
│  HTTP / API   │
└───────┬───────┘
        │
        ▼
┌───────────────┐
│   Pydantic    │
│  Validation   │
└───────┬───────┘
        │
        ▼
┌───────────────┐
│ Business Logic│
│   Services    │
└───────┬───────┘
        │
   ┌────┴─────────────┐
   │                  │
   ▼                  ▼
┌─────────┐      ┌──────────┐
│  Redis  │      │SQLAlchemy│
│  Cache  │      │   ORM    │
└─────────┘      └────┬─────┘
                      │
                      ▼
                ┌───────────┐
                │PostgreSQL │
                └───────────┘
```

### ⚙️ Backend & APIs

Com **Python, FastAPI, Pydantic e SQLAlchemy**, trabalho com desenvolvimento de APIs pensando não apenas no endpoint, mas no comportamento do sistema como um todo.

Isso inclui:

* organização e separação de responsabilidades;
* autenticação e autorização;
* validação e modelagem de dados;
* caching e invalidação de cache;
* rate limiting;
* processamento assíncrono;
* integração com serviços e APIs externas;
* tratamento de erros e logging;
* acesso e persistência de dados.

---

### ⚡ Cache & Persistência

Uso **PostgreSQL** para persistência relacional e **Redis** quando existe vantagem real em manter informações em memória.

```text id="v4n44c"
              ┌────── HIT ──────► Response
              │
Request ──► Redis
              │
              └────── MISS
                       │
                       ▼
                  PostgreSQL
                       │
                       ▼
                  Update Cache
                       │
                       ▼
                    Response
```

Além de caching, utilizo Redis para **TTL, contadores, rate limiting e estruturas temporárias**.

A ideia é evitar consultas e processamento desnecessários sem transformar cache em fonte de verdade.

---

### 🤖 IA & Agentes

Na parte de IA, trabalho principalmente com a **OpenAI API**, integração de LLMs, agentes e automações.

Procuro tratar o modelo como **um componente da aplicação**, mantendo lógica determinística no backend sempre que ela não precisa depender de IA.

```text id="5nb4qh"
Application
     │
     ▼
┌──────────────┐
│   Backend    │
└──────┬───────┘
       │
       ▼
┌──────────────┐
│ Agent / Flow │
└──────┬───────┘
       │
   ┌───┴───────────────┐
   │                   │
   ▼                   ▼
  LLM              Tools / APIs
   │                   │
   └─────────┬─────────┘
             │
             ▼
          Response
```

Meu foco está em **LLM Integration, Agent Design, tool calling, automação e orquestração**.

---

### 📊 Dados

Para análise e processamento de dados trabalho com **Pandas, NumPy, Polars e Apache Spark**.

Procuro organizar processamento como um fluxo claro:

```text id="scl9ju"
Raw Data
   │
   ▼
Extraction
   │
   ▼
Cleaning
   │
   ▼
Validation
   │
   ▼
Transformation
   │
   ▼
Processed Data
   │
   ├──► Analytics
   ├──► Database
   └──► API
```

A ferramenta depende do problema e do volume de dados, em vez de existir uma biblioteca padrão para qualquer situação.

---

### 🐳 Infraestrutura & Ambiente

Uso **Docker** para criar ambientes isolados e reproduzíveis, **Linux** como ambiente de desenvolvimento e **Git/GitHub** para versionamento e organização dos projetos.

Gosto de enxergar além do código da aplicação:

```text id="3it7ny"
Code
 │
 ▼
Application
 │
 ├── Database
 ├── Cache
 └── External Services
 │
 ▼
Container
 │
 ▼
Infrastructure
 │
 ▼
Production
```

> **Primeiro entendo o problema. Depois escolho a ferramenta. Complexidade precisa ter motivo.**

---

## 📊 Estatísticas do GitHub

<div align="center">

<img height="165" src="https://github-readme-stats.vercel.app/api?username=BrayanDevZN&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" />

<img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=BrayanDevZN&layout=compact&theme=tokyonight&hide_border=true" />

</div>

<div align="center">

<img src="https://github-readme-streak-stats.herokuapp.com/?user=BrayanDevZN&theme=tokyonight&hide_border=true" />

</div>

---

## 📫 Conecte-se comigo

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge\&logo=linkedin\&logoColor=white)](#)

[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge\&logo=gmail\&logoColor=white)](#)

</div>

---

<div align="center">

### `Code. Build. Learn. Repeat.`

</div>
