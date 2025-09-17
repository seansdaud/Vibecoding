# Vibecoding
Zero-setup US-based AI hackathon starter kit. Next.js frontend, FastAPI backend, GPT-4.1, LangChain + Pinecone RAG, Supabase, ElevenLabs voice, Vercel &amp; Railway deployment, GitHub Actions CI/CD, and ready-to-use Codespaces for instant cloud development.
# 🇺🇸 VibeHack US Starter Kit

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![Vercel](https://img.shields.io/badge/Deploy-Frontend-blue)](https://vercel.com/new)
[![Railway](https://img.shields.io/badge/Deploy-Backend-brightgreen)](https://railway.app/new/template?git=https://github.com/<your-username>/vibehack-us-starter)

Zero-setup US-based AI hackathon starter kit built for rapid prototyping:

* **Frontend:** Next.js 14 + Tailwind + ShadCN UI
* **Backend:** FastAPI (Python)
* **AI:** OpenAI GPT-4.1
* **RAG:** LangChain + Pinecone (US region)
* **Database:** Supabase + pgVector
* **Voice:** ElevenLabs + Whisper
* **Deployment:** Vercel (frontend) + Railway (backend)
* **CI/CD:** GitHub Actions
* **Cloud Dev:** GitHub Codespaces ready

---

## 🏁 Quick Start

### 1️⃣ Clone & Install

```bash
git clone https://github.com/<your-username>/vibehack-us-starter.git
cd vibehack-us-starter
cp .env.example .env
npm install
npm run dev
```

### 2️⃣ Environment Variables

```env
OPENAI_API_KEY=sk-xxxxxx
PINECONE_API_KEY=xxxxxx
SUPABASE_URL=https://your-project.supabase.co
SUPABASE_ANON_KEY=xxxxxx
ELEVENLABS_API_KEY=xxxxxx
```

### 3️⃣ Run Locally

```bash
npm run dev
```

Visit [http://localhost:3000](http://localhost:3000) to start using the app.

---

## 🚀 Deployment

### Frontend (Vercel)

[![Deploy Frontend](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https://github.com/<your-username>/vibehack-us-starter&project-name=vibehack-frontend&repo-name=vibehack-frontend)

### Backend (Railway)

[![Deploy Backend](https://img.shields.io/badge/Deploy%20Backend-Railway-brightgreen)](https://railway.app/new/template?git=https://github.com/<your-username>/vibehack-us-starter)

**CI/CD:** Auto-deploys on push to `main` once secrets are configured.

---

## ☁️ Cloud Development

**GitHub Codespaces** is preconfigured:

* Opens full dev environment instantly
* Installs backend dependencies and Node packages
* Includes Python + Node features
* Recommended machine: 4-core / 8GB RAM

Launch: **Code → Codespaces → Create Codespace on Main**

---

## 📂 Project Structure

```text
vibehack-us-starter/
├── frontend/                # Next.js + Tailwind UI
├── backend/                 # FastAPI + LangChain pipeline
├── ai/                      # RAG examples, embeddings
├── .github/
│   ├── workflows/deploy.yml # CI/CD
│   └── codespaces/devcontainer.json # Codespaces
├── railway.json             # Railway deployment config
├── .env.example
└── README.md
```

---

## 💡 Vibe-Coding Tips

* Use **Cursor AI**, **Bolt.new**, or GPT prompts to generate code instantly.
* Extend RAG pipelines in `ai/chains/`.
* Integrate ElevenLabs TTS or Whisper for voice features.
* Test locally before pushing — CI/CD redeploys automatically.
* Codespaces enables **zero local setup**.

---

## ✅ Hackathon Deliverables

1. Deployed app links (Vercel + Railway)
2. Public GitHub repository
3. 2-minute demo video (optional)

---

## 🔒 Compliance & Data Residency

* All services are US-hosted or US-region selectable.
* No EU data transfers.
* SOC 2 / HIPAA-ready components where possible.

---

## 🏆 Happy Hacking!

Get started quickly and focus on building AI-first products with vibe-coding!
