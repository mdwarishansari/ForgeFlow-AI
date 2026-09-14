
# 🚀 ForgeFlow AI

<p align="center">
  <img src="https://raw.githubusercontent.com/warishlabs/ForgeFlow-AI/main/public/Logo/forgeflow-logo-gradient.svg" width="150" alt="ForgeFlow AI Logo" />
</p>

<h1 align="center">ForgeFlow AI</h1>

<p align="center">
  <strong>Autonomous Agentic AI Platform for Software Architecture & Implementation Blueprints</strong>
</p>

<p align="center">
  Turn a single software idea into a structured, reasoned, implementation-ready engineering blueprint
  using persistent project state, LLM reasoning, external research, and human-in-the-loop AI execution.
</p>

<p align="center">
  <a href="https://forgeflow.warishlabs.in">
    <img src="https://img.shields.io/badge/🚀_LIVE_DEMO-forgeflow.warishlabs.in-1060ee?style=for-the-badge" alt="Live Demo" />
  </a>
  <a href="https://github.com/warishlabs/ForgeFlow-AI">
    <img src="https://img.shields.io/badge/🔗_ACTUAL_SOURCE-WarishLabs%2FForgeFlow--AI-181717?style=for-the-badge&logo=github" alt="Actual Source Repository" />
  </a>
</p>

<p align="center">
  <a href="https://github.com/mdwarishansari/ForgeFlow-AI">
    <img src="https://img.shields.io/badge/👤_PERSONAL_SHOWCASE-mdwarishansari%2FForgeFlow--AI-181717?style=for-the-badge&logo=github" alt="Personal Showcase Repository" />
  </a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Next.js-16-black?style=flat-square&logo=next.js" />
  <img src="https://img.shields.io/badge/React-19-61DAFB?style=flat-square&logo=react&logoColor=black" />
  <img src="https://img.shields.io/badge/TypeScript-5-3178C6?style=flat-square&logo=typescript&logoColor=white" />
  <img src="https://img.shields.io/badge/LangGraph.js-Agentic_AI-FF6B6B?style=flat-square" />
  <img src="https://img.shields.io/badge/PostgreSQL-Database-4169E1?style=flat-square&logo=postgresql&logoColor=white" />
  <img src="https://img.shields.io/badge/Prisma-ORM-2D3748?style=flat-square&logo=prisma&logoColor=white" />
  <img src="https://img.shields.io/badge/Groq-LLM-8A2BE2?style=flat-square" />
  <img src="https://img.shields.io/badge/Gemini-Fallback-4285F4?style=flat-square&logo=google" />
  <img src="https://img.shields.io/badge/Tavily-Web_Research-FF6B35?style=flat-square" />
  <img src="https://img.shields.io/badge/Clerk-Authentication-6C47FF?style=flat-square" />
  <img src="https://img.shields.io/badge/Upstash-Redis-00E9A3?style=flat-square" />
</p>

---

## 🌐 Quick Access

<table>
<tr>
<td align="center" width="33%">

### 🚀 Live Application

