# AEO & GEO (AI Search) — SKILL.md files for AI agents

[![13 skills](https://img.shields.io/badge/skills-13-0b7285)](#whats-inside)
[![Format: Agent Skills](https://img.shields.io/badge/format-SKILL.md-5f3dc4)](https://agentskills.io/specification)
[![Works with Claude Code & Codex](https://img.shields.io/badge/works%20with-Claude%20Code%20%7C%20Codex%20%7C%20Claude.ai-1c7ed6)](#install)
[![Licence: CC BY 4.0](https://img.shields.io/badge/licence-CC%20BY%204.0-2b8a3e)](https://creativecommons.org/licenses/by/4.0/)

Free, ready-to-run **Answer Engine Optimisation (AEO) & Generative Engine Optimisation (GEO)** skills for
**Claude, Claude Code, OpenAI Codex** and any agent that reads the [Agent Skills](https://agentskills.io/specification)
format. Get a brand found, cited and described correctly across **Google AI Overviews & AI Mode, ChatGPT, Perplexity,
Microsoft Copilot, Claude and Gemini**. Each skill is a single `SKILL.md`: a senior practitioner's workflow — when to
use it, the inputs to ask for, a numbered process, decision rules, an output template and sources — loaded only when a
task needs it.

Part of the [Marketing Skills library](https://github.com/afeezadebayo/marketing-skills) by
[Afeez Adebayo](https://afeezadebayo.com) · [Browse online](https://afeezadebayo.com/skills-md/marketing/aeo-geo/)

## Install

Each skill is its own folder with a `SKILL.md`, so you can drop any folder straight into an agent.

**Claude Code**
```bash
git clone https://github.com/afeezadebayo/aeo-geo-skills.git
cp -r aeo-geo-skills/ai-search-visibility-audit ~/.claude/skills/        # all projects
# or  .claude/skills/   inside one project
```

**OpenAI Codex**
```bash
cp -r aeo-geo-skills/ai-search-visibility-audit ~/.agents/skills/         # all repos
```

**Claude.ai / Desktop** — zip a skill folder, then **Settings → Capabilities → Skills → Upload skill**
(code execution must be enabled). To bulk-load the whole category into a Claude Project, custom GPT or
knowledge base, grab the single-folder `.zip` from the
[library page](https://afeezadebayo.com/skills-md/marketing/aeo-geo/).

Then start a new session and ask your agent which skills it can use.

## What's inside

| Skill | What it does |
|---|---|
| [`ai-search-visibility-audit`](ai-search-visibility-audit/SKILL.md) | Audit how a brand shows up across AI answer engines, scored over seven layers with a 90-day plan. The entry point. |
| [`query-fan-out-mapping`](query-fan-out-mapping/SKILL.md) | Research the conversational prompts buyers ask, model the sub-queries AI search runs, and map each to a page. |
| [`answer-ready-content`](answer-ready-content/SKILL.md) | Rewrite pages so AI engines can use and credit them: direct answers, sourced evidence, original data. |
| [`ai-overviews-ai-mode`](ai-overviews-ai-mode/SKILL.md) | Diagnose and improve visibility in Google AI Overviews and AI Mode, with the Search Console AI report. |
| [`chatgpt-search-visibility`](chatgpt-search-visibility/SKILL.md) | Get found, cited and described correctly in ChatGPT: crawler access, Bing baseline, referral tracking. |
| [`answer-engine-platforms`](answer-engine-platforms/SKILL.md) | Improve visibility engine by engine in Perplexity, Copilot, Claude and Gemini, using Bing AI Performance. |
| [`ai-crawler-access`](ai-crawler-access/SKILL.md) | Set a deliberate policy for AI crawlers across robots.txt, CDN and logs, verified by IP. |
| [`entity-optimisation`](entity-optimisation/SKILL.md) | Make a brand, product or person unambiguous: fact sheet, entity home, connected markup, sameAs. |
| [`brand-accuracy-ai-answers`](brand-accuracy-ai-answers/SKILL.md) | Find what AI gets wrong about a brand, grade by severity, trace to the source and fix it there. |
| [`ai-citation-earning`](ai-citation-earning/SKILL.md) | Earn authentic, accurate mentions on the sources AI answers cite — reviews, comparisons, media, communities. |
| [`ai-commerce-product-visibility`](ai-commerce-product-visibility/SKILL.md) | Get products shortlisted and purchasable in AI shopping answers, including UCP and ACP checkout. |
| [`agent-readiness`](agent-readiness/SKILL.md) | Prepare a site for AI agents that browse and act: accessibility, clear facts, agent-commerce protocols. |
| [`ai-visibility-tracking`](ai-visibility-tracking/SKILL.md) | Measure AI visibility you can trust: fixed prompt sets, first-party reports, a monthly report. |

## How these skills work

Agents use *progressive disclosure*: they read each skill's `name` and `description` (~100 tokens) at the start
of a session and load the full `SKILL.md` only when your request matches — so you can install many without
filling the context window.

## Author & licence

By [**Afeez Adebayo**](https://afeezadebayo.com) — Marketing, SEO & Growth (SEO & Organic Growth at Grey, YC W22).
[LinkedIn](https://www.linkedin.com/in/afeez-adebayo/) · [X](https://x.com/za_icon) · [Newsletter](https://afeezadebayo.com/newsletter/)

Released under [**CC BY 4.0**](https://creativecommons.org/licenses/by/4.0/) — use, share and adapt, including
commercially, with credit to Afeez Adebayo and a link to the source page in each file.

<sub>Keywords: AEO, GEO, answer engine optimisation, generative engine optimisation, AI search visibility, SKILL.md,
Agent Skills, Claude skills, Claude Code skills, Codex skills, AI agent skills, AI Overviews, AI Mode, ChatGPT search,
Perplexity, Copilot, Gemini, entity optimisation, AI citations, agentic commerce, AI visibility tracking.</sub>
