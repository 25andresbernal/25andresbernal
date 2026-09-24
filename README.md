# Andre Bernal

**AI Product Manager who builds. Agentic systems, voice agents, RAG, evals, and the strategy to ship them inside real companies.**

I'm an AI Product Manager who ships. Currently at Savage Companies as a Sr Manager, Applied AI, where I own AI product strategy and the agentic
workflows that put it into practice. I also work on voice agents,
RAG systems, fine-tuning pipelines, and the evals that keep all of it
honest. I care most about the gap between a model demo and a system a
real company can run on.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-andrebernall-0A66C2?style=flat)](https://www.linkedin.com/in/andrebernall)
[![Email](https://img.shields.io/badge/Email-25andresbernal%40gmail.com-D14836?style=flat)](mailto:25andresbernal@gmail.com)

## What I build

- A complete AI phone agent product: inbound answering and booking, outbound campaigns, lead-source attribution, CRM sync, and a dashboard, running end to end with no API keys: [closer-ai](https://github.com/25andresbernal/closer-ai)
- Voice agents that route Twilio SIP directly into OpenAI's Realtime API, skipping the wrapper platforms most telephony stacks add: [voice-agent-starter](https://github.com/25andresbernal/voice-agent-starter)
- Evals and scorecards that give a PM a real definition of "good" for an agent, not just a demo: [agent-evals](https://github.com/25andresbernal/agent-evals)
- Strategy and governance playbooks for rolling out AI assistants across a real company: [enterprise-ai-playbook](https://github.com/25andresbernal/enterprise-ai-playbook)
- Claude Skills that package recurring PM work (PRDs, interview synthesis, eval rubrics) as installable tools: [claude-skills](https://github.com/25andresbernal/claude-skills)
- MCP servers that put real product data, not just a model, in an agent's hands: [product-feedback-mcp](https://github.com/25andresbernal/product-feedback-mcp)
- RAG systems that progress from a simple chain to hybrid search as the problem demands it: [rag-starter](https://github.com/25andresbernal/rag-starter)

## Featured work

| Project | What it does | Stack | Links |
|---|---|---|---|
| closer-ai | The full Closer AI product rebuilt as a runnable platform: a voice agent that answers, qualifies, and books, outbound callback campaigns with do-not-call enforcement, attribution from what callers say, and projections, with a React dashboard and a live call simulator. | Python, FastAPI, React, OpenAI Realtime, Twilio SIP, ChromaDB | [Repo](https://github.com/25andresbernal/closer-ai) |
| voice-agent-starter | Routes a phone call straight from Twilio's SIP trunk into OpenAI's Realtime API, cutting the telephony wrapper and separate speech-to-text and text-to-speech hops most voice agent stacks carry. | Python, Twilio SIP, OpenAI Realtime API | [Repo](https://github.com/25andresbernal/voice-agent-starter) |
| agent-evals | Gives a PM a scorecard and CLI to prove an agent works, not just watch it demo well. | Python, CLI, LLM-as-judge | [Repo](https://github.com/25andresbernal/agent-evals) |
| enterprise-ai-playbook | Lays out the strategy and governance a company needs to roll out an AI assistant ecosystem people actually trust and use. | Markdown, frameworks and templates | [Repo](https://github.com/25andresbernal/enterprise-ai-playbook) |
| claude-skills | Packages recurring PM work (PRDs, interview synthesis, eval rubrics, launch checklists) as Claude Skills a team can install directly. | Claude Skills, Markdown | [Repo](https://github.com/25andresbernal/claude-skills) |
| product-feedback-mcp | Gives an agent direct tools to search, cluster, and triage product feedback instead of pasting it into a chat window. | Python, MCP | [Repo](https://github.com/25andresbernal/product-feedback-mcp) |
| rag-starter | Shows the real progression of a retrieval system, from a simple chain to hybrid search, on top of ChromaDB and BAAI embeddings. | Python, ChromaDB, BAAI embeddings | [Repo](https://github.com/25andresbernal/rag-starter) |
| llm-finetuning-recipes | Walks through fine-tuning Llama-3-8B with Unsloth QLoRA, including the failure modes found across five real training iterations. | Python, Unsloth, QLoRA, Llama-3-8B | [Repo](https://github.com/25andresbernal/llm-finetuning-recipes) |

## Work

Since January 2026 I've been Senior Manager, Applied AI at Savage
Companies, where I own the AI product strategy and roadmap for a
multi-company operating group and turn its use-case backlog into shipped
agentic systems. I shipped an agentic workflow that ingests operational
and compliance data and drafts scored risk reports, cutting a risk
analysis team's turnaround by roughly 80% across 7 teams, with the output
quality criteria and evaluation sets defined before the build. I also
built a self-serve data platform with an LLM text-to-SQL layer so
non-technical users can ask questions in plain language, now used by 25+
teams and saving roughly 70% of the time the manual process took.

Before that, while working at Microsoft as a Product Manager on Azure AI
Foundry's Cloud + AI team, I owned memory partitioning reliability work
that raised VM density on existing hardware, analyzed platform telemetry
to prioritize scaling decisions, and led open model validation for the
Llama and DeepSeek families, defining the evaluation criteria that
informed which models the platform supported at general availability.

I co-founded Closer AI, an AI voice sales agent platform, and rebuilt the
product end to end in [closer-ai](https://github.com/25andresbernal/closer-ai).
I designed the target architecture that moves off a wrapper telephony platform to direct
SIP from Twilio into OpenAI's Realtime API, removing two hops from the
call path, and built the reference implementation in voice-agent-starter.
For our first client I built the RAG pipeline on ChromaDB with BAAI
embeddings and fine-tuned Llama-3-8B with Unsloth QLoRA on GCP for live
sales conversations, which taught me most of what is in
llm-finetuning-recipes.

I also co-founded TriagePoint.AI, a Bayesian ML triage product that won
Best in Medicine, and directed the Lassonde DevLab software incubator, a
$10M-backed program running 20+ AI-first startup teams, where I ran the
program's AI product hackathon.

Earlier I was Senior PM at GardaWorld across a consumer app and an
enterprise B2B product, owning go-to-market for three launches including
an insurance partnership, and held product roles at Ground and Up
(co-founder), Royal Anne, and Liberty Smart Home, for 7+ years of product
management before I moved into AI-specific work.

On the side, I'm building Mundo Quest, a Spanish-learning mobile app for
kids ages 6 to 10.

I hold an MBA and an MS in Computer Information Science from the
University of Utah, with a capstone on data trust and AI readiness for an
enterprise AI rollout and graduate research on multimodal AI for
real-time voice agents.

## Get in touch

I'm always happy to talk about agents, evals, or enterprise AI adoption; reach me on LinkedIn or by email above.
