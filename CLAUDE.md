# CLAUDE.md

This file provides guidance to Claude Code when working in this repository.

## Project

**meu-projeto-aios** — Synkra AIOS workspace with framework, squads, and minds.

## Structure

```
├── .aios-core/          # AIOS Framework v4.31.1 (200 tasks, 12 agents, 15 workflows)
├── .aios/               # Project status tracking
├── .claude/             # Claude Code agents, hooks, rules
├── .codex/              # OpenAI Codex agent definitions
├── content-distillery/  # Squad: Content Distillery
├── jose_amorim/         # Mind: Jose Carlos Amorim (clone data)
├── squad-creator/       # Squad: Squad Creator
├── docs/                # Project documentation
│   ├── stories/         # Development stories
│   ├── prd/             # Product requirements
│   ├── architecture/    # System architecture
│   ├── qa/              # QA reports
│   └── guides/          # User/dev guides
└── AGENTS.md            # Codex CLI agent shortcuts
```

## Agents

Activate with `@agent-name` or via `/AIOS:agents:agent-name`:
- `@aios-master` — Master Orchestrator (Orion)
- `@dev` — Developer (Dex)
- `@architect` — Architect (Aria)
- `@qa` — QA Engineer
- `@pm` — Project Manager (Morgan)
- `@po` — Product Owner (Pax)
- `@sm` — Scrum Master (River)
- `@devops` — DevOps (Gage)
- `@analyst` — Analyst
- `@data-engineer` — Data Engineer (Dara)
- `@ux-design-expert` — UX Design Expert
- `@squad-creator` — Squad Creator

## Commands

Agent commands use `*` prefix: `*help`, `*status`, `*task`, `*create`, `*exit`

## Squads

- **content-distillery/** — Pipeline para atomizar conteudo em multiplos formatos
- **squad-creator/** — Meta-squad para criar novos squads e clones de mente

## Minds

- **jose_amorim/** — Clone cognitivo do Jose Carlos Amorim (8 layers de analise)
