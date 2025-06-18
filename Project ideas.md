
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


> **DIP** as a golden compromise between hard code and soft code


**Design rule**
- Each module should encapsulate its own logic and internal data.
- Dependency Inversion: Modules depend on **interfaces**, not implementations.
- Event-Driven Communication with event bus (in-memory, Kafka).




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
- Some action can be caller by triggers
- **Trigger**
	- eg. onClick, onHover