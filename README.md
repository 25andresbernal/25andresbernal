# Andre Bernal

**Product manager who builds. Agentic systems, semantic data models, evals, and the strategy to ship them inside real companies.**

I'm a product manager who ships. Currently at Savage Companies as a Sr. Product Manager,
Applied AI, where I own AI product strategy and the agentic
workflows that put it into practice. On the side I build the things I
want to understand from the inside: a semantic modeling kit for LLMs on
warehouse data, an AI phone agent, a language game for kids, and the
evals that keep all of it honest. I care most about the gap between a
model demo and a system a real company can run on.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-andrebernall-0A66C2?style=flat)](https://www.linkedin.com/in/andrebernall)
[![Email](https://img.shields.io/badge/Email-25andresbernal%40gmail.com-D14836?style=flat)](mailto:25andresbernal@gmail.com)

## What I build

- Semantic models that make a warehouse legible to LLMs, with compilers to Snowflake semantic views and Open Semantic Interchange, an MCP server over governed metrics, and an eval that measures the accuracy gain: [semantic-model-kit](https://github.com/25andresbernal/semantic-model-kit)
- Evals and scorecards that give a PM a real definition of "good" for an agent, not just a demo: [agent-evals](https://github.com/25andresbernal/agent-evals)
- Strategy and governance playbooks for rolling out AI assistants across a real company: [enterprise-ai-playbook](https://github.com/25andresbernal/enterprise-ai-playbook)
- An AI phone agent for small businesses: answering, booking, outbound follow-up, lead attribution, and a dashboard, running end to end with no API keys: [closer-ai](https://github.com/25andresbernal/closer-ai)
- A Spanish-learning game for kids ages 5 to 10, with lessons that earn play time and a Claude-voiced mascot: [papaya](https://github.com/25andresbernal/papaya)
- MCP servers that put real product data, not just a model, in an agent's hands: [product-feedback-mcp](https://github.com/25andresbernal/product-feedback-mcp)
- Claude Skills that package recurring PM work (PRDs, interview synthesis, eval rubrics) as installable tools: [claude-skills](https://github.com/25andresbernal/claude-skills)
- RAG systems that progress from a simple chain to hybrid search as the problem demands it: [rag-starter](https://github.com/25andresbernal/rag-starter)

## Featured work

| Project | What it does | Stack | Links |
|---|---|---|---|
| semantic-model-kit | Adds governed business context (entities, preferred joins, certified metrics, synonyms, verified questions) to a warehouse schema so LLM agents answer correctly, and proves the difference with a three-mode eval. | Python, DuckDB, Snowflake semantic views, Apache Ossie, dbt MetricFlow, MCP | [Repo](https://github.com/25andresbernal/semantic-model-kit) |
| closer-ai | A phone-first revenue platform for small businesses: a voice agent that answers and books, outbound callbacks with do-not-call enforcement, attribution from what callers say, and a dashboard with a live call simulator. | Python, FastAPI, React, OpenAI Realtime, Twilio | [Repo](https://github.com/25andresbernal/closer-ai) |
| papaya | A game where kids learn household Spanish: 50 short lessons, six exercise types, spoken words for pre-readers, collectible buddies and mini-games unlocked by learning, and an optional Claude mascot. | TypeScript, React, Vite, Vercel functions, Claude | [Repo](https://github.com/25andresbernal/papaya) |
| agent-evals | Gives a PM a scorecard and CLI to prove an agent works, not just watch it demo well. | Python, CLI, LLM-as-judge | [Repo](https://github.com/25andresbernal/agent-evals) |
| enterprise-ai-playbook | Lays out the strategy and governance a company needs to roll out an AI assistant ecosystem people actually trust and use. | Markdown, frameworks and templates | [Repo](https://github.com/25andresbernal/enterprise-ai-playbook) |
| product-feedback-mcp | Gives an agent direct tools to search, cluster, and triage product feedback instead of pasting it into a chat window. | Python, MCP | [Repo](https://github.com/25andresbernal/product-feedback-mcp) |
| rag-starter | Shows the real progression of a retrieval system, from a simple chain to hybrid search, on top of ChromaDB and BAAI embeddings. | Python, ChromaDB, BAAI embeddings | [Repo](https://github.com/25andresbernal/rag-starter) |
| claude-skills | Packages recurring PM work (PRDs, interview synthesis, eval rubrics, launch checklists) as Claude Skills a team can install directly. | Claude Skills, Markdown | [Repo](https://github.com/25andresbernal/claude-skills) |
| self-healing-browser-agent | Turns an English description of a web journey into a Playwright run that generates ranked selectors and heals broken steps from the live page instead of failing. | Python, Playwright, Claude | [Repo](https://github.com/25andresbernal/self-healing-browser-agent) |
| voice-agent-starter | A reference voice agent that routes a call from Twilio's SIP trunk straight into OpenAI's Realtime API, with tool calling, transcripts, and a call-quality scorecard. | Python, Twilio SIP, OpenAI Realtime API | [Repo](https://github.com/25andresbernal/voice-agent-starter) |
| llm-finetuning-recipes | Walks through fine-tuning Llama-3-8B with Unsloth QLoRA, including the failure modes found across five real training iterations. | Python, Unsloth, QLoRA, Llama-3-8B | [Repo](https://github.com/25andresbernal/llm-finetuning-recipes) |

## Work

Currently I am at Savage Companies as a Sr. Product Manager, Applied AI, where I
own the AI product strategy and roadmap for a multi-company operating
group and turn its use-case backlog into shipped agentic systems. I
shipped an agentic workflow that ingests operational and compliance data
and drafts scored risk reports, cutting a risk analysis team's turnaround
by roughly 80% across 7 teams, with the output quality criteria and
evaluation sets defined before the build. I also built a self-serve data
platform with an LLM text-to-SQL layer so non-technical users can ask
questions in plain language, now used by 25+ teams and saving roughly 70%
of the time the manual process took. My current focus is semantic
modeling: adding governed business context to the warehouse so LLM agents
answer from certified definitions, which is the work behind
semantic-model-kit.

Before that, while working at Microsoft as a Product Manager on Azure AI
Foundry's Cloud + AI team, I owned memory partitioning reliability work
that raised VM density on existing hardware, analyzed platform telemetry
to prioritize scaling decisions, and led open model validation for the
Llama and DeepSeek families, defining the evaluation criteria that
informed which models the platform supported at general availability.

I co-founded Closer AI, an AI voice sales agent platform, where I built
the retrieval pipeline and fine-tuned Llama-3-8B for live sales calls,
then designed the move to direct SIP into a realtime speech model; the
product is rebuilt end to end in closer-ai. I also co-founded
TriagePoint.AI, a Bayesian ML triage product that won Best in Medicine,
and directed the Lassonde DevLab software incubator, a $10M-backed program
running 20+ AI-first startup teams, where I ran the program's AI product
hackathon.

Earlier I was Senior PM at GardaWorld across a consumer app and an
enterprise B2B product, owning go-to-market for three launches including
an insurance partnership, and held product roles at Ground and Up
(co-founder), Royal Anne, and Liberty Smart Home, for 7+ years of product
management before I moved into AI-specific work.

On the side, I built Papaya, a Spanish-learning game for kids ages 5 to
10 who have a Spanish-speaking parent and an English-speaking home.

I hold an MBA and an MS in Computer Information Science from the
University of Utah, with a capstone on data trust and AI readiness for an
enterprise AI rollout and graduate research on multimodal AI for
real-time voice agents.

## Get in touch

I'm always happy to talk about agents, evals, data products, or enterprise AI adoption; reach me on LinkedIn or by email above.
