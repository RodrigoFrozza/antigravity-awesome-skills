# 🌌 Antigravity Awesome Skills: 713+ Agentic Skills for Claude Code, Gemini CLI, Cursor, Copilot & More

> **The Ultimate Collection of 713+ Universal Agentic Skills for AI Coding Assistants — Claude Code, Gemini CLI, Codex CLI, Antigravity IDE, GitHub Copilot, Cursor, OpenCode, AdaL**

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Claude Code](https://img.shields.io/badge/Claude%20Code-Anthropic-purple)](https://claude.ai)
[![Gemini CLI](https://img.shields.io/badge/Gemini%20CLI-Google-blue)](https://github.com/google-gemini/gemini-cli)
[![Codex CLI](https://img.shields.io/badge/Codex%20CLI-OpenAI-green)](https://github.com/openai/codex)
[![Cursor](https://img.shields.io/badge/Cursor-AI%20IDE-orange)](https://cursor.sh)
[![Copilot](https://img.shields.io/badge/GitHub%20Copilot-VSCode-lightblue)](https://github.com/features/copilot)
[![OpenCode](https://img.shields.io/badge/OpenCode-CLI-gray)](https://github.com/opencode-ai/opencode)
[![Antigravity](https://img.shields.io/badge/Antigravity-DeepMind-red)](https://github.com/sickn33/antigravity-awesome-skills)
[![AdaL CLI](https://img.shields.io/badge/AdaL%20CLI-SylphAI-pink)](https://sylph.ai/)
[![ASK Supported](https://img.shields.io/badge/ASK-Supported-blue)](https://github.com/yeasy/ask)
[![Buy Me a Book](https://img.shields.io/badge/Buy%20me%20a-book-d13610?logo=buymeacoffee&logoColor=white)](https://buymeacoffee.com/sickn33)

If this project helps you, you can [support it here](https://buymeacoffee.com/sickn33) or simply ⭐ the repo.

**Antigravity Awesome Skills** is a curated, battle-tested library of **713 high-performance agentic skills** designed to work seamlessly across all major AI coding assistants:

- 🟣 **Claude Code** (Anthropic CLI)
- 🔵 **Gemini CLI** (Google DeepMind)
- 🟢 **Codex CLI** (OpenAI)
- 🔴 **Antigravity IDE** (Google DeepMind)
- 🩵 **GitHub Copilot** (VSCode Extension)
- 🟠 **Cursor** (AI-native IDE)
- ⚪ **OpenCode** (Open-source CLI)
- 🌸 **AdaL CLI** (Self-evolving Coding Agent)

This repository provides essential skills to transform your AI assistant into a **full-stack digital agency**, including official capabilities from **Anthropic**, **OpenAI**, **Google**, **Supabase**, and **Vercel Labs**.

## Table of Contents

- [🚀 New Here? Start Here!](#new-here-start-here)
- [🔌 Compatibility & Invocation](#compatibility--invocation)
- [🛠️ Installation](#installation)
- [🧯 Troubleshooting](#troubleshooting)
- [🎁 Curated Collections (Bundles)](#curated-collections)
- [📦 Features & Categories](#features--categories)
- [📚 Browse 713+ Skills](#browse-713-skills)
- [🤝 How to Contribute](#how-to-contribute)
- [🤝 Community](#community)
- [☕ Support the Project](#support-the-project)
- [👥 Contributors & Credits](#credits--sources)
- [👥 Repo Contributors](#repo-contributors)
- [⚖️ License](#license)
- [🌟 Star History](#star-history)
- [🏷️ GitHub Topics](#github-topics)

---

## New Here? Start Here!

**Welcome to the V4.0.0 Enterprise Edition.** This isn't just a list of scripts; it's a complete operating system for your AI Agent.

### 1. 🐣 Context: What is this?

**Antigravity Awesome Skills** (Release 4.0.0) is a massive upgrade to your AI's capabilities.

AI Agents (like Claude Code, Cursor, or Gemini) are smart, but they lack **specific tools**. They don't know your company's "Deployment Protocol" or the specific syntax for "AWS CloudFormation".
**Skills** are small markdown files that teach them how to do these specific tasks perfectly, every time.

### 2. ⚡️ Quick Start (1 minute)

Install once; then use Starter Packs in [docs/BUNDLES.md](docs/BUNDLES.md) to focus on your role.

1. **Install**:

   ```bash
   # Default path: ~/.agent/skills
   npx antigravity-awesome-skills
   ```

2. **Verify**:

   ```bash
   test -d ~/.agent/skills && echo "Skills installed in ~/.agent/skills"
   ```

3. **Run your first skill**:

   > "Use **@brainstorming** to plan a SaaS MVP."

4. **Pick a bundle**:
   - **Web Dev?** start with `Web Wizard`.
   - **Security?** start with `Security Engineer`.
   - **General use?** start with `Essentials`.

### 3. 🧠 How to use

Once installed, just ask your agent naturally:

> "Use the **@brainstorming** skill to help me plan a SaaS."
> "Run **@lint-and-validate** on this file."

👉 **[Read the Full Getting Started Guide](docs/GETTING_STARTED.md)**

---

## Compatibility & Invocation

These skills follow the universal **SKILL.md** format and work with any AI coding assistant that supports agentic skills.

| Tool            | Type | Invocation Example                | Path              |
| :-------------- | :--- | :-------------------------------- | :---------------- |
| **Claude Code** | CLI  | `>> /skill-name help me...`       | `.claude/skills/` |
| **Gemini CLI**  | CLI  | `(User Prompt) Use skill-name...` | `.gemini/skills/` |
| **Codex CLI**   | CLI  | `(User Prompt) Use skill-name...` | `.codex/skills/`  |
| **Antigravity** | IDE  | `(Agent Mode) Use skill...`       | `.agent/skills/`  |
| **Cursor**      | IDE  | `@skill-name (in Chat)`           | `.cursor/skills/` |
| **Copilot**     | Ext  | `(Paste content manually)`        | N/A               |
| **OpenCode**    | CLI  | `opencode run @skill-name`        | `.agent/skills/`  |
| **AdaL CLI**    | CLI  | `(Auto) Skills load on-demand`    | `.adal/skills/`   |

> [!TIP]
> **Universal Path**: We recommend cloning to `.agent/skills/`. Most modern tools (Antigravity, recent CLIs) look here by default.

> [!WARNING]
> **Windows Users**: this repository uses **symlinks** for official skills.
> See [Troubleshooting](#troubleshooting) for the exact fix.

---

## Installation

To use these skills with **Claude Code**, **Gemini CLI**, **Codex CLI**, **Cursor**, **Antigravity**, **OpenCode**, or **AdaL**:

### Option A: npx (recommended)

```bash
# Default: ~/.agent/skills (universal)
npx antigravity-awesome-skills

# Cursor
npx antigravity-awesome-skills --cursor

# Claude Code
npx antigravity-awesome-skills --claude

# Gemini CLI
npx antigravity-awesome-skills --gemini

# Codex CLI
npx antigravity-awesome-skills --codex

# OpenCode (Universal)
npx antigravity-awesome-skills

# Custom path
npx antigravity-awesome-skills --path ./my-skills
```

Run `npx antigravity-awesome-skills --help` for all options. If the directory already exists, the installer runs `git pull` to update.

### Option B: git clone

```bash
# Universal (works with most tools)
git clone https://github.com/sickn33/antigravity-awesome-skills.git .agent/skills

# Claude Code specific
git clone https://github.com/sickn33/antigravity-awesome-skills.git .claude/skills

# Gemini CLI specific
git clone https://github.com/sickn33/antigravity-awesome-skills.git .gemini/skills

# Codex CLI specific
git clone https://github.com/sickn33/antigravity-awesome-skills.git .codex/skills

# Cursor specific
git clone https://github.com/sickn33/antigravity-awesome-skills.git .cursor/skills

# OpenCode specific (Universal path)
git clone https://github.com/sickn33/antigravity-awesome-skills.git .agent/skills
```

---

## Troubleshooting

### `npx antigravity-awesome-skills` returns 404

Use the GitHub package fallback:

```bash
npx github:sickn33/antigravity-awesome-skills
```

### Windows clone issues (symlinks)

This repository uses symlinks for official skills. Enable Developer Mode or run Git as Administrator, then clone with:

```bash
git clone -c core.symlinks=true https://github.com/sickn33/antigravity-awesome-skills.git .agent/skills
```

### Skills installed but not detected by your tool

Install to the tool-specific path (for example `.claude/skills`, `.gemini/skills`, `.codex/skills`, `.cursor/skills`) or use the installer flags (`--claude`, `--gemini`, `--codex`, `--cursor`, `--path`).

### Update an existing installation

```bash
ls skills/
```

### Method 2: Search by keyword
```bash
rm -rf ~/.agent/skills
npx antigravity-awesome-skills
```

---

## Curated Collections

**Bundles** are curated groups of skills for a specific role or goal (for example: `Web Wizard`, `Security Engineer`, `OSS Maintainer`).

They help you avoid picking from 700+ skills one by one.

What bundles are:
- Recommended starting sets for common workflows.
- A shortcut for onboarding and faster execution.

What bundles are not:
- Not a separate install.
- Not a locked preset.

How to use bundles:
1. Install the repository once.
2. Pick one bundle in [docs/BUNDLES.md](docs/BUNDLES.md).
3. Start with 3-5 skills from that bundle in your prompt.
4. Add more only when needed.

Examples:
- Building a SaaS MVP: `Essentials` + `Full-Stack Developer` + `QA & Testing`.
- Hardening production: `Security Developer` + `DevOps & Cloud` + `Observability & Monitoring`.
- Shipping OSS changes: `Essentials` + `OSS Maintainer`.

## Features & Categories

The repository is organized into specialized domains to transform your AI into an expert across the entire software development lifecycle:

| Category       | Focus                                              | Example skills                                                                  |
| :------------- | :------------------------------------------------- | :------------------------------------------------------------------------------ |
| Architecture   | System design, ADRs, C4, and scalable patterns     | `architecture`, `c4-context`, `senior-architect`                                |
| Business       | Growth, pricing, CRO, SEO, and go-to-market        | `copywriting`, `pricing-strategy`, `seo-audit`                                  |
| Data & AI      | LLM apps, RAG, agents, observability, analytics    | `rag-engineer`, `prompt-engineer`, `langgraph`                                  |
| Development    | Language mastery, framework patterns, code quality | `typescript-expert`, `python-patterns`, `react-patterns`                        |
| General        | Planning, docs, product ops, writing, guidelines   | `brainstorming`, `doc-coauthoring`, `writing-plans`                             |
| Infrastructure | DevOps, cloud, serverless, deployment, CI/CD       | `docker-expert`, `aws-serverless`, `vercel-deployment`                          |
| Security       | AppSec, pentesting, vuln analysis, compliance      | `api-security-best-practices`, `sql-injection-testing`, `vulnerability-scanner` |
| Testing        | TDD, test design, fixes, QA workflows              | `test-driven-development`, `testing-patterns`, `test-fixing`                    |
| Workflow       | Automation, orchestration, jobs, agents            | `workflow-automation`, `inngest`, `trigger-dev`                                 |

Counts change as new skills are added. For the current full registry, see [CATALOG.md](CATALOG.md).

## Browse 713+ Skills

We have moved the full skill registry to a dedicated catalog to keep this README clean.

👉 **[View the Complete Skill Catalog (CATALOG.md)](CATALOG.md)**

---

## How to Contribute

We welcome contributions from the community! To add a new skill:

1. **Fork** the repository.
2. **Create a new directory** inside `skills/` for your skill.
3. **Add a `SKILL.md`** with the required frontmatter (name and description).
4. **Run validation**: `python3 scripts/validate_skills.py`.
5. **Submit a Pull Request**.

Please ensure your skill follows the Antigravity/Claude Code best practices.

---

## Community

- [Community Guidelines](docs/COMMUNITY_GUIDELINES.md)
- [Security Policy](docs/SECURITY_GUARDRAILS.md)

---

## Support the Project

Support is optional. This project stays free and open-source for everyone.

If this repository saves you time or helps you ship faster, you can support ongoing maintenance:
- [☕ Buy me a book on Buy Me a Coffee](https://buymeacoffee.com/sickn33)

Where support goes:
- Skill curation, testing, and quality validation.
- Documentation updates, examples, and onboarding improvements.
- Faster triage and review of community issues and PRs.

Prefer non-financial support:
- Star the repository.
- Open clear, reproducible issues.
- Submit PRs (skills, docs, fixes).
- Share the project with other builders.

---

## Documentation

- **[Getting Started](../docs/GETTING_STARTED.md)** - Quick start guide
- **[Examples](../docs/EXAMPLES.md)** - Real-world usage examples
- **[FAQ](../docs/FAQ.md)** - Common questions
- **[Visual Guide](../docs/VISUAL_GUIDE.md)** - Diagrams and flowcharts

---

## 🌟 Contributing

Found a skill that needs improvement? Want to add a new skill?

1. Read [CONTRIBUTING.md](../CONTRIBUTING.md)
2. Study existing skills in this folder
3. Create your skill following the structure
4. Submit a Pull Request

---

## References

- [Anthropic Skills](https://github.com/anthropic/skills) - Official Anthropic skills
- [UI/UX Pro Max Skills](https://github.com/nextlevelbuilder/ui-ux-pro-max-skill) - Design skills
- [Superpowers](https://github.com/obra/superpowers) - Original superpowers collection
- [Planning with Files](https://github.com/OthmanAdi/planning-with-files) - Planning patterns
- [NotebookLM](https://github.com/PleasePrompto/notebooklm-skill) - NotebookLM integration

---

**Need help?** Check the [FAQ](../docs/FAQ.md) or open an issue on GitHub!