[**Open ForgeFlow AI**](https://forgeflow.warishlabs.in)

Production deployment for exploring the complete platform.

</td>
<td align="center" width="33%">

### 🔗 Actual Source

[**WarishLabs/ForgeFlow-AI**](https://github.com/warishlabs/ForgeFlow-AI)

Official repository containing the complete implementation.

</td>
<td align="center" width="33%">

### 👤 Personal Showcase

[**mdwarishansari/ForgeFlow-AI**](https://github.com/mdwarishansari/ForgeFlow-AI)

Personal GitHub showcase repository.

</td>
</tr>
</table>

> **Repository structure:** This repository is a lightweight personal showcase for ForgeFlow AI.  
> The complete production source code is maintained in the **WarishLabs organization repository** above.

---

# 🧠 What is ForgeFlow AI?

ForgeFlow AI is an **Agentic AI platform for software architecture, requirements engineering, technical planning, and implementation blueprint generation**.

The platform is designed around a simple idea:

> **Software architecture should be treated as persistent project state, not disposable chat output.**

Traditional AI chat applications commonly follow:

```text
User Prompt
    ↓
LLM Response
    ↓
Text in Chat
    ↓
Conversation Continues
    ↓
Context Becomes Hard to Manage
````

ForgeFlow takes a different approach:

```text
Software Idea
      ↓
Project State
      ↓
Requirements
      ↓
Architecture
      ↓
Data Models
      ↓
Roadmap
      ↓
Agent Reasoning
      ↓
Structured Proposal
      ↓
Human Review
      ↓
Accept / Reject
      ↓
Controlled State Mutation
      ↓
Audit Event
```

Instead of producing another temporary AI answer, ForgeFlow maintains a structured representation of the project and allows an AI agent to reason about changes to that state.

---

# 🎯 The Problem ForgeFlow Solves

When engineers use generic LLM chat interfaces for architecture work, a typical workflow becomes fragmented.

You ask the model to:

* define requirements
* suggest a technology stack
* design a database
* propose architecture
* create ADRs
* build a roadmap
* revise an earlier decision

But those responses generally remain disconnected pieces of text.

The engineer then has to manually:

```text
Copy
 ↓
Review
 ↓
Edit
 ↓
Move into documentation
 ↓
Update database / architecture
 ↓
Repeat
```

ForgeFlow introduces a structured engineering workflow where the AI operates against the **current project state**.

That creates a much more controlled lifecycle:

```text
┌──────────────────────────────┐
│       Persistent Project     │
│             State            │
│                              │
│ Requirements                 │
│ Technology Stack             │
│ Data Models                  │
│ Architecture Decisions       │
│ Roadmap                      │
└──────────────┬───────────────┘
               │
               ▼
      ┌──────────────────┐
      │   Agent Engine   │
      │   LangGraph.js   │
      └────────┬─────────┘
               │
       ┌───────┼────────┐
       ▼       ▼        ▼
     Groq    Gemini   Tavily
     LLM     Fallback Research
       │       │        │
       └───────┼────────┘
               ▼
     ┌────────────────────┐
     │ Structured Proposal│
     │       Card         │
     └──────────┬─────────┘
                │
                ▼
          Human Review
          /          \
         /            \
     ACCEPT          REJECT
       │               │
       ▼               ▼
 Update State       Discard
       │
       ▼
 Audit Event
```

---

# ✨ Why ForgeFlow is Different

<table>
<tr>
<td width="50%">

### 🧠 Persistent Intelligence

Project requirements, architecture decisions, data models, roadmaps, and related engineering state remain persisted in a relational database.

</td>
<td width="50%">

### 🤖 Agentic Workflow

LangGraph.js orchestrates multi-step AI workflows rather than treating every request as an isolated completion.

</td>
</tr>

<tr>
<td width="50%">

### 👤 Human-in-the-Loop

AI-generated changes are surfaced as structured proposals that require explicit approval before project state is mutated.

</td>
<td width="50%">

### 🔍 External Research

Tavily can provide web research context when external information is needed during blueprint generation.

</td>
</tr>

<tr>
<td width="50%">

### 🔄 LLM Provider Resilience

Groq is used as the primary LLM provider with Google Gemini available as a fallback.

</td>
<td width="50%">

### 📋 Auditability

Accepted proposal execution can be tracked through audit events, providing visibility into project-state changes.

</td>
</tr>

<tr>
<td width="50%">

### 📑 Engineering Documentation

Project state can be synthesized into structured engineering documents such as PRDs, stack guides, security specifications, topology documentation, ADRs, and roadmaps.

</td>
<td width="50%">

### 🏗️ State-Driven Architecture

The platform treats software architecture as structured data that can evolve over time instead of static documentation.

</td>
</tr>
</table>

---

# 🧩 Core Platform Modules

## 🎯 1. Software Vision Engine

The Software Vision Engine transforms a high-level software concept into structured product information.

It focuses on:

* Product vision
* Target users
* User personas
* Functional requirements
* Non-functional requirements
* MVP boundaries
* Core capabilities

The workflow can use multiple rounds of reasoning and dynamic questions to progressively clarify a project.

```text
High-Level Idea
      ↓
Product Vision
      ↓
Target Users
      ↓
Functional Requirements
      ↓
Non-Functional Requirements
      ↓
MVP Boundaries
```

---

## 🏗️ 2. Architecture & Data Synthesizer

Once project requirements exist, ForgeFlow can generate structured architecture information.

The platform can reason about:

* Component topology
* Technology choices
* Entity relationships
* Database schemas
* Architecture decisions
* Architecture Decision Records
* System-level design
* Technical constraints

The output becomes part of the persistent project state.

```text
Requirements
      ↓
Architecture
      ├── Components
      ├── Technologies
      ├── Data Models
      ├── Relationships
      └── ADRs
```

---

## 📅 3. Sequential Delivery Roadmap

ForgeFlow can organize delivery into sequential implementation phases.

A typical structure is:

```text
┌────────────┐
│  Phase 1   │
│    MVP     │
└─────┬──────┘
      ↓
┌────────────┐
│  Phase 2   │
│   Growth   │
└─────┬──────┘
      ↓
┌────────────┐
│  Phase 3   │
│   Scale    │
└────────────┘
```

The roadmap can represent prerequisite relationships and implementation dependencies.

---

# 🤖 4. ForgeFlow Agent Copilot

The Agent Copilot is the central AI workflow of the platform.

Unlike a conventional chatbot, the agent does not operate only on the user's latest message.

It can first retrieve the current project state and then reason over:

```text
Current Project State
         +
User Request
         +
Research Context
         ↓
    LLM Reasoning
         ↓
Structured Proposal
```

This allows an architectural request to be interpreted in the context of the existing project.

---

# 📝 5. Proposal Card System

One of ForgeFlow's core UX concepts is the **Proposal Card**.

Instead of immediately applying AI-generated changes, the system presents a structured proposal.

Example:

```text
╭─────────────────────────────────────────╮
│             AI PROPOSAL                 │
├─────────────────────────────────────────┤
│ Change Type: Technology                 │
│                                         │
│ Current:                                │
│ PostgreSQL                              │
│                                         │
│ Proposed:                               │
│ PostgreSQL + Redis                      │
│                                         │
│ Reason:                                  │
│ Introduce caching for frequently        │
│ accessed project state.                 │
│                                         │
│ Impact:                                  │
│ • Infrastructure                        │
│ • Application architecture              │
│ • Database workload                     │
│                                         │
│ Status: Pending Review                  │
│                                         │
│  [ ✓ Accept ]       [ ✕ Reject ]       │
╰─────────────────────────────────────────╯
```

The proposal lifecycle is intentionally explicit:

```text
AI Recommendation
       ↓
Proposal Card
       ↓
Human Review
    ↙       ↘
Accept     Reject
   ↓          ↓
Apply       Discard
   ↓
Audit Event
```

---

# 👤 Human-in-the-Loop Architecture

Human approval is a first-class part of the system.

The system does **not** treat AI output as an unquestionable source of truth.

```mermaid
sequenceDiagram
    autonumber

    actor User as Engineer / Founder
    participant UI as ForgeFlow Workspace
    participant Agent as Agent Execution Engine
    participant LLM as Groq / Gemini
    participant Search as Tavily
    participant DB as PostgreSQL

    User->>UI: Submit requirement or architecture change

    UI->>Agent: Trigger agent execution

    Agent->>DB: Fetch current project state

    DB-->>Agent: Requirements, stack, entities, ADRs, roadmap

    Agent->>LLM: Reason over state + request

    Agent->>Search: Perform external research

    Search-->>Agent: Research context

    LLM-->>Agent: Structured proposal

    Agent-->>UI: Render Proposal Card

    alt User accepts proposal
        User->>UI: Accept Proposal
        UI->>Agent: Apply Proposal
        Agent->>DB: Mutate project state
        Agent->>DB: Record audit event
        DB-->>UI: Updated project state
    else User rejects proposal
        User->>UI: Reject Proposal
        UI->>Agent: Reject Proposal
        Agent->>DB: Record rejection
    end
```

---

# 🏛️ High-Level Architecture

```mermaid
flowchart TB

    User["👤 User / Engineer"]

    subgraph Client["Client Layer"]
        UI["React 19 / Next.js 16<br/>App Router UI"]
        Admin["Super Admin Dashboard<br/>Email Studio"]
    end

    subgraph Security["Authentication & Middleware"]
        Clerk["Clerk Authentication"]
        Proxy["Proxy / Middleware Guard"]
    end

    subgraph Application["Application & Agent Layer"]
        Actions["Next.js Server Actions"]
        Agent["LangGraph.js<br/>Agent Orchestrator"]
        Email["Resend Email Engine"]
    end

    subgraph AI["AI & Research Layer"]
        Groq["Groq<br/>Llama 3.3 70B"]
        Gemini["Google Gemini<br/>Fallback"]
        Tavily["Tavily<br/>Web Research"]
    end

    subgraph Persistence["Persistence Layer"]
        Prisma["Prisma ORM"]
        PostgreSQL[("PostgreSQL")]
        Redis[("Upstash Redis")]
    end

    User --> UI
    User --> Admin

    UI --> Clerk
    UI --> Proxy
    Proxy --> Actions

    Actions --> Agent

    Agent --> Groq
    Agent --> Gemini
    Agent --> Tavily

    Actions --> Prisma
    Prisma --> PostgreSQL

    Actions --> Redis

    Admin --> Email
    Admin --> Prisma
```

---

# 🧠 Agent Reasoning Flow

ForgeFlow's agent workflow can be represented as:

```mermaid
flowchart LR

    Input["User Requirement"]
        --> State["Load Current Project State"]

    State
        --> Context["Build Reasoning Context"]

    Context
        --> Research["External Research"]

    Research
        --> Reason["LLM Reasoning"]

    Reason
        --> Proposal["Structured Proposal"]

    Proposal
        --> Review{"Human Review"}

    Review -->|Accept| Apply["Apply Proposal"]
    Review -->|Reject| Reject["Reject Proposal"]

    Apply --> Persist["Persist Updated State"]
    Persist --> Audit["Create Audit Event"]

    Reject --> Log["Record Rejection"]
```

---

# 📦 Persistent Project State

ForgeFlow represents the project using structured relational state.

```text
Project
│
├── Software Vision
│
├── Requirements
│   ├── Functional Requirements
│   └── Non-Functional Requirements
│
├── Technology Stack
│
├── Data Models
│
├── Architecture
│
├── Architecture Decision Records
│
├── Delivery Roadmap
│
├── Agent Proposals
│
└── Audit Events
```

This architecture allows the platform to maintain continuity between engineering decisions.

For example:

```text
Day 1
User defines PostgreSQL
        ↓
Database choice persisted

Day 2
User requests caching
        ↓
Agent reads current project state
        ↓
Agent proposes Redis

Day 3
User accepts proposal
        ↓
Project state updated
        ↓
Audit event recorded
```

The agent is therefore reasoning over the **evolving project**, not simply responding to disconnected prompts.

---

# 🔄 LLM Provider Architecture

ForgeFlow uses a primary/fallback approach for LLM orchestration.

```mermaid
flowchart TD

    Request["Agent Request"]
        --> Primary["Groq<br/>Llama 3.3 70B"]

    Primary -->|Success| Result["Structured AI Result"]

    Primary -->|Failure / Fallback| Gemini["Google Gemini"]

    Gemini --> Result

    Agent["LangGraph Agent"] --> Primary
    Agent --> Tavily["Tavily Web Research"]
    Tavily --> Agent
```

### Primary Reasoning Engine

**Groq — Llama 3.3 70B**

Used as the primary LLM provider.

### Fallback Model

**Google Gemini**

Provides a fallback path when the primary model provider cannot complete the requested workflow.

### Research Layer

**Tavily**

Provides external web research context when the agent needs information beyond the current project state.

---

# 🔎 External Web Research

Tavily is integrated into the agent workflow as a research capability.

The high-level flow is:

```text
User Request
     ↓
Agent Determines Need for Research
     ↓
Tavily Web Search
     ↓
Relevant Research Context
     ↓
LLM Reasoning
     ↓
Structured Proposal
```

This allows architecture proposals to incorporate external research when required instead of depending entirely on previously stored project information.

---

# 📑 Engineering Document Synthesis

ForgeFlow can synthesize structured engineering documentation from the current project state.

Examples include:

```text
Project State
     │
     ├── Product Requirements
     ├── Technology Stack
     ├── Security Requirements
     ├── System Topology
     ├── Architecture Decisions
     └── Roadmap
            │
            ▼
    LLM Document Synthesizer
            │
            ▼
     Engineering Documents
```

The documented modules include support for documents such as:

* Product Requirements Documents
* Stack Guides
* Security Specifications
* System Topology
* Architecture Decision Records
* Roadmaps
* Other project specifications

---

# 🛡️ Authentication & Protected Workflows

ForgeFlow uses **Clerk** for authentication.

Authentication is integrated into the application layer to protect user-facing workflows and administrative surfaces.

The architecture includes:

```text
User
 ↓
Clerk Authentication
 ↓
Application / Middleware
 ↓
Protected Server Actions
 ↓
Project Data
```

---

# 🗄️ Data Architecture

ForgeFlow uses a relational persistence model.

## PostgreSQL

PostgreSQL stores the persistent application and project state.

Project information can include:

* Requirements
* Technology choices
* Data models
* Architecture decisions
* Roadmaps
* Proposals
* Audit information

## Prisma ORM

Prisma provides the application-level database abstraction and schema management layer.

## Upstash Redis

Upstash Redis provides a fast cache layer for application workflows that benefit from temporary high-speed access.

---

# ✉️ Admin Broadcast Studio

ForgeFlow also includes a Super Admin environment.

The administrative functionality includes:

* Custom HTML email creation
* Live email preview
* Waitlist communication
* Release announcements
* Subscriber-oriented broadcasts
* Telemetry monitoring

The email workflow is integrated with **Resend**.

```text
Admin Dashboard
      ↓
Email Studio
      ↓
HTML Email
      ↓
Preview
      ↓
Resend
      ↓
Waitlist / Subscribers
```

---

# 📊 Platform Modules Overview

<table>
<thead>
<tr>
<th>Module</th>
<th>Purpose</th>
</tr>
</thead>
<tbody>
<tr>
<td>🎯 Software Vision Engine</td>
<td>Transforms high-level product ideas into structured requirements and project boundaries.</td>
</tr>
<tr>
<td>🏗️ Architecture & Data Synthesizer</td>
<td>Generates architecture, technology decisions, data models and ADR-oriented engineering state.</td>
</tr>
<tr>
<td>📅 Sequential Delivery Roadmap</td>
<td>Organizes MVP, growth and scale phases with implementation dependencies.</td>
</tr>
<tr>
<td>🤖 ForgeFlow Agent Copilot</td>
<td>Reasons over live project state and produces structured engineering proposals.</td>
</tr>
<tr>
<td>🔎 Web Research</td>
<td>Uses Tavily to retrieve external research context when required.</td>
</tr>
<tr>
<td>📝 Proposal Cards</td>
<td>Provides structured AI recommendations with explicit Accept / Reject actions.</td>
</tr>
<tr>
<td>📋 Audit System</td>
<td>Tracks proposal-driven project state changes and rejection events.</td>
</tr>
<tr>
<td>📑 Document Synthesizer</td>
<td>Generates structured engineering documents from persistent project state.</td>
</tr>
<tr>
<td>📊 Telemetry</td>
<td>Supports administrative monitoring and platform insights.</td>
</tr>
<tr>
<td>✉️ Broadcast Studio</td>
<td>Provides HTML email authoring, preview and broadcast workflows through Resend.</td>
</tr>
</tbody>
</table>

---

# 🧱 Technology Stack

## Frontend

| Technology       | Role                                                    |
| ---------------- | ------------------------------------------------------- |
| **Next.js 16**   | Full-stack React framework and application architecture |
| **React 19**     | User interface                                          |
| **TypeScript 5** | Type-safe application development                       |
| **App Router**   | Next.js routing and application structure               |
| **Tailwind CSS** | UI styling                                              |
| **Vanilla CSS**  | Custom styling                                          |
| **Lucide Icons** | Interface iconography                                   |

## Backend & Application

| Technology                 | Role                                     |
| -------------------------- | ---------------------------------------- |
| **Next.js Server Actions** | Server-side application workflows        |
| **Prisma ORM**             | Database access and schema layer         |
| **PostgreSQL**             | Persistent project and application state |
| **Upstash Redis**          | Caching                                  |
| **Clerk**                  | Authentication                           |

## Agentic AI

| Technology        | Role                    |
| ----------------- | ----------------------- |
| **LangGraph.js**  | Agent orchestration     |
| **Groq**          | Primary LLM provider    |
| **Llama 3.3 70B** | Primary reasoning model |
| **Google Gemini** | Fallback LLM provider   |
| **Tavily**        | External web research   |

## Platform Services

| Technology   | Role                                  |
| ------------ | ------------------------------------- |
| **Resend**   | Email delivery                        |
| **Supabase** | PostgreSQL infrastructure option      |
| **Vercel**   | Production deployment                 |
| **GitHub**   | Source control and project management |

---

# 🧭 Architectural Principles

ForgeFlow is designed around several core principles.

## 1. Persistent State Over Disposable Chat

Software requirements and architecture decisions should persist as structured project state instead of remaining trapped in conversation history.

## 2. Structured AI Output

AI should produce structured proposals that the application can interpret and execute instead of returning only free-form text.

## 3. Human Control

Important project changes require explicit human approval.

## 4. Provider Resilience

The architecture supports multiple LLM providers with a primary/fallback strategy.

## 5. Auditable Changes

State mutations resulting from accepted proposals can be recorded as audit events.

## 6. Separation of Concerns

The client, authentication layer, application layer, agent orchestration, AI providers, data layer, and external services remain conceptually separated.

---

# 🧪 Example End-to-End Workflow

Imagine a founder starts with:

```text
"I want to build a marketplace for local retailers."
```

ForgeFlow can progressively turn that idea into:

```text
                    💡 Software Idea
                           │
                           ▼
                  🎯 Product Vision
                           │
                           ▼
                     📋 Requirements
                      /           \
                     /             \
                    ▼               ▼
          Functional           Non-Functional
          Requirements         Requirements
                    \               /
                     \             /
                           ▼
                    🏗️ Architecture
                           │
                           ▼
                     🗄️ Data Models
                           │
                           ▼
                  📑 Architecture Decisions
                           │
                           ▼
                    📅 Delivery Roadmap
```

Later, the founder might say:

```text
"Add caching for frequently accessed product information."
```

ForgeFlow can process that request in the context of the existing project:

```text
Existing Project State
        +
New Requirement
        +
Optional Web Research
        ↓
LangGraph Agent
        ↓
LLM Reasoning
        ↓
Proposal Card
        ↓
Human Review
```

The user can then explicitly:

```text
✅ ACCEPT
```

or:

```text
❌ REJECT
```

Only an accepted proposal proceeds through the application workflow to mutate persistent state.

---

# 🔐 Proposal Execution Model

```text
┌──────────────────────┐
│  User submits change │
└──────────┬───────────┘
           │
           ▼
┌──────────────────────┐
│ Load project state   │
└──────────┬───────────┘
           │
           ▼
┌──────────────────────┐
│ LangGraph processing │
└──────────┬───────────┘
           │
           ▼
┌──────────────────────┐
│ LLM reasoning        │
└──────────┬───────────┘
           │
           ▼
┌──────────────────────┐
│ Proposal Card        │
└──────────┬───────────┘
           │
      ┌────┴────┐
      ▼         ▼
   ACCEPT     REJECT
      │         │
      ▼         ▼
  Apply       Discard
      │
      ▼
  Database
  Mutation
      │
      ▼
 Audit Event
```

---

# 📈 Project State Evolution

ForgeFlow can be understood as a continuously evolving project knowledge system.

```mermaid
flowchart LR

    Initial["💡 Initial Idea"]

    Initial --> Vision["🎯 Vision"]
    Vision --> Req["📋 Requirements"]
    Req --> Stack["⚙️ Technology Stack"]
    Stack --> Data["🗄️ Data Model"]
    Data --> Arch["🏗️ Architecture"]
    Arch --> ADR["📑 ADRs"]
    ADR --> Roadmap["📅 Roadmap"]

    Roadmap --> Agent["🤖 Agent Copilot"]

    Agent --> Proposal["📝 Proposal"]
    Proposal --> Review["👤 Human Review"]

    Review -->|Accept| Updated["✅ Updated State"]
    Review -->|Reject| Rejected["❌ Rejected"]

    Updated --> Audit["📋 Audit Event"]
    Audit --> Agent
```

This creates a feedback loop where the project state evolves as engineers review and apply AI-generated proposals.

---

# 🧠 Engineering Focus

ForgeFlow is an exploration of how **LLM and agentic AI systems can become part of real software engineering workflows** rather than remaining isolated conversational tools.

The project focuses on:

* Agent orchestration
* LLM integration
* Structured AI output
* Persistent relational project state
* Human-in-the-loop workflows
* AI-assisted architecture
* External web research
* Database-driven application design
* Server-side workflows
* Authentication
* Caching
* Auditability
* Engineering documentation generation
* Production application architecture

---

# 🏗️ Production Architecture at a Glance

```text
                         ┌─────────────────────┐
                         │       Browser       │
                         │   React / Next.js   │
                         └──────────┬──────────┘
                                    │
                                    ▼
                         ┌─────────────────────┐
                         │ Clerk Authentication│
                         └──────────┬──────────┘
                                    │
                                    ▼
                         ┌─────────────────────┐
                         │ Next.js Server      │
                         │ Actions             │
                         └──────────┬──────────┘
                                    │
                                    ▼
                         ┌─────────────────────┐
                         │ LangGraph.js Agent  │
                         └──────────┬──────────┘
                                    │
                 ┌──────────────────┼──────────────────┐
                 │                  │                  │
                 ▼                  ▼                  ▼
          ┌─────────────┐    ┌─────────────┐    ┌─────────────┐
          │    Groq     │    │   Gemini    │    │   Tavily    │
          │ Llama 3.3   │    │  Fallback   │    │   Search    │
          │    70B      │    │    Model    │    │    / Web    │
          └─────────────┘    └─────────────┘    └─────────────┘
                 │                  │                  │
                 └──────────────────┼──────────────────┘
                                    │
                                    ▼
                         ┌─────────────────────┐
                         │ Structured Proposal │
                         └──────────┬──────────┘
                                    │
                                    ▼
                         ┌─────────────────────┐
                         │   Human Decision    │
                         └───────┬───────┬─────┘
                                 │       │
                              Accept   Reject
                                 │       │
                                 ▼       ▼
                         ┌────────────┐  Discard
                         │   Prisma   │
                         └─────┬──────┘
                               │
                               ▼
                        ┌──────────────┐
                        │  PostgreSQL  │
                        └──────────────┘

                         ┌──────────────┐
                         │ Upstash Redis│
                         │    Cache     │
                         └──────────────┘
```

---

# 🚀 Production Deployment

ForgeFlow AI is available as a live production application.

<p align="center">
  <a href="https://forgeflow.warishlabs.in">
    <img src="https://img.shields.io/badge/OPEN_FORGEFLOW_AI-🚀_LIVE_PRODUCTION_APP-1060ee?style=for-the-badge" alt="Open ForgeFlow AI" />
  </a>
</p>

### 🌐 Live URL

**[https://forgeflow.warishlabs.in](https://forgeflow.warishlabs.in)**

---

# 🔗 Source Code & Repository Structure

## Official Production Source

The complete implementation is maintained here:

**[https://github.com/warishlabs/ForgeFlow-AI](https://github.com/warishlabs/ForgeFlow-AI)**

## Personal Showcase Repository

This repository exists to make ForgeFlow easily discoverable from the personal GitHub profile:

**[https://github.com/mdwarishansari/ForgeFlow-AI](https://github.com/mdwarishansari/ForgeFlow-AI)**

The separation is intentional:

```text
Official Implementation
        │
        ▼
warishlabs/ForgeFlow-AI
        │
        │
        ▼
Production Application
forgeflow.warishlabs.in


Personal Showcase
        │
        ▼
mdwarishansari/ForgeFlow-AI
        │
        └── README / Project Presentation
```

---

# ⚙️ Local Development

> The following setup instructions apply to the **actual source repository**.

## Prerequisites

* Node.js `>= 20.9`
* npm
* PostgreSQL or Supabase
* Git

---

## 1. Clone the actual repository

```bash
git clone https://github.com/warishlabs/ForgeFlow-AI.git
cd ForgeFlow-AI
```

---

## 2. Install dependencies

```bash
npm install
```

---

## 3. Configure environment variables

Create a local environment file:

```bash
cp .env.example .env.local
```

Example configuration:

```env
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=pk_test_...
CLERK_SECRET_KEY=sk_test_...

NEXT_PUBLIC_CLERK_SIGN_IN_FALLBACK_REDIRECT_URL="/dashboard"
NEXT_PUBLIC_CLERK_SIGN_UP_FALLBACK_REDIRECT_URL="/dashboard"

DATABASE_URL="postgresql://postgres:password@localhost:5432/forgeflow"
DIRECT_URL="postgresql://postgres:password@localhost:5432/forgeflow"

LLM_PROVIDER="groq"

GROQ_API_KEY=gsk_...
GOOGLE_GENERATIVE_AI_API_KEY=...
TAVILY_API_KEY=tvly_...

RESEND_API_KEY=re_...
RESEND_FROM_EMAIL="ForgeFlow AI <onboarding@resend.dev>"
```

> Never commit real API keys, database credentials, authentication secrets, or other sensitive environment variables to Git.

---

## 4. Sync the database

```bash
npx prisma db push
```

---

## 5. Start development

```bash
npm run dev
```

Open:

```text
http://localhost:3000
```

---

# 📜 Available NPM Scripts

| Command             | Purpose                                            |
| ------------------- | -------------------------------------------------- |
| `npm run dev`       | Start local development with Next.js and Turbopack |
| `npm run build`     | Build the optimized production application         |
| `npm run typecheck` | Run TypeScript strict compiler validation          |
| `npm run lint`      | Run ESLint checks                                  |

---

# 🔒 Environment Security

ForgeFlow integrates with multiple external services, so local and deployment environments require secure configuration.

Important secrets include:

```text
Clerk Keys
Database Credentials
Groq API Key
Google Gemini API Key
Tavily API Key
Resend API Key
```

For production deployments, configure these through the deployment platform's secure environment-variable system.

---

# 📁 Conceptual Repository Structure

The production source repository is organized around the application, components, agent workflows, database layer, shared libraries, and public assets.

```text
ForgeFlow-AI/
│
├── app/
│   ├── routes
│   ├── pages
│   ├── server actions
│   └── application workflows
│
├── components/
│   └── reusable UI components
│
├── lib/
│   ├── agent logic
│   ├── integrations
│   ├── utilities
│   └── application services
│
├── prisma/
│   └── database schema
│
├── public/
│   ├── logos
│   └── static assets
│
├── types/
│   └── shared TypeScript types
│
├── package.json
├── .env.example
└── README.md
```

---

# 🧠 Key Design Decision

The central design decision behind ForgeFlow can be summarized in one comparison:

### Traditional AI Assistant

```text
Prompt
  ↓
Response
  ↓
Conversation
```

### ForgeFlow AI

```text
Prompt
  +
Persistent Project State
  +
External Research
  ↓
Agent Orchestration
  ↓
LLM Reasoning
  ↓
Structured Proposal
  ↓
Human Approval
  ↓
Controlled Mutation
  ↓
Persistent State
  ↓
Audit Trail
```

The goal is to move AI from:

> **"Give me an answer."**

toward:

> **"Understand the current project, reason about the requested change, propose a structured engineering modification, and wait for human approval before applying it."**

---

# 🌟 Key Takeaways

ForgeFlow demonstrates an architecture where:

```text
       LLM
        +
   Agent Graph
        +
Persistent State
        +
 Web Research
        +
Human Approval
        +
   Auditability
        │
        ▼
Agentic Software Engineering Workflow
```

The platform combines modern full-stack engineering with applied agentic AI concepts to create a persistent, state-aware environment for software architecture and planning.

---

# 🧰 Complete Technology Matrix

| Category             | Technologies              |
| -------------------- | ------------------------- |
| **Framework**        | Next.js 16, React 19      |
| **Language**         | TypeScript 5              |
| **AI Orchestration** | LangGraph.js              |
| **LLM**              | Groq / Llama 3.3 70B      |
| **Fallback LLM**     | Google Gemini             |
| **Research**         | Tavily                    |
| **Authentication**   | Clerk                     |
| **Database**         | PostgreSQL / Supabase     |
| **ORM**              | Prisma 6                  |
| **Caching**          | Upstash Redis             |
| **Email**            | Resend                    |
| **Styling**          | Tailwind CSS, Vanilla CSS |
| **Icons**            | Lucide Icons              |
| **Deployment**       | Vercel                    |
| **Source Control**   | Git / GitHub              |

---

# 👨‍💻 Author

<p align="center">
  <strong>MD Warish Ansari</strong>
</p>

<p align="center">
  Full Stack Developer focused on production web applications and applied AI / LLM engineering.
</p>

<p align="center">
  <a href="https://portfolio.warishlabs.in">🌐 Portfolio</a>
  &nbsp;•&nbsp;
  <a href="https://github.com/mdwarishansari">💻 GitHub</a>
  &nbsp;•&nbsp;
  <a href="https://linkedin.com/in/md-warish-ansari">🔗 LinkedIn</a>
  &nbsp;•&nbsp;
  <a href="https://forgeflow.warishlabs.in">🚀 ForgeFlow AI</a>
</p>

---

# 📄 License

ForgeFlow AI is distributed under the **MIT License**.

See the complete license and implementation in the official source repository:

**[https://github.com/warishlabs/ForgeFlow-AI](https://github.com/warishlabs/ForgeFlow-AI)**

---

<p align="center">
  <img src="https://img.shields.io/badge/Built_with-Next.js-black?style=flat-square&logo=next.js" />
  <img src="https://img.shields.io/badge/Powered_by-LangGraph-FF6B6B?style=flat-square" />
  <img src="https://img.shields.io/badge/Driven_by-LLMs-8A2BE2?style=flat-square" />
  <img src="https://img.shields.io/badge/Deployed_on-Vercel-black?style=flat-square&logo=vercel" />
</p>

<p align="center">
  <strong>ForgeFlow AI</strong>
  <br />
  <em>Software idea → persistent project state → agent reasoning → structured proposal → human approval → engineering blueprint.</em>
</p>
