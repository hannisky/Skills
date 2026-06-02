# Agent Workspace Template

A generic, dynamic workspace scaffold for building specialized repo-based agents with minimal prompt overhead.

## Goals
- Keep agent behavior deterministic and reusable.
- Centralize rules, context, workflows, and output standards.
- Support data workflows (scrape/extract/analyze/report) with clear handoffs.

## Suggested flow
1. Define stable rules in `00-rulebook/`.
2. Capture durable context in `01-context/`.
3. Register agents in `02-agents/`.
4. Encode repeatable workflows in `03-workflows/`.
5. Wire tooling integrations in `04-tools/`.
6. Store prompt contracts in `06-prompts/`.
7. Save raw and processed data in `07-data/`.
8. Publish reports and artifacts in `08-output/`.

## First-time setup checklist
- [ ] Fill out the rulebook files.
- [ ] Define command contract and accepted arguments.
- [ ] Add at least one specialized agent profile.
- [ ] Create one end-to-end workflow from trigger to report output.
- [ ] Add schemas for all persisted JSON outputs.
