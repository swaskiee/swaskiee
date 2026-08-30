<!--
  SWATI DUBEY — PROFILE README
  Place this README.md in the profile repository.
  Keep chibbi.gif in the same repository root.
-->

<div align="center">

<img src="./chibbi.gif" alt="Chibbi" width="100%" />

<br/>

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&size=16&duration=2600&pause=900&color=8B5CF6&center=true&vCenter=true&width=760&lines=software+engineering+%C2%B7+AI+%C2%B7+data+%C2%B7+systems;building+things+to+understand+how+they+work;from+analytics+to+applications+to+engineering+systems;curious+by+default.+building+by+choice." alt="Animated introduction" />

<br/><br/>

<a href="https://github.com/swaskiee">
  <img src="https://img.shields.io/badge/GitHub-18181B?style=for-the-badge&logo=github&logoColor=white" alt="GitHub"/>
</a>
<a href="https://github.com/swaskiee/Gauntlet">
  <img src="https://img.shields.io/badge/GAUNTLET-18181B?style=for-the-badge&logo=github&logoColor=ef4444" alt="GAUNTLET"/>
</a>
<a href="https://github.com/swaskiee/Prism-AI-Hiring-Intelligence-Platform">
  <img src="https://img.shields.io/badge/PRISM-18181B?style=for-the-badge&logo=github&logoColor=8b5cf6" alt="PRISM"/>
</a>
<a href="https://github.com/corsairdev/corsair/pull/1230">
  <img src="https://img.shields.io/badge/OPEN%20SOURCE-MERGED-18181B?style=for-the-badge&logo=github&logoColor=22c55e" alt="Merged open source contribution"/>
</a>

</div>

<br/>

<div align="center">

```text
┌──────────────────────────────────────────────────────────────────────┐
│                                                                      │
│   learn  ───────►  build  ───────►  break  ───────►  understand     │
│      ▲                                                    │          │
│      └──────────────────── rebuild better ◄───────────────┘          │
│                                                                      │
└──────────────────────────────────────────────────────────────────────┘
```

</div>

---

## About

I’m **Swati Dubey**, a software engineering student and builder interested in the layers underneath modern software.

My work has gradually moved from learning how to analyze data and build applications toward understanding how **intelligent systems, APIs, storage engines, query systems, and production codebases** are actually put together.

I enjoy projects where the interesting part is not only what the user sees, but what happens underneath it.

```text
Data Analysis
     │
     ▼
Application Development
     │
     ▼
Applied AI
     │
     ▼
Systems Engineering
     │
     ▼
Open Source
```

The goal is simple:

> **Keep building harder things until the internals become understandable.**

---

## Current Interests

<table>
<tr>
<td width="25%" align="center">

### AI

Semantic systems  
Ranking  
Explainability  
Anomaly detection

</td>
<td width="25%" align="center">

### Systems

Persistence  
Recovery  
Indexing  
Query execution

</td>
<td width="25%" align="center">

### Engineering

APIs  
Architecture  
Testing  
Tooling

</td>
<td width="25%" align="center">

### Open Source

Integrations  
Typed systems  
Code review  
Collaboration

</td>
</tr>
</table>

---

# Selected Work

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:0f172a,50:1e1b4b,100:082f49&height=3&section=header" width="100%" alt="Animated divider"/>

</div>

## PRISM

### AI Hiring Intelligence Platform

<a href="https://github.com/swaskiee/Prism-AI-Hiring-Intelligence-Platform">
<img src="https://img.shields.io/badge/EXPLORE%20PRISM-8B5CF6?style=for-the-badge&logo=github&logoColor=white" alt="Explore PRISM"/>
</a>

<br/><br/>

PRISM is an explainable candidate-intelligence platform built around a deterministic multi-stage ranking pipeline.

Instead of treating an LLM as the entire decision engine, the system combines semantic similarity, structural constraints, behavioral signals, anomaly detection, and score fusion into a ranking workflow designed to remain inspectable.

<div align="center">

```text
┌───────────────────────┐
│   Candidate Profiles  │
└───────────┬───────────┘
            │
            ▼
┌───────────────────────┐
│ Semantic Intelligence │
│      TF-IDF + LSA     │
└───────────┬───────────┘
            │
            ▼
┌───────────────────────┐
│   Structural Rules    │
│   Hard Constraints    │
└───────────┬───────────┘
            │
            ▼
┌───────────────────────┐
│ Behavioral Signals    │
│ Trust / Activity      │
└───────────┬───────────┘
            │
            ▼
┌───────────────────────┐
│ Anomaly / Honeypot    │
│      Detection        │
└───────────┬───────────┘
            │
            ▼
┌───────────────────────┐
│ Explainable Fusion    │
│       + Ranking       │
└───────────┬───────────┘
            │
            ▼
      Ranked Candidates
```

