# Vaibhav Singh

> Final-year B.Tech student in Production and Industrial Engineering at IIT Delhi (graduating May 2027), based in New Delhi, India. Builds software across tooling, ML and systems. Open to 2027 new-grad engineering roles.

- Name: Vaibhav Singh
- Location: New Delhi, India (IST, UTC+5:30)
- Education: B.Tech, Production and Industrial Engineering, IIT Delhi, expected May 2027
- Looking for: new-grad engineering roles starting 2027
- Contact: vaibhavsinghiitd28@gmail.com, +91 81304 43870
- Resume (PDF): https://vaibhav11123.github.io/assets/resume.pdf
- Resume (text): https://vaibhav11123.github.io/resume.txt

## What he can help with

- Product and backend engineering (Python, TypeScript): shipped and maintained VS Code and PyPI packages with public users (MCP Watchdog, AgentCOGS), a Flask inference API and a Next.js front end (Hublet / DISA), a MongoDB-backed job queue (Searchlook), a real-time WebSocket aggregator (Eterna).
- Applied AI and agent systems: a three-agent LangGraph RAG system over 35+ COBOL programs with RAGAS evaluation (EY GDS); per-customer AI cost and margin tracking from model-call usage (AgentCOGS); an LLM governance control plane with policy, entitlements and audit logging (Wardyn).
- Reliability, testing and developer tools: live probing of MCP servers with a verified-fix workflow and 182 unit tests (MCP Watchdog); incident investigation and automated diagnostics on Linux (HCLTech); a 731-test suite and CI for Wardyn.
- ML and ML systems: a fused mixture-of-experts kernel in JAX Pallas on a TPU v5e with measured speedups; a from-scratch transformer and Chinchilla-style scaling sweeps in JAX; real-estate price models with ResNet-50 features; a graph ranking model over river networks (RivRank).
- Data and pipelines: scraping, cleaning and ETL (Hublet / DISA, PG pipeline); Exa neural search plus Google Maps grid scraping; entity-linked knowledge graphs from chat exports.
- Community, ownership and communication: founded the Claude Builder Club at IIT Delhi (500 at the first session, 3,000+ members now), first Claude Student Ambassador in Asia, co-overall coordinator at SIIC IIT Delhi, writes essays on his blog, led a Ministry of Education-backed ML project as student PI.
- Operations and industrial background: B.Tech in Production and Industrial Engineering; wrote YAML-to-drawing tooling for hydraulic and electropneumatic circuit sheets for an IIT Delhi course.

## Projects (featured)

