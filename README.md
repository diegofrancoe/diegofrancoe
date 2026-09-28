<p align="center">
  <a href="https://www.diegofrancoe.com/">
    <img src="./assets/profile-header.svg" width="100%" alt="Diego Franco — AI Solutions Engineer" />
  </a>
</p>



## AI Solutions Engineer

I design and build full-stack products where **software, business workflows, automation, data and applied AI** work as one system.

My focus is not adding AI as decoration. I build the product around real operational context: clear UX/UI, structured data, secure integrations, AI agents and human-approved actions.

Based in Bogotá, Colombia.

## Featured systems

| Project | Focus | Access |
|---|---|---|
| **CENIZA — AI-Powered Full-Stack CRM** | Full-stack CRM, operational data, RAG-based AI agent, automation and public read-only demo | [Live demo](https://ceniza-crm.vercel.app/) · [Case study](https://www.diegofrancoe.com/proyectos/ceniza) · [Public website](https://cenizaproducciones.com/) |
| **NAVAL — AI Business Ecosystem** | B2B web platform, product assistant, commercial automation and private ERP under active development | [Live website](https://www.productosnaval.com/) · [Case study](https://www.diegofrancoe.com/proyectos/naval) |
| **40+ — E-commerce & Automation** | Commerce experience, WhatsApp-assisted sales, secure forms and automated customer communication | [Live website](https://cuarentamas.com/) · [Case study](https://www.diegofrancoe.com/proyectos/40-plus) |

> **Privacy by design:** production business data, credentials and sensitive operational systems remain private. Public demos and portfolio evidence are separated from real production information.

## Architecture snapshots

### CENIZA — AI-Powered Full-Stack CRM

~~~mermaid
flowchart LR
    U[User] --> UI[React + TypeScript CRM]
    UI --> AUTH[Supabase Auth]
    AUTH --> RLS[Membership + RLS]
    RLS --> DB[(PostgreSQL)]
    RLS --> ST[Private Storage]
    UI --> AI[AI agent]
    AI --> RAG[Hybrid RAG]
    RAG --> KB[Semantic guides]
    RAG --> LIVE[Live operational data]
    LIVE --> DB
    AI --> APPROVAL[Human approval]
    APPROVAL --> EDGE[Edge Function]
    EDGE --> ACTIONS[Controlled actions / email]
~~~

The public Ceniza website uses a separate secure intake boundary before data reaches automation or the CRM. The CRM demo is designed to show the product without exposing real business data.

### NAVAL — AI Business Ecosystem

~~~mermaid
flowchart LR
    C[Customer] --> WEB[React + Vite web platform]
    WEB --> CAT[Product catalog]
    WEB --> CHAT[Commercial assistant]
    CHAT --> LOCAL[Local product knowledge]
    CHAT --> API[Serverless API]
    API --> MAKE[Make workflows]
    API --> OAI[OpenAI fallback]
    WEB --> DOCS[Technical documents]
    ERP[Private ERP — in development] -. operational evolution .-> WEB
~~~

The public website supports product discovery and commercial flows. The ERP remains private while production, inventory, purchasing, finance and AI capabilities are still being completed.

### 40+ — E-commerce & Automation

~~~mermaid
flowchart LR
    V[Visitor] --> WEB[React commerce experience]
    WEB --> WA[WhatsApp-assisted order]
    WEB --> FORM[Experience form]
    FORM --> API[Server validation]
    API --> TS[Cloudflare Turnstile]
    TS --> MAKE[Make]
    MAKE --> MAIL[Microsoft 365 email]
    MAKE --> SHEETS[Google Sheets / Drive]
~~~

The website deliberately separates public UX from private automation credentials and operational services.

## How I build

~~~text
Business problem
      ↓
Product & system architecture
      ↓
UX/UI
      ↓
Full-stack implementation
      ↓
Integrations & automation
      ↓
Applied AI / RAG / tool-enabled workflows
      ↓
Security, testing & human oversight
~~~

## Core stack

<p>
  <img alt="React" src="https://img.shields.io/badge/React-252824?style=flat-square&logo=react&logoColor=74CDA7" />
  <img alt="TypeScript" src="https://img.shields.io/badge/TypeScript-252824?style=flat-square&logo=typescript&logoColor=74CDA7" />
  <img alt="Next.js" src="https://img.shields.io/badge/Next.js-252824?style=flat-square&logo=nextdotjs&logoColor=74CDA7" />
  <img alt="Supabase" src="https://img.shields.io/badge/Supabase-252824?style=flat-square&logo=supabase&logoColor=74CDA7" />
  <img alt="PostgreSQL" src="https://img.shields.io/badge/PostgreSQL-252824?style=flat-square&logo=postgresql&logoColor=74CDA7" />
  <img alt="OpenAI" src="https://img.shields.io/badge/OpenAI-252824?style=flat-square&logo=openai&logoColor=74CDA7" />
  <img alt="n8n" src="https://img.shields.io/badge/n8n-252824?style=flat-square&logo=n8n&logoColor=74CDA7" />
  <img alt="Make" src="https://img.shields.io/badge/Make-252824?style=flat-square&logo=make&logoColor=74CDA7" />
  <img alt="Vercel" src="https://img.shields.io/badge/Vercel-252824?style=flat-square&logo=vercel&logoColor=74CDA7" />
  <img alt="Figma" src="https://img.shields.io/badge/Figma-252824?style=flat-square&logo=figma&logoColor=74CDA7" />
</p>

<p align="center">
  <strong>Full-stack products · AI agents · RAG · workflow automation · product UX/UI</strong>
</p>
