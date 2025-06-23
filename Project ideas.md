
### 1. NeuraNotes – AI-First Smart Note System

A full-stack app where users can write, organize, and analyze notes— with the help of AI features like summarization and topic extraction

**Features**
- AI Summarization
- Automated graph view organization
- Collaborations


**Stack**
- Frontend - React + TypeScript + Tailwind + Zustand
- Backend - Go
- Database - Postgres
- AI - local model
- Storage - S3
- Deployment - Docker Compose + Fly.io
- CI/CD - Github actions


**Frontend**
- Note editor
- Real-time readme
- Login page
- Graph view
- Github connection


**Backend**
- JWT/google auth
- AI endpoints
- Database
- Local LLM



---

### 2. Vizual – AI-powered visual-coding dev tool

An AI-powered visual coding platform for building full-stack, cross-platform apps — aimed at beginner developers, indie hackers, and teams — with real code export.

Developing with web techniques - applied to everything

**Design rule**
- Each module should encapsulate its own logic and internal data.
- Dependency Inversion: Modules depend on **interfaces**, not implementations.
- Event-Driven Communication with event bus (in-memory, Kafka).


**Core Constructs of VizualScript**
- Primitives
- Functions (Nodes)
- Interfaces (API)
- UI Description
- Database


**Compilation targets**
- Backend Monolith
- Microservices
- Frontend


**To-Do For MVP**
- Visually define UI & Logic
- Compile into code


**Steps to Launch**
- [ ] `VizualScript 0.1` Format
	- [ ] for API
	- [ ] for UI (Block, Text, Event)
- [ ] Python compiler 0.1
	- [ ] API compiler
	- [ ] UI compiler
- [ ] Landing page
- [ ] Visual Builder



---

I'm building a project called **Vizual** — an AI-first, visual coding platform that sits between no-code and traditional coding. It's designed to let beginner developers, startups, and "vibe coders" build full-stack, cross-platform apps visually.

Projects in Vizual are defined using a **visual scripting system** called **VizualScript**, which can describe:

- Backend logic (functions, APIs, DB models)
    
- Frontend UI layouts and component behavior
    
- Communication between microservices or modules
    
- External API integrations
    

The same project can be compiled to:

- A backend monolith (e.g., Go or Python)
    
- A distributed microservice system
    
- A desktop app or web frontend
    

Vizual is not just another no-code tool — it's a **declarative-first abstraction layer** over real code (Go, TS, etc.), focused on **developer empowerment**, not hiding complexity.

I need help designing features, architecture, and MVPs that make this platform useful, scalable, and intuitive.

---

### For Reddit

Hey everyone!

I'm a solo builder and I’ve been working on a project called **Vizual** — it’s an AI-powered visual coding platform that helps people design full-stack applications **and export real production code**, not just prototypes.

🛠️ Why I built this:
I noticed that most visual or no-code tools are either too simple (like Scratch) or not flexible enough to build real-world apps. And traditional tools can feel overwhelming for beginners or solo indie makers.

So I thought… what if you could:
- visually design apps (frontend, backend, API, DB),
- use AI to help you build logic/structure, and
- export clean, editable code for **React, Node, etc.**

 🚀 What it does:
- Visual drag-and-drop UI builder with real component system
- Visual scripting for APIs and logic
- Database schema builder
- Real code export (React, Express, etc.)
- AI help for logic, refactoring, design hints

It’s like **Figma meets GitHub Copilot**, but full-stack.

 🔍 Why I'm here:
I’d love to get your honest feedback — whether you're learning to code, building your own startup, or teaching programming.

I'm offering **free early access** for anyone curious. You can check it out here: [Landing Page Link or DM me]

Thanks for reading, happy to answer any questions or hear your thoughts!

— [Your Name or Reddit handle]

---

---
### Frontend Editor (UI + Logic)



---
### Backend Editor (API + Database)



---
### Project Editor (microservices + brokers)

Service-first

**Project**
- Services

**Frontend Service**
- UI

**Backend Service**
- API

**UI**
- tree of components where each can call action

**Component**
- a function that returns UI and can have state

**Action**
- basically a function
- described with VizualScript

**VizualScript (VS)**
- Static- & strong-typed scripting language that describes logic (data transformation)
- Is to be trans-compiled to any targer language (Go, TypeScript, Python)

**Block**
- Main UI primitive and action caller
- Action are called by triggers (eg. onClick, onHover)
- Blocks are used in building components (main UI abstraction in real code. When code is generated, blocks are represented with divs, appropriate CSS and hooks like useState, useRef etc.)
- Blocks are mostly like a flexbox container with style adaptations like in CSS (background, border, border radius etc.)




### One-Pager Pitch

**Vizual – One-Pager Pitch**

🪄 What Is Vizual?

**Vizual** is an **AI-powered visual development platform** that lets you design, build, and compile real, cross-platform applications — without writing traditional code.

It’s **not** no-code. It’s **not** a drag-and-drop toy.  
It’s a new **visual programming paradigm** that’s as powerful as real code — and far easier to start with.

---

🧱 What You Can Build with Vizual

- 🧩 **Frontend apps** for web, mobile, desktop
    
- ⚙️ **Backends** as monoliths or microservices
    
- 🔌 **Custom APIs**, workflows, and logic
    
- 🗃️ **Databases, schemas**, and admin panels
    
- 📦 Compile to real code in **Go, TypeScript, Python, etc.**
    

---

 🧠 Why It's Different

|Vizual|Traditional No-Code|Traditional Coding|
|---|---|---|
|Declarative + visual|Click-based + limited|Manual and verbose|
|Compiles to real code|Locked to platform|Full control, but high friction|
|Backend + frontend|Mostly frontend|Full stack|
|Flexible architecture|Preset templates|Infinite, but DIY|
|Easy to learn|Easy to use|Hard to master|

---

 🔧 How It Works

Behind the scenes, Vizual uses a custom **visual scripting language** called **VizualScript**, which acts like a **universal app interface**:

- All logic, API, database, and UI structure is represented in a **visual, connected graph**
    
- That graph is compiled to real, production-grade code
    
- You can choose to compile as:
    
    - A **Go monolith**
        
    - A **React frontend + FastAPI backend**
        
    - A **microservice system with queues**
        
    - Or even a desktop app
        

Think of Vizual as:

> 🎮 **Unreal Engine Blueprints**  
> 🎨 meets **Figma simplicity**  
> 🧠 meets **Go/Python-level power**

---

 🔥 Who It's For

- 🛠️ Makers, indie hackers, startup founders
    
- 🧑‍💻 Devs who want to move fast without boilerplate
    
- 🎨 Designers who want to build real apps
    
- 🧪 Technical founders prototyping MVPs fast
    

If you know what a **database**, an **API**, and a **function** are — you can use Vizual.

---

 🚀 Why It Matters

Building a real app today requires choosing frameworks, setting up CI, managing folders, connecting DBs, learning a dozen tools.

**Vizual removes all of that — without removing the power.**  
You focus on **designing your system**, and Vizual compiles it into real code, deployable anywhere.

---

 🗣 TL;DR Elevator Pitch

> Vizual is a visual-first, AI-powered app compiler that lets you build and ship full-stack, cross-platform apps in minutes — not weeks. It combines the ease of no-code with the power of real code, compiling your logic, UI, and data into production-grade software in Go, TypeScript, Python, or whatever stack you choose.