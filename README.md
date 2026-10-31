<a href="https://yash-gurav-portfolio.vercel.app"><img src="assets/portfolio.png" alt="Yash Gurav: Don't read my resume. Ask it." width="100%"></a>

# Hi, I'm Yash 👋

AI engineer in Mumbai. I fine-tune small open models, build agents that are allowed to say "I don't know", and ship internal tools to people who aren't engineers.

**Portfolio:** [yash-gurav-portfolio.vercel.app](https://yash-gurav-portfolio.vercel.app). It has an AI agent that answers questions about my work, cites its sources, and lets you try to break it.

[![Portfolio](https://img.shields.io/badge/Portfolio-ff8f3f?style=flat-square&logoColor=black)](https://yash-gurav-portfolio.vercel.app)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/yash-gurav-58bbba21a/)
[![X](https://img.shields.io/badge/X-000000?style=flat-square&logo=x&logoColor=white)](https://x.com/yash_gurav_2002)
[![Hugging Face](https://img.shields.io/badge/Hugging%20Face-FFD21E?style=flat-square&logo=huggingface&logoColor=black)](https://huggingface.co/Yash-2002)
[![Email](https://img.shields.io/badge/yashgurav002%40gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:yashgurav002@gmail.com)

---

## Selected work

| Project | What it is | Result | Links |
|---|---|---|---|
| **[PF Desk](https://github.com/Yashgurav002/pf-desk)** | A private back office for Provident Fund consultants: pre-checks claims and decodes EPFO rejection remarks into fixes, on a laptop. Qwen3-8B + LoRA, Temporal, PGlite + pgvector, Next.js | **72%** correct on 148 real remarks it never saw, vs 53% for the base model | [Case study](https://yash-gurav-portfolio.vercel.app/work/pf-desk) · [Demo](https://pfdesk.buildwithyash.tech) |
| **[Sitspot](https://github.com/Yashgurav002/sitspot)** | A proactive voice agent that watches outdoor spots with open data and calls you when a good window opens. Temporal, MCP, Gemma, ElevenLabs | Unsafe advice cut from **12.5% to 2.5%** after red-teaming | [Case study](https://yash-gurav-portfolio.vercel.app/work/sitspot) · [Demo](https://sitspot.vercel.app) |
| **[Hearsay](https://github.com/Yashgurav002/hearsay)** | Agent memory for game characters: they remember what you did and gossip along trust lines, with provenance. FalkorDB, FastAPI, React Three Fiber | **500** worlds load-tested at ~1 ms reads | [Case study](https://yash-gurav-portfolio.vercel.app/work/hearsay) · [Demo](https://hearsay-six.vercel.app) |
| **Divine Solitaires** (work) | Internal tools for pricing, inventory custody, dashboards and a savings scheme, used daily by non-technical teams | **90%+** less time to price a batch; a ledger race closed across 9 writers | [Case study](https://yash-gurav-portfolio.vercel.app/work/divine) |

<details>
<summary><b>Earlier projects</b></summary>

- **[Chat with PDF](https://github.com/Yashgurav002/-chat-with-pdf)**: RAG with token streaming and source attribution. FastAPI, LangChain, ChromaDB, Groq. [Demo](https://chat-with-pdf-amber-chi.vercel.app/)
- **[TacticLens](https://github.com/Yashgurav002/TacticsLens-)**: a football tactics RAG chatbot grounded in StatsBomb data. [Demo](https://yash-2002-tacticlens.hf.space)
- **[UrbanSage](https://github.com/Yashgurav002/urbansage-project)**: a civic platform with DistilBERT complaint classification. Next.js, React Native, FastAPI
- **Jeev Rakshak**: real-time animal detection with YOLOv7 and a React alert dashboard

</details>

---

## Experience

| Period | Role |
|---|---|
| Jul 2026 – now | **Junior Front End Engineer**, R S Diamond (Divine Solitaires) |
| Mar 2026 – Jul 2026 | **Founding Engineer (Tech & Operations)**, Pioneer Sports Consultancy |
| Jan 2026 – Jul 2026 | **Consultant (freelance, part-time)**, Sportify LLP |
| Dec 2024 – Mar 2026 | **Assistant System Engineer**, Tata Consultancy Services |
| Oct 2023 – Feb 2024 | **Full Stack Developer Intern**, K3Y Technology Services (Sahayata24x7) |

**Education:** B.E. in Artificial Intelligence and Data Science, Fr. Conceicao Rodrigues College of Engineering, Mumbai University. CGPA 9.51/10.

**Certifications:** Oracle Cloud Infrastructure Generative AI Professional (2025), AI Foundations Associate (2025), Foundations Associate (2025).

---

## How I work

Spec first, then build with Claude Code, Codex and Cursor inside guardrails I set up: an impact check before editing inherited code, no writes to live data, and end-to-end checks on every change. I measure with evals, keep the baselines and the failures, and label synthetic data as synthetic.

**Stack:** Python · TypeScript · Next.js · React · FastAPI · Django · Hono · PostgreSQL + pgvector · FalkorDB · Temporal · Docker · LoRA fine-tuning · RAG and hybrid search · agents and tool calling · MCP · Ollama · llama.cpp
