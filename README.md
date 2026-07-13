# Masayoshi Nakamura - Portfolio (July 2026)

## 1. Introduction

I specialize in **high-velocity, high-quality iterative development** powered by **Grok Build**.

Drawing on experience as a Scrum Product Owner and Scrum Master, I start each cycle by defining clear iteration goals and scope. Implementation follows **Test-Driven Development (TDD)**. When beneficial for GenAI features, I integrate **G-Eval** evaluations into CI/CD pipelines.

Deployment platforms are chosen pragmatically per project — AWS, Vercel, Railway, and others.

To balance speed with deployment safety, all merges to the protected `main` (master) branch require explicit human review and approval. AI agents are intentionally restricted from directly pushing or merging to production branches.

All currently live portfolio projects were developed end-to-end using Grok Build.

## 2. Core Competencies

- **AI-Assisted Iterative Development:** Grok Build (iteration planning, TDD-first workflows)
- **Backend:** Python (FastAPI), JavaScript/TypeScript
- **Frontend & CMS:** Sanity (headless CMS), Vercel-optimized web apps
- **GenAI:** xAI API (TTS and conversational capabilities)
- **CI/CD & Quality:** GitHub Actions with human gate on `main`, optional G-Eval integration
- **Cloud & Platforms:** AWS (selective use of CDK/IaC), Vercel, Railway
- **Practices:** Scrum, TDD, pragmatic Infrastructure as Code, GitOps with safety guardrails
- **Tooling:** Docker, Git, modern Python/JS tooling

## 3. Live Projects (All developed with Grok Build)

### Project 1: Notion-like Blog Engine (Sanity + Vercel)

A modern, Notion-inspired blog and content publishing platform.

- **Sanity** serves as the flexible headless CMS for structured content management and real-time collaboration feel.
- Frontend and hosting on **Vercel** for instant previews, edge deployment, and excellent DX.
- Developed through planned iterations: Scrum-style goal setting → TDD implementation → human-reviewed merge to production.
- Focus on clean UX, content flexibility, and fast release cycles.

- **Live:** https://blog.masanakamuraconsulting.com/
- **Repo:** https://github.com/masayang/sanity-nextjs-blog (Private)

### Project 2: TTS Chatbot using xAI API

An interactive chatbot featuring high-quality text-to-speech powered by the **xAI API**.

- Natural conversation interface with voice output.
- Built entirely with Grok Build-driven iterative development (planning → TDD → optional evaluation → deploy).
- Deployed to a lightweight, fast-iteration platform (Vercel or Railway).

- **Live:** https://chatbot.masanakamuraconsulting.com/
- **Repo:** https://github.com/masayang/chatbot-by-grok-build

## 4. Development Approach

- **Iteration Planning:** Apply Scrum PO/SM knowledge to create focused, valuable iteration plans before coding.
- **Implementation:** Strict TDD for reliability and rapid feedback loops.
- **GenAI Quality:** Selectively introduce G-Eval or similar automated evaluations into CI/CD.
- **Safety First:** Protected `main` branch + mandatory human approval before any production deployment. Agents never merge directly.
- **Platform Flexibility:** Choose the most suitable deployment target (AWS, Vercel, Railway, etc.) instead of being locked into one stack.

## Archived Work

The previous RAG API platform (Bedrock + LangChain, hosted via AWS CDK IaC with GitHub Actions CI/CD) and its demo system have been retired. Source code and related diagrams have been archived.
