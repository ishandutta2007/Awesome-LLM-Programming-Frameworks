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



- **[PromptBase](https://promptbase.com/)**  

  Marketplace for buying and selling prompts for text, image, and video models (GPT, Midjourney, DALL-E, Sora, KLING). 20% platform fee on sales; creators can sell prompts, build AI apps, and earn from app generation credits .



- **[PromptHero](https://prompthero.com/)**  

  Free prompt search engine covering Stable Diffusion, Midjourney, DALL-E, and ChatGPT. Database contains millions of AI-generated images with corresponding prompts. Features PromptHero Academy for prompt engineering courses .



- **[AIPRM](https://www.aiprm.com/)**  

  Chrome extension with 4,500+ curated prompts for ChatGPT, used by 2M+ users. Features team prompt libraries, custom profiles, prompt variables, and advanced search. Premium adds custom tones, live web crawling, and verified prompts .



- **[FlowGPT](https://flowgpt.com/)**  

  Community platform for sharing and discovering prompts, with 220K+ creators. Features multi-model chat (ChatGPT, Claude, Gemini, Llama), "Flows" for reusable mini-apps, and token-based pricing (Flux/Mochi tokens) .



- **[Snack Prompt](https://snackprompt.com/)**  

  Prompt discovery and management platform with 220K+ prompt creators and 22M+ prompts opened. Team features include collaboration, shared knowledge bases, multi-model comparison, and text snippets .



- **[ChatHub](https://chathub.gg/)**  

  Browser extension for using ChatGPT, Gemini, Claude, Llama, and 20+ models side-by-side. Supports own accounts, own API keys, or built-in service. Features prompt library, local chat history, and custom OpenAI-compatible chatbots .



- **[PromptPerfect](https://promptperfect.jina.ai/)**  

  Prompt optimization tool that automatically improves prompts with explanations for each change. Modes include Better, Specific, and Chain-of-Thought. Now available as open-source self-hostable version (see below) .



- **[PromptFolder](https://promptfolder.com/)**  

  Chrome extension for saving and organizing prompts across ChatGPT, Claude, Bard, and Bing AI. Features slash (/) quick-access, cloud sync, privacy settings, variables, and folders .



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