</div>

`NLP` `semantic matching` `ranking` `explainability` `behavioral signals` `anomaly detection`

---

## GAUNTLET

### Temporal Data & Analytics Engine

<a href="https://github.com/swaskiee/Gauntlet">
<img src="https://img.shields.io/badge/EXPLORE%20GAUNTLET-EF4444?style=for-the-badge&logo=github&logoColor=white" alt="Explore GAUNTLET"/>
</a>

<br/><br/>

GAUNTLET is a purpose-built temporal data and analytics engine designed around durable storage, indexed retrieval, query execution, historical reconstruction, analytics, and explainable anomaly detection.

It explores the engineering problems that normally disappear behind mature database and analytics systems.

<div align="center">

```text
                         ┌───────────────┐
                         │   Web / CLI   │
                         └───────┬───────┘
                                 │
                         ┌───────▼───────┐
                         │  Query Engine │
                         │ Lexer → AST   │
                         │   → Executor  │
                         └───────┬───────┘
                                 │
              ┌──────────────────┼──────────────────┐
              │                  │                  │
       ┌──────▼──────┐    ┌──────▼──────┐    ┌─────▼─────┐
       │   Indexes   │    │   Temporal  │    │ Analytics │
       │ Entity/Time │    │ Reconstruction│   │ + Anomaly │
       │ Type/Bloom  │    │              │    │ Detection │
       └──────┬──────┘    └──────┬──────┘    └─────┬─────┘
              │                  │                  │
              └──────────────────┼──────────────────┘
                                 │
                         ┌───────▼───────┐
                         │Storage Engine │
                         │ WAL / Memtable│
                         │   / Segments  │
                         └───────┬───────┘
                                 │
                         ┌───────▼───────┐
                         │   Persistent  │
                         │     Data      │
                         └───────────────┘
```

</div>

`WAL` `durability` `recovery` `segments` `indexing` `query execution` `temporal data` `analytics`

---

# Open Source

## Corsair — Dropbox Sign Integration

<a href="https://github.com/corsairdev/corsair/pull/1230">
<img src="https://img.shields.io/badge/MERGED%20PULL%20REQUEST-%231230-22C55E?style=for-the-badge&logo=github&logoColor=white" alt="Merged Pull Request 1230"/>
</a>

<br/><br/>

Contributed a Dropbox Sign integration plugin to **Corsair**, an active open-source codebase.

The contribution covers:

```text
56 API operations
        │
        ├── Signature Requests
        ├── Templates
        ├── Drafts
        ├── Embedded Signing
        ├── Bulk Send
        ├── Teams
        ├── API Apps
        └── Fax / Reports
```

The integration includes:

- API-key authentication
- OAuth 2.0 authentication
- Typed request and response schemas
- Input validation
- Authenticated API client handling
- Normalized API error handling
- Endpoint-level tests
- Plugin-level tests
- TypeScript package and build configuration
- Documentation and integration work

**Merged upstream — August 29, 2026**

<a href="https://github.com/corsairdev/corsair/pull/1230">
View the contribution →
</a>

---

# Earlier Builds

The earlier projects are where the foundation started.

<table>
<tr>
<th>Project</th>
<th>What it explored</th>
<th>Technology</th>
</tr>

<tr>
<td><b>Student Registration System</b></td>
<td>CRUD workflows, persistence and server-side application development</td>
<td>Python · Flask · SQLite · HTML · CSS · Jinja2</td>
</tr>

<tr>
<td><b>Restaurant Reviews Analysis Dashboard</b></td>
<td>Data cleaning, restaurant performance, review trends and interactive business analytics</td>
<td>Microsoft Excel · Pivot Tables · Charts · Slicers</td>
</tr>

<tr>
<td><b>Vrinda Store Data Analysis</b></td>
<td>Sales performance, customer segmentation, channels, geography and business recommendations</td>
<td>Microsoft Excel · Pivot Tables · Charts</td>
</tr>

</table>

These projects may be simpler than the newer systems, but they represent the progression that led there.

---

# Engineering Toolkit

<div align="center">

