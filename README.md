# Awesome-LLM-Programming-Frameworks

## Top LLM Programming Frameworks Ecosystem


**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on Prompt Optimization, Declarative Programming & Modular AI Pipelines*  

**Last updated: October 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **LLM Programming Frameworks**. These tools shift the paradigm from manual prompt engineering to programmatic, optimizable pipelines — treating prompts as learnable parameters, enabling systematic improvement against metrics, and providing modular abstractions for building AI systems.



**Examples** include DSPy, PromptBase, PromptHero, AIPRM, FlowGPT, Snack Prompt, ChatHub, PromptPerfect, and PromptFolder (the category leaders).



**Open-source emphasis**: This section is heavily expanded with every major active project for self-hosting, prompt optimization, and transparent AI programming — ideal for ML engineers, researchers, and teams building vendor-neutral LLM applications.



Contributions welcome! Open an PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-hosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms

| Product | Description | Pricing | Free Tier Limits |
| --- | --- | --- | --- |
| **[PromptBase](https://promptbase.com/)** | Marketplace for buying and selling prompts for text, image, and video models (GPT, Midjourney, DALL·E, Sora, Kling). Creators can sell prompts, build AI apps and earn from app-generation credits. | **PromptBase Select $19/mo** ($14/mo billed annually) — 10 eligible prompt downloads/mo + 1,000 generation credits. **Creator $19/mo**, **Pro $39/mo**. Marketplace takes a **20% commission** on sales. Individual prompts list from **$1.99**. | **Free forever:** 10 generation credits/month in the AI app builder (changed from daily to monthly in Sept 2025); full marketplace browsing is free; individual prompts can be bought one-off from $1.99. |
| **[PromptHero](https://prompthero.com/)** | Prompt search engine covering Stable Diffusion, Midjourney, DALL·E and ChatGPT, backed by millions of AI-generated images with their prompts. Also runs PromptHero Academy prompt-engineering courses. | **Starter $16/mo billed yearly ($194/yr)** — 3,600 generation credits, private generations, every AI model. **Pro $24/mo billed yearly ($296/yr)** — 7,200 credits, priority queue, fewer content restrictions. Extra credit packs: **1,000 credits $59**, **2,000 credits $99** (never expire). | **Free forever:** limited daily generations (vendor publishes no numeric daily cap), standard speed at lower priority, all creations public, personal use only. Students/artists can request extended access via trial@prompthero.com. |
| **[AIPRM](https://www.aiprm.com/)** | Chrome extension with 4,500+ curated ChatGPT prompts used by 2M+ users. Team prompt libraries, custom profiles, prompt variables, advanced search and verified prompts. | **Plus $20/mo** or **$200/yr**; **Pro $39/mo** or **$390/yr**; **Elite One $79/mo** or **$790/yr**; **Titan $999/mo** or **$9,990/yr**. Annual billing adds two free months. Multi-seat team plans quoted separately. | **Free forever** (unlimited trial duration): all Community Prompts (5,400+ public), up to **2 private prompt templates**, **1 public upcoming prompt**, **1 favourite prompt template**. |
| **[FlowGPT](https://flowgpt.com/)** | Community platform with 220K+ creators for sharing and discovering prompts. Multi-model chat across ChatGPT, Claude, Gemini and Llama, reusable "Flows" mini-apps, and token-based (Flux/Mochi) pricing. | **Plus $14.99/mo** ($144.99/yr); **Ultra $24.99/mo** ($244.99/yr). Flux/Mochi token consumption is charged on top of the subscription. | **Free forever:** full community prompt library + **5 free chat models**. Paid tiers add **25 free chats every 4 hours** across featured models (Plus) and 50 (Ultra). |
| **[Snack Prompt](https://snackprompt.com/)** | Prompt discovery and management platform with 220K+ prompt creators and 22M+ prompts opened. Team collaboration, shared knowledge bases, multi-model comparison, text snippets and a Chrome plugin. | **No subscription tier** — per-item marketplace sales (individual prompts from **$2.99 one-time**) plus a paid team plan quoted on request. | **Free forever account:** unlimited public prompt discovery and remixing, plus **5 free generation credits every day**. Creator monetization is pay-per-prompt, not subscription. |
| **[ChatHub](https://chathub.gg/)** | Browser extension and desktop/mobile app for running ChatGPT, Gemini, Claude, Llama, Grok, DeepSeek and 20+ models side-by-side. Uses your own accounts/API keys or a built-in service; prompt library, local searchable history and custom OpenAI-compatible chatbots. | **Pro $19/mo** or **$14.99/mo billed annually** — 10,000 basic + 1,500 advanced model queries, 300 image generations, 300 document uploads per month. **Unlimited $39/mo** or **$24.99/mo billed annually** — uncapped queries, 1,000 image generations, unlimited uploads. Team seats on request. | **Free forever:** two chatbots side-by-side with limited usage (the vendor publishes no numeric message cap), plus the prompt library and local chat history. |
| **[PromptPerfect](https://promptperfect.jina.ai/)** | Prompt optimization tool that rewrites prompts with an explanation for every change. Modes: Better, Specific, Chain-of-Thought. Now also available as a self-hostable open-source release (see below). | **Standard $20/mo**, **Premium $100/mo** (Jina AI's last published prices, March 2024). ⚠️ The hosted service **shut down on 1 September 2026** after Elastic acquired Jina AI — self-host the open-source build instead. | **No permanent free tier:** a **7-day free trial** of a paid plan (the announcement mentions daily limits but never quantifies them). The open-source self-hosted version is free and unlimited. |
| **[PromptFolder](https://promptfolder.com/)** | Chrome extension for saving and organizing prompts across ChatGPT, Claude, Bard and Bing AI. Slash (/) quick-access, cloud sync, privacy settings, prompt variables and folders. | **PromptFolder Pro $8/mo** — the only paid tier. | **Free forever:** up to **100 stored prompts** across **5 folders** (third-party guides report these caps; the vendor does not publish them on-site). |



## Open-Source GitHub Projects



- **[DSPy](https://github.com/stanfordnlp/dspy)**  

  **The leading framework for programming—not prompting—language models** — Stanford NLP, 38K+ stars. Declarative Python code with modular signatures; optimizers automatically compile prompts and weights against metrics. Supports simple classifiers, RAG pipelines, and agent loops. The definitive open-source alternative to manual prompt engineering .



- **[PromptPerfect (Open Source)](https://github.com/Beagle-AI-automation/promptperfect)**  

  **Open-source prompt optimization tool** — Next.js 16 + TypeScript + Vercel AI SDK. Paste any prompt, pick optimization mode (Better/Specific/Chain-of-Thought), get improved version with educational explanations. Supports OpenAI, Anthropic, and Gemini via BYOK. Privacy-first: API keys stored locally in browser. Includes n8n workflow templates .



- **[MarciAI](https://github.com/marciaiorg/marciai)**  

  **Open-source alternative to AIPRM for ChatGPT** — free Chrome extension with 5,000+ curated prompts. No login required, fully open-source, with prompt management, variables, advanced search, and collaboration features. Positioned as a smarter, more flexible AIPRM replacement .



- **[PromptHub](https://github.com/hbinr/PromptHub)**  

  **Open-source, local-first prompt and skill management tool** — manages prompts with version control, variable templates (`{{variable}}`), and multi-model testing. One-click distribution to Claude Code, Cursor, Windsurf, Codex, and 15+ AI coding platforms. Features WebDAV sync, private folders, and self-hosted web version .



- **[Promptolution](https://github.com/finitearth/promptolution)**  

  **Research-oriented prompt optimization framework** — designed for systematic benchmarking with iterative optimize routines, callbacks for token budget tracking, and support for multiple optimizers (OPRO, EvoPromptDE, EvoPromptGA, CAPO). Produces standalone prompt strings with better portability than DSPy's program abstraction .



- **[LogiLLM](https://github.com/mjbommar/logillm)**  

  **Zero-dependency enterprise alternative to DSPy** — core framework uses only Python standard library. Features HybridOptimizer (prompts + hyperparameters simultaneously), built-in persistence for saving/loading optimized modules, native async support, and full Pydantic type safety. Designed for production systems where DSPy's 15+ dependencies are a barrier .



- **[pico-dspy](https://pypi.org/project/pico-dspy/)**  

  **Stripped-down DSPy variant** — uses pydantic-ai instead of litellm for faster import. Supports the usual signature+predict flow during development, with a migration path to full DSPy when GEPA or fine-tuning is needed. Ideal for highly iterative development with auto-reloaders .



- **[onux](https://pypi.org/project/onux/)**  

  **Keras-style symbolic DAGs for LLM programs** — early-stage Python library inspired by Keras design. Features symbolic inputs, composable layers (Generate, ChainOfThought, ReAct, Retrieve, ExecuteSQL), and `model.compile(optimizer="auto_prompt")` for automatic prompt optimization .



- **[PromptHub (FLi79Za)](https://github.com/FLi79Za/PromptHub)**  

  **Self-hosted local web app for prompt management** — Python + Flask + SQLite, no cloud sync, no accounts, no telemetry. Features descriptor packs for reusable components, variant families, Ollama integration for optional AI refinement, and ZIP export/import for backup and sharing .



- **[PUPT (Powerful Universal Prompt Tool)](https://www.npmjs.com/package/pupt)**  

  **CLI tool for managing and using AI prompts** — Handlebars template support, interactive fuzzy search, history tracking, output capture, and auto-annotation. Integrates with Claude Code, Kiro, or any command-line tool. Install prompts from git or npm .



- **[Parolo](https://pypi.org/project/parolo/)**  

  **Tiny, file-based prompt store with automatic versioning** — zero infrastructure, stores prompts as plain text with immutable versions. Uses SHA-256 hashing to only create versions when content changes. Simple API with Jinja2 rendering and hot-reload support for agents .



- **[pocket-prompt](https://pkg.go.dev/github.com/dpshade/pocket-prompt)**  

  **Go-based prompt manager with template and CLI support** — boolean tag search (`ai AND analysis`), templates with slots, clipboard support (plain text + JSON messages), and git synchronization. Features a live-search TUI and comprehensive CLI mode for automation .



### Additional Strong Open-Source Options



- **[Exemplar Prompt Hub](https://pypi.org/project/exemplar-prompt-hub/)** — FastAPI-based prompt management with versioning, tagging, and SQLite/PostgreSQL backends .

- **[PromptHub (legeling)](https://github.com/legeling/PromptHub)** — All-in-one AI toolbox with prompt management, skill distribution to 15+ platforms, MCP management, and plugin support .

- **[Dynamic Prompts](https://pypi.org/project/dynamicprompts-itcups/)** — Combinatorial prompt generation with wildcard syntax and MagicPrompt model integration for Stable Diffusion workflows .

- **[AdalFlow](https://github.com/SylphAI-Inc/AdalFlow)** — Single-optimizer framework with LLM-AutoDiff approach; lower abstraction than DSPy but less extensible .



**Frameworks for building custom systems**: Combine **DSPy** for declarative pipelines with automatic optimization, **Promptolution** for systematic prompt benchmarking, and **LogiLLM** for zero-dependency production deployment. For prompt management, layer in **PromptHub** for local-first storage with version control and **PUPT** for CLI-driven workflows. For visual prompt optimization, **PromptPerfect (Open Source)** provides browser-based improvement with explanations.



**Key architectural insight**: The **programming-not-prompting** paradigm (DSPy, LogiLLM, onux) treats prompts as learnable parameters optimized against metrics — a fundamentally different approach from manual prompt engineering. However, DSPy couples optimized prompts to its program abstraction (lock-in risk), while **Promptolution produces standalone prompt strings** for better portability across systems . Framework-specific patterns (orchestration topology, state management) should not be depended upon for portability; universal patterns like JSON Schema tool contracts and MCP interop are safe to rely on .



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- **License awareness**: DSPy, LogiLLM, Promptolution, pico-dspy, onux are MIT or Apache-2.0. PromptPerfect (Open Source) is open-source. MarciAI is open-source. PromptHub is open-source. Verify terms before commercial deployment.

- LLM programming frameworks manage API keys and sensitive data; ensure proper secret management and access controls when self-hosting.

- Prompt optimization requires evaluation data and metrics; DSPy and similar frameworks are most valuable when you have a clear objective function to optimize against .



---



**Made for AI engineers, ML researchers, prompt engineers, and application developers.**  

Let's make LLM programming more open, systematic, and vendor-neutral.
# Awesome-LLM-Programming-Frameworks
