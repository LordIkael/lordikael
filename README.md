<!-- ╔══════════════════════════════════════════════════════════╗
     ║                  LORD IKAEL / PROFILE                  ║
     ╚══════════════════════════════════════════════════════════╝ -->

<div align="center">

# `@tamegnontech`

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=24&duration=2800&pause=900&color=00F5D4&center=true&vCenter=true&width=760&lines=SOFTWARE+ENGINEERING;ARTIFICIAL+INTELLIGENCE;CYBERSECURITY;DATA+%26+INTELLIGENT+SYSTEMS;ROBOTICS+%26+EMBEDDED+SYSTEMS" alt="Typing animation" />

### Jean-Marie AGBANGLA

**aka `Lord Ikael`**

`Software Developer` · `AI & Data` · `Cybersecurity` · `Robotics`

<br>

[![GitHub](https://img.shields.io/badge/GitHub-tamegnontech-111111?style=for-the-badge\&logo=github\&logoColor=white)](https://github.com/tamegnontech)
[![Email](https://img.shields.io/badge/Email-tamegnontech%40gmail.com-111111?style=for-the-badge\&logo=gmail\&logoColor=EA4335)](mailto:tamegnontech@gmail.com)
[![Profile Views](https://komarev.com/ghpvc/?username=tamegnontech\&style=for-the-badge\&color=00F5D4\&label=PROFILE+VIEWS)](https://github.com/tamegnontech)

</div>

---

## `01 / WHO AM I`

I'm **Jean-Marie AGBANGLA**, an **Electrotechnics student and software developer** interested in what happens underneath the interface.

I like building things, taking them apart, understanding the decisions behind them, and making them better.

My interests sit at the intersection of:

```text
 SOFTWARE ENGINEERING
          │
     ┌────┼────┐
     │    │    │
    WEB  DATA  SYSTEMS
     │    │    │
     └────┼────┘
          │
         AI
          │
     ┌────┴────┐
     │         │
 SECURITY   ROBOTICS
```

I'm not trying to collect frameworks.

I'm trying to build the engineering foundations to **design systems, reason about them, secure them and evolve them**.

---

# `02 / CURRENTLY BUILDING`

## 🔧 FIXA

### `Client ↔ Professional Infrastructure`

**FIXA** is a platform I am building to connect clients with technical professionals and artisans, starting with **Parakou, Benin**.

The idea is simple:

> Find the right professional.
> Make the interaction trustworthy.
> Turn a request into a real mission.

But underneath that simple experience is a much deeper system.

### Core flow

```text
┌──────────────┐
│    REQUEST   │
└──────┬───────┘
       ↓
┌──────────────┐
│   MATCHING   │
└──────┬───────┘
       ↓
┌──────────────┐
│ PROFESSIONAL │
└──────┬───────┘
       ↓
┌──────────────┐
│     CHAT     │
└──────┬───────┘
       ↓
┌──────────────┐
│    QUOTE     │
└──────┬───────┘
       ↓
┌──────────────┐
│    MISSION   │
└──────┬───────┘
       ↓
┌──────────────┐
│   PAYMENT    │
└──────┬───────┘
       ↓
┌──────────────┐
│   REVIEW     │
└──────────────┘
```

### What FIXA is solving

* 🔎 Professional discovery & matching
* 📍 Service areas & geolocation
* ⭐ Reputation & reviews
* 📋 Requests & missions
* 💬 Context-aware messaging
* 📝 Diagnostics & quotations
* 🔐 Identity verification
* 👥 Role-based permissions
* 🛡️ Fraud & circumvention controls
* 📊 Operational metrics

### Product principles

```text
TRUST
  ↓
IDENTITY
  ↓
MATCHING
  ↓
TRANSACTION
  ↓
REPUTATION
```

The MVP is designed as a **mobile-first PWA** backed by a **modular monolith**, with **PostgreSQL/PostGIS**, private object storage and asynchronous processing through an **outbox/worker pattern**.

---

# `03 / SYSTEM DESIGN`

### FIXA — simplified architecture

```text
                         ┌───────────────────────┐
                         │       CLIENTS         │
                         │     PROFESSIONALS     │
                         └───────────┬───────────┘
                                     │
                                     ▼
                         ┌───────────────────────┐
                         │       PWA / WEB       │
                         │    Mobile-first UI    │
                         └───────────┬───────────┘
                                     │
                                     ▼
                   ┌─────────────────────────────────┐
                   │          API / BACKEND          │
                   │                                 │
                   │ Auth      Matching    Missions  │
                   │ Messaging Reviews     Payments  │
                   │                                 │
                   │        Modular Monolith         │
                   └──────────────┬──────────────────┘
                                  │
              ┌───────────────────┼───────────────────┐
              │                   │                   │
              ▼                   ▼                   ▼
     ┌────────────────┐  ┌────────────────┐  ┌─────────────────┐
     │   PostgreSQL   │  │ Private Object │  │ Outbox / Worker │
     │    + PostGIS   │  │    Storage     │  │   Async Jobs    │
     └────────────────┘  └────────────────┘  └─────────────────┘
```

### Engineering priorities

```text
Security
   │
Data integrity
   │
Maintainability
   │
Controlled complexity
   │
Observability
   │
Scalability
```

I prefer a system that is **simple enough to understand** and **structured enough to evolve**.

---

# `04 / STACK`

### Languages

<p align="left">
<img src="https://skillicons.dev/icons?i=html,css,js,ts,python" />
</p>

### Frontend

<p align="left">
<img src="https://skillicons.dev/icons?i=react,vite" />
</p>

`React` · `Vite` · `PWA` · `Responsive Design`

### Backend

<p align="left">
<img src="https://skillicons.dev/icons?i=nodejs" />
</p>

`Node.js` · `Fastify` · `REST` · `OpenAPI`

### Database & Data

<p align="left">
<img src="https://skillicons.dev/icons?i=postgres,prisma" />
</p>

`PostgreSQL` · `PostGIS` · `Prisma`

### DevOps / Environment

<p align="left">
<img src="https://skillicons.dev/icons?i=git,github,docker,linux,bash" />
</p>

`Git` · `GitHub` · `GitHub Actions` · `Docker` · `Linux` · `Bash`

---

# `05 / AI + DATA`

I don't want AI to be just an API call hidden behind a button.

I'm interested in the engineering side of intelligent systems:

```text
          DATA
           │
           ▼
      PROCESSING
           │
           ▼
       FEATURES
           │
           ▼
        MODELS
           │
           ▼
       PREDICTION
           │
           ▼
      APPLICATION
```

### Areas I'm exploring

`Machine Learning`

`Data Science`

`Data Analysis`

`Recommendation Systems`

`AI Agents`

`Natural Language Processing`

`AI-assisted Engineering`

The goal is to understand both sides:

**building software that uses AI**
and
**understanding the systems that make AI useful**.

---

# `06 / CYBERSECURITY`

Security is not something I want to bolt onto an application at the end.

I want to understand security at the **architecture level**.

### Offensive side

```text
Recon
  ↓
Enumeration
  ↓
Attack Surface
  ↓
Exploitation
  ↓
Privilege / Access
  ↓
Impact
```

Areas of interest:

`Web Application Security`

`Penetration Testing`

`Vulnerability Research`

`Network Security`

`Ethical Hacking`

`Red Team Methodologies`

### Defensive side

`Secure Development`

`Authentication`

`Authorization`

`RBAC`

`Threat Modeling`

`Logging`

`Auditing`

`Application Security`

`Security Architecture`

The mindset is simple:

> **Build it. Break it. Understand it. Secure it.**

---

# `07 / ROBOTICS`

My Electrotechnics background gives me a second perspective on engineering:

**software is not the whole system.**

I'm also interested in:

```text
ELECTRONICS
     +
PROGRAMMING
     +
CONTROL
     +
AUTOMATION
     +
AI
     ↓
INTELLIGENT SYSTEMS
```

Exploration areas:

`Embedded Systems`

`Robotics`

`Automation`

`IoT`

`Control Systems`

`Hardware / Software Integration`

---

# `08 / LINUX`

My main development environment is **Fedora Linux**.

The terminal is not just a place where I run commands.

It's part of how I understand the system.

### Currently strengthening

```bash
shell scripting
filesystem
permissions
processes
package management
git
CLI workflows
development environments
```

I enjoy working close to the system because it forces me to understand what is actually happening.

---

# `09 / ENGINEERING NOTES`

Things I care about more than knowing the newest framework:

```text
        ┌─────────────────────────┐
        │        SOFTWARE         │
        └────────────┬────────────┘
                     │
             ┌───────┴───────┐
             ▼               ▼
           DATA            LOGIC
             │               │
             └───────┬───────┘
                     ▼
                 ARCHITECTURE
                     │
             ┌───────┴───────┐
             ▼               ▼
          SECURITY        RELIABILITY
             │               │
             └───────┬───────┘
                     ▼
                   SYSTEM
```

Questions I naturally ask when building:

> Where does the data go?

> What happens when this fails?

> Who is allowed to do this?

> What happens under bad input?

> What happens when two requests arrive at the same time?

> What happens if the network disappears?

> How could someone abuse this system?

Those questions interest me more than simply making a demo work.

---

# `10 / GITHUB // BUILD LOG`

This profile is where I document the things I'm actually building and learning.

### `@tamegnontech`

[![Repositories](https://img.shields.io/badge/Explore_my_repositories-111111?style=for-the-badge\&logo=github\&logoColor=white)](https://github.com/tamegnontech?tab=repositories)

[![GitHub Stats](https://github-readme-stats.vercel.app/api?username=tamegnontech\&show_icons=true\&hide_border=true\&bg_color=00000000\&title_color=00F5D4\&icon_color=00F5D4\&text_color=9CA3AF\&rank_icon=github)](https://github.com/tamegnontech)

[![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=tamegnontech\&layout=compact\&hide_border=true\&bg_color=00000000\&title_color=00F5D4\&text_color=9CA3AF)](https://github.com/tamegnontech)

[![GitHub Streak](https://streak-stats.demolab.com?user=tamegnontech\&hide_border=true\&background=00000000\&ring=00F5D4\&fire=00F5D4\&currStreakLabel=00F5D4\&sideLabels=9CA3AF\&dates=9CA3AF)](https://github.com/tamegnontech)

### What matters here

```text
Repositories
   ↓
Experiments
   ↓
Architecture
   ↓
Lessons
   ↓
Better Systems
```

The objective is not to make the graph look impressive.

It's to leave a **trace of real work**.

---

# `11 / CURRENT OBJECTIVE`

```text
NOW
 │
 ├── Stronger software fundamentals
 │
 ├── Full-stack engineering
 │
 ├── Backend architecture
 │
 ├── Data & AI
 │
 ├── Cybersecurity
 │
 └── Robotics
        │
        ▼
   DEEPER SYSTEMS
        │
        ▼
  SOFTWARE ENGINEERING
        │
        ▼
    AI ENGINEERING
        │
        ▼
SECURITY-FOCUSED ENGINEERING
```

I'm especially interested in projects where several of these domains collide.

---

# `12 / SELECTED BUILD`

<div align="center">

## 🔧 FIXA

### `Client ↔ Professional Platform`

**Parakou · Benin**

`PWA` · `Node.js` · `Fastify` · `PostgreSQL` · `PostGIS` · `Prisma`

**Request → Matching → Conversation → Quote → Mission → Review**

[![Explore FIXA](https://img.shields.io/badge/FIXA-111111?style=for-the-badge\&logo=github\&logoColor=white)](https://github.com/tamegnontech)

</div>

---

# `13 / CONTACT`

<div align="center">

### Jean-Marie AGBANGLA

`@tamegnontech`

[![Email](https://img.shields.io/badge/tamegnontech%40gmail.com-111111?style=for-the-badge\&logo=gmail\&logoColor=EA4335)](mailto:tamegnontech@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-111111?style=for-the-badge\&logo=github\&logoColor=white)](https://github.com/tamegnontech)

<br>

```text
BUILD
  ↓
BREAK
  ↓
UNDERSTAND
  ↓
SECURE
  ↓
IMPROVE
```

### `Still building. Still learning. Still going deeper.`

</div>
<!-- END -->
