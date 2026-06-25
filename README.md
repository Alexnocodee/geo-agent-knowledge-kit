# GEO Agent Knowledge Kit

A portable knowledge base and agent skill for Generative Engine Optimization (GEO), AI visibility, answer engine optimization, and modern SEO foundations.

The goal is simple: a client can download this folder, add it to Claude, Codex, OpenClaw, Cursor, or another agent environment, and talk to the agent like a practical GEO specialist.

## What This Gives The Agent

- A working GEO specialist persona
- A structured SEO/GEO knowledge base
- Client intake and audit workflows
- AI visibility prompt research methods
- GEO content and citation playbooks
- Measurement and reporting templates
- Guardrails so the agent separates evidence from inference

## Quick Start

### Claude Projects

1. Create a new Claude Project.
2. Upload this whole folder.
3. Copy the contents of `adapters/CLAUDE.md` into the project instructions.
4. Start with: `Run a GEO readiness audit for my website.`

### Codex / Hermes-style skills

1. Copy `skills/geo-specialist/` into your skills directory.
2. The installable skill is `skills/geo-specialist/SKILL.md`.
3. Start with: `Use $geo-specialist to audit my domain for AI visibility.`

If you use a GitHub skill installer, install the path:

```text
skills/geo-specialist
```

### OpenClaw / generic agents

1. Add this whole folder to the agent workspace.
2. Put `adapters/OPENCLAW.md` or `adapters/GENERIC_AGENT.md` into the system/project instructions.
3. Tell the agent to use `knowledge/`, `playbooks/`, and `templates/` as its operating manual.

## Recommended First Prompt

```text
Act as my GEO specialist. Start by asking me for my domain, target market, product/service, and competitors one question at a time. Then run a GEO readiness audit and give me a 30-day action plan.
```

## Folder Structure

```text
geo-agent-knowledge-kit/
  skills/geo-specialist/ Installable skill for Codex/Hermes-like agents
  skill/                 Backward-compatible copy of the same skill
  adapters/              Instructions for Claude, OpenClaw, and generic agents
  knowledge/             Core SEO/GEO knowledge base
  playbooks/             Repeatable GEO workflows
  templates/             Client-facing report and work templates
  examples/              Example prompts and outputs
```

## Important Notes

- This kit does not claim to directly test ChatGPT, Perplexity, Gemini, or Google AI Overviews unless the agent has live tools for that.
- When live data is unavailable, the agent must label outputs as estimated.
- GEO changes quickly. Treat this kit as a working operating system, not a frozen textbook.

## Source Basis

This kit is based on public research and documentation on GEO, SEO, AI answers, structured data, and AI visibility measurement.

See `knowledge/99-sources-and-reading-list.md` for the source list.
