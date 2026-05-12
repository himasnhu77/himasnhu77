<!-- Header -->
<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=22&pause=1000&color=1D9E75&center=true&vCenter=true&width=600&lines=Building+Voice+AI+%2B+Memory+Systems;Agentic+AI+%7C+Graph+RAG+%7C+Neo4j;2027+Batch+%40+IIIT+Bhagalpur" alt="Typing SVG" />

<br/>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=flat-square&logo=linkedin)](https://www.linkedin.com/in/himanshu-tiwari-97a738291/)
[![LeetCode](https://img.shields.io/badge/LeetCode-1000%2B_solved-FFA116?style=flat-square&logo=leetcode&logoColor=white)](https://leetcode.com/u/HimanshuTiwari206123/)
[![GitHub](https://img.shields.io/badge/GitHub-himasnhu77-181717?style=flat-square&logo=github)](https://github.com/himasnhu77)

</div>

---

## 🧠 Who I Am

I'm a final-year CSE student at **IIIT Bhagalpur (2027)** who builds production-grade AI systems — not just toy demos.

My core obsession: **voice AI + persistent memory**. I've shipped a multi-tenant calling agent where every conversation updates a live Neo4j knowledge graph — the AI actually remembers callers across sessions.

I've contributed **architecture recommendations** to YC-backed startups in the GenAI and Agentic AI space, and I've gone deep on Speech-to-Speech pipelines, Graph RAG, MCP tooling, and LLM orchestration.

---

## 🏗️ Signature Projects

### 🎙️ [AI Calling Agent](https://github.com/himasnhu77/ai-calling-agent) — Production Voice AI with Graph Memory

> A real-time voice AI system where the agent **remembers every caller** using a Neo4j knowledge graph.

**Full Stack:**
```
Twilio (media stream) → Deepgram nova-2-phonecall (STT)
  → Ollama qwen2.5:1.5b (LLM reasoning)
    → Neo4j Aura (Caller + Entity + Memory graph nodes)
      → ElevenLabs cloned voice ulaw_8000 (TTS)
        → Tavily (real-time web search)
```

**What makes it non-trivial:**
- Cross-call memory: `Caller → REMEMBERS → Memory → ABOUT → Entity` graph
- Multi-tenant architecture with per-tenant Neo4j isolation
- Deployed on AWS EC2 (t3.medium) with PM2 + Nginx reverse proxy
- Debugged Deepgram 1005 WebSocket closures + ElevenLabs stream buffering in prod

---

### 🤖 [Multi-Agent Calling Orchestrator](https://github.com/himasnhu77/multi-calling-agent-with-knowledge-base-orchestrator-agent)

> Orchestrator agent that routes inbound calls to specialist sub-agents based on intent, with a shared knowledge base.

- Intent classification → dynamic agent routing
- Shared knowledge base across agent pool
- Built for multi-domain call center use cases

---

### 🎤 [Voice Cloning Pipeline](https://github.com/himasnhu77/VOICE-CLONING)

> Custom voice cloning and synthesis pipeline using ElevenLabs API with ulaw_8000 output for telephony.

---

## ⚡ Technical Depth

| Domain | Stack |
|--------|-------|
| **Voice AI** | Deepgram STT, ElevenLabs TTS, Voice Cloning, Twilio Media Streams |
| **LLM & Memory** | Ollama, Neo4j Graph RAG, Qdrant, LangChain, MCP |
| **Agentic AI** | Multi-agent orchestration, n8n, tool-use pipelines |
| **Backend** | Node.js, Express, Python, FastAPI, WebSockets |
| **Infra** | AWS EC2, PM2, Nginx, Docker, PostgreSQL, Redis |
| **Frontend** | React.js, TypeScript, Next.js |

---

## 📊 Stats

<div align="center">

![LeetCode Stats](https://leetcard.jacoblin.cool/HimanshuTiwari206123?theme=nord&font=Fira%20Code&ext=heatmap)

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=himasnhu77&show_icons=true&theme=dark&hide_border=true&count_private=true)

</div>

---

## 🔍 What I'm Building Next

- 📞 **AI Email Client** — replies in your voice using a cloned voice model + style RAG
- 🎬 **Animano** — manga → cinematic shorts via multi-agent AI pipeline
- 🔌 **CRM Copilot** — Chrome extension that auto-fills partner forms from CRM data during live calls

---

<div align="center">
  <i>Open to referrals, collaborations, and conversations about AI infrastructure.</i><br/>
  <b><a href="https://www.linkedin.com/in/himanshu-tiwari-97a738291/">Connect on LinkedIn ↗</a></b>
</div>