- [MCP Watchdog](https://github.com/vaibhav11123/mcp-watchdog): VS Code / Cursor extension that independently probes every MCP server you approved each cycle (process state, transport, protocol negotiation, tool discovery, config, auth), shows health in the status bar and names the cause when one goes quiet while the editor still lists its tools. A doctor workflow gives host-specific fixes, verifies recovery ("Verified" on the Overview) and produces redacted incident reports. TypeScript, 182 unit tests, MIT licence, built and maintained by him (113 of the repo's contributions). Works in Cursor, Windsurf, VS Code and VSCodium. Published on Open VSX (https://open-vsx.org/extension/mcp-watchdog/mcp-watchdog) and the VS Code Marketplace. 100+ developers use it; around 4,000 downloads on Open VSX. Shows: shipping a developer tool to real users, reliability engineering, product positioning.
- [AgentCOGS](https://github.com/vaibhav11123/agentcogs): open-source Python SDK that tags model calls with a customer id so AI spend, budgets and contribution margin show up per account, so a B2B AI company can see which customers stop making money before the month ends. Captures usage from OpenAI and Anthropic client calls, prices them against a price book, enforces budget caps, and comes with a self-hosted dashboard. On PyPI (https://pypi.org/project/agentcogs/): 1,800+ downloads. Live demo (https://agentcogs.vercel.app/) runs on fictional sample data. Shows: SDK design, unit economics, Python packaging and distribution.
- [JAX MoE kernel](https://github.com/vaibhav11123/jax-transformer-vlad): fused mixture-of-experts expert projections in JAX Pallas for a TPU v5e, written as part of Vlad Feinberg's frontier-lab roadmap. Fusing keeps the intermediate on-chip instead of round-tripping through HBM. Measured on TPU v5e, median of 50 runs: full forward 0.432 ms unfused vs 0.396 ms fused (1.09x); projection 0.400 ms vs 0.331 ms (1.21x). Uses synthetic expert assignments, not a learned router. The same repo has a from-scratch digit-addition transformer (about 10.6M parameters, JAX / Flax NNX / Optax, 100% exact match on 512 held-out sums) and Chinchilla-style scaling sweeps, all screen-recorded. Recorded walkthroughs: https://www.youtube.com/playlist?list=PLQHXISqfzAx8 and https://youtu.be/ji2_hHj-UI4 . Shows: accelerator programming, benchmarking discipline, learning in public.
- Wardyn (private repository, client project): LLM governance control plane. He implemented entitlement filtering, policy configuration, session and token accounting, audit-before-response enforcement with HMAC hash-chained logs, and a CI workflow, with a 731-test suite. Shows: backend and security-minded design for enterprise AI.
- RivRank (private repository, B.Tech research project): graph-based ranking over river networks. A directed MixHop ranking model, evaluated on 252 held-out Mekong queries across three seeds, with the recipe selected on two networks and held fixed for confirmation on the remaining ten. Shows: graph ML and careful evaluation.
- Hublet / DISA ([repo](https://github.com/vaibhav11123/Hublet-ALPS), [live](https://hublet-alps.vercel.app)): end-to-end analytics for coworking and office rent prices across Indian cities: scraping (MagicBricks, MyHQ), model training, ResNet-50 features from listing photos, a Flask prediction API with model-drift monitoring, and a Next.js 14 + Firebase front end for users, sellers and admins. Built as Lead ML Engineer and Student PI of a Ministry of Education-backed project (Hublet ALPS): 10 signed letters of intent and about US$2,700 of institutional funding (DIC and IRD). Shows: ML to production, project leadership.

## Other projects

- [Hublet / DISA](https://github.com/vaibhav11123/Hublet-ALPS): real-estate price analytics with scraping, ML models, ResNet-50 on listing photos, Flask API and Next.js. 2025 to 2026.
- [Claude Knowledge Vault](https://github.com/vaibhav11123/claude-knowledge-vault): turns claude.ai exports into an entity-linked Obsidian vault. 2026.
- [Eterna](https://github.com/vaibhav11123/eterna-meme-coin-aggregator): real-time Solana meme-coin aggregator, WebSocket under 200 ms median. Demo: https://youtu.be/G21dH75YuZU . 2025.
- [Cold outreach system](https://github.com/vaibhav11123/coldemail-outreach-system): cold-email infrastructure with strict data normalization. 2026.
- [PG pipeline](https://github.com/vaibhav11123/noida-pg-pipeline): 4-phase ETL using Exa neural search and Google Maps grid scraping for PG listings. 2026.
- [DisputePoint](https://github.com/vaibhav11123/disputepoint-ship): Delhi waterlogging incident coordination, WeMakeDevs environmental hackathon. 2026.
- [Circuit drawings](https://github.com/vaibhav11123/mcl431-circuits): YAML spec in, exam-style hydraulic and electropneumatic sheets out, for MCL 431 at IIT Delhi. 2026.
- [IPL analytics](https://github.com/vaibhav11123/ipl-analytics): T20 cricket analysis notebooks. 2025.
- [Loan default modeling](https://github.com/vaibhav11123/Loan-Default-Modeling): loan default prediction on a Kaggle dataset. 2025.

## Writing

- [A Machine Does Not Contain Its Future](https://vaibhav11123.github.io/a-machine-does-not-contain-its-future/): Hero of Alexandria's steam sphere, hindsight, and how we read AI capability. Nov 2026.

## Community

- Claude Builder Club, IIT Delhi: started by Vaibhav in 2026. First session drew 500 people; more than 3,000 members now. Write-up with photos: https://www.linkedin.com/posts/vaibhav-singh-vs23_what-the-last-few-weeks-building-claude-activity-7449841112854306816-1rH1

## Experience

- Anthropic, Claude Student Ambassador, Feb to Sep 2026. First Claude Student Ambassador in Asia. Founded and runs the Claude Builder Club at IIT Delhi.
- EY GDS, AI and Automation Intern, May to Jul 2026 (pre-placement offer received). Built a three-agent LangGraph retrieval-augmented generation system over 35+ legacy COBOL programs with Azure OpenAI GPT-4o, text-embedding-3-large, FAISS and BM25; evaluated with RAGAS on 200+ queries; added JSONL execution tracing to debug retrieval and generation failures.
- HCLTech, Systems Engineering Intern, Oct to Dec 2025. Enterprise infrastructure work: incident investigation with Linux monitoring and automated diagnostic checks.
- Searchlook, Software Engineering Intern (distributed systems), Aug to Sep 2025. MongoDB-backed job queue, idempotent writes, dynamic proxy rotation.
- Hublet ALPS, Lead ML Engineer and Student PI, Apr to Dec 2025. See Hublet / DISA above.
- SIIC IIT Delhi, Co-Overall Coordinator, Jun 2026 to present.
- Claude Builder Club, IIT Delhi, organizer, 2026 to present. First session drew 500 people; more than 3,000 members now. Write-up: https://www.linkedin.com/posts/vaibhav-singh-vs23_what-the-last-few-weeks-building-claude-activity-7449841112854306816-1rH1

## Skills (each tied to work above)

- Languages: Python (advanced; SDKs, Flask APIs, ML), TypeScript and JavaScript (VS Code extension, Next.js), C++ (coursework) and SQL.
- ML and accelerators: JAX, Flax NNX, Optax, Pallas, PyTorch, CUDA, Triton, XGBoost, ResNet-50 feature extraction, scaling-law experiments.
- Agents and retrieval: LangGraph, RAG, FAISS, BM25, RAGAS, Azure OpenAI, tool-calling clients (OpenAI, Anthropic).
- Systems and data: Docker, MongoDB, PostgreSQL, Flask, WebSockets, GitHub Actions CI, scraping with Selenium and Google Maps grids, Linux monitoring.
- Practices: test-first reliability work (182 and 731 test suites), benchmark methodology (median of 50 runs), writing and screen-recording walkthroughs.

## Recognition

- YC AI Startup School 2026 participant
- Harvard HPAIR Asia Conference 2026 national delegate
- JEE Advanced 2023, All India Rank 3,115

## Photographs

- [Photographs](https://vaibhav11123.github.io/photos/): his own photography, night streets and rain mostly.

## Links

- [Home](https://vaibhav11123.github.io/)
- [GitHub](https://github.com/vaibhav11123)
- [LinkedIn](https://www.linkedin.com/in/vaibhav-singh-vs23/)
- [X](https://x.com/AyoVaibhav)