<img src="https://skillicons.dev/icons?i=python,typescript,java,cpp,html,css,bash,sql,flask,nodejs,sqlite,git,github,linux,vscode" alt="Technology stack"/>

<br/><br/>

<img src="https://img.shields.io/badge/Python-18181B?style=flat-square&logo=python&logoColor=3776AB" alt="Python"/>
<img src="https://img.shields.io/badge/TypeScript-18181B?style=flat-square&logo=typescript&logoColor=3178C6" alt="TypeScript"/>
<img src="https://img.shields.io/badge/Flask-18181B?style=flat-square&logo=flask&logoColor=white" alt="Flask"/>
<img src="https://img.shields.io/badge/SQLite-18181B?style=flat-square&logo=sqlite&logoColor=003B57" alt="SQLite"/>
<img src="https://img.shields.io/badge/Git-18181B?style=flat-square&logo=git&logoColor=F05032" alt="Git"/>
<img src="https://img.shields.io/badge/Linux-18181B?style=flat-square&logo=linux&logoColor=FCC624" alt="Linux"/>

</div>

---

# How I Like to Build

<div align="center">

```text
                 ┌──────────────────────┐
                 │      Interesting     │
                 │        problem       │
                 └──────────┬───────────┘
                            │
                            ▼
                 ┌──────────────────────┐
                 │     Understand the   │
                 │       constraints    │
                 └──────────┬───────────┘
                            │
                            ▼
                 ┌──────────────────────┐
                 │     Build a small    │
                 │      working core    │
                 └──────────┬───────────┘
                            │
                            ▼
                 ┌──────────────────────┐
                 │   Test the ugly edge │
                 │       cases          │
                 └──────────┬───────────┘
                            │
                            ▼
                 ┌──────────────────────┐
                 │   Understand why it  │
                 │        works         │
                 └──────────┬───────────┘
                            │
                            ▼
                 ┌──────────────────────┐
                 │      Make it better  │
                 └──────────────────────┘
```

</div>

---

# A Few Things I Care About

```text
01  Systems that are understandable
02  Software that can explain its decisions
03  Engineering trade-offs over magic abstractions
04  Clean interfaces between components
05  Learning by building rather than only consuming
06  Code that survives beyond the happy path
07  Open-source work that can be reviewed, tested and improved
```

---

<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&size=15&duration=3200&pause=1100&color=22C55E&center=true&vCenter=true&width=650&lines=still+learning.;still+building.;still+breaking+things.;still+going+deeper." alt="Animated closing text"/>

<br/><br/>

<svg width="760" height="110" viewBox="0 0 760 110" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <linearGradient id="line" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" stop-color="#8b5cf6"/>
      <stop offset="50%" stop-color="#22d3ee"/>
      <stop offset="100%" stop-color="#22c55e"/>
    </linearGradient>
  </defs>

  <path d="M20 70 C130 20 210 20 300 65 S480 110 570 55 S670 25 740 60"
        fill="none"
        stroke="url(#line)"
        stroke-width="2"
        stroke-linecap="round"
        stroke-dasharray="8 12">
    <animate attributeName="stroke-dashoffset"
             from="0" to="-100"
             dur="2.5s"
             repeatCount="indefinite"/>
  </path>

  <circle cx="20" cy="70" r="4" fill="#8b5cf6">
    <animate attributeName="cx"
             values="20;130;300;480;570;670;740"
             dur="5s"
             repeatCount="indefinite"/>
    <animate attributeName="cy"
             values="70;28;65;103;55;30;60"
             dur="5s"
             repeatCount="indefinite"/>
  </circle>

  <circle cx="740" cy="60" r="3" fill="#22c55e">
    <animate attributeName="r"
             values="3;6;3"
             dur="1.6s"
             repeatCount="indefinite"/>
  </circle>
</svg>

<br/>

<code>curiosity → engineering → iteration</code>

<br/><br/>

<a href="https://github.com/swaskiee">
  <img src="https://img.shields.io/badge/Explore%20the%20repositories-18181B?style=for-the-badge&logo=github&logoColor=white" alt="Explore repositories"/>
</a>

</div>

<!--
  PROFILE README NOTES

  1. chibbi.gif should remain in the profile repository root.
  2. GitHub may sanitize inline SVG elements in README rendering.
  3. The README therefore also uses animated external SVG services
     for typing/divider effects and the local chibbi.gif as the hero.
  4. No GitHub contribution graph or streak chart is used.
-->

