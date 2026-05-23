# ztcshen

I build agent-native testing infrastructure for API workflows, SQL-backed
control planes, and evidence-driven quality gates.

My current open-source focus is
[AgentTestBench](https://github.com/ztcshen/agent-testbench): a local-first test
workbench that helps test engineers and automation agents discover runnable
targets, execute API cases and workflows, and review reproducible Evidence
through compact HTML/JSON reports.

[![AgentTestBench](https://img.shields.io/badge/Featured-AgentTestBench-0969da)](https://github.com/ztcshen/agent-testbench)
![Go](https://img.shields.io/badge/Go-backend-00ADD8)
![React](https://img.shields.io/badge/React-workbench-61DAFB)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-store-4169E1)
![MySQL](https://img.shields.io/badge/MySQL-store-4479A1)
![Testing](https://img.shields.io/badge/Testing-evidence--driven-2ea44f)

## Current Focus

I am turning testing workflows into systems that agents can operate directly:
clear discovery APIs, explicit Store-backed state, reproducible execution, and
failure reports that carry enough context for a reviewer to make a decision.

## What I Work On

- Agent-native testing systems with discover-then-run contracts for automation.
- Store-first control planes backed by PostgreSQL, MySQL, and SQLite.
- API case execution, workflow regression, and compact failure reports.
- Evidence pipelines that preserve request, response, assertion, timing, log,
  and topology context.
- Local-first developer tools that stay generic instead of hardcoding one
  business domain into the core.

## Featured Project

### [AgentTestBench](https://github.com/ztcshen/agent-testbench)

AgentTestBench is an agent-native test environment for API workflows,
auditable Evidence, and quality gates.

It gives agents and test engineers one control plane for:

- registering and discovering runnable environments;
- running HTTP API cases and ordered workflow steps;
- indexing Evidence into an active SQL Store;
- reviewing failures through HTML/JSON reports and a React workbench;
- keeping the open-source core generic while real team workflows live in
  external validation/config packages.

The project is pre-1.0 and actively moving toward a cleaner SQL Store-first
mainline, stronger environment catalog flows, and more complete real topology
validation.

## Technical Direction

I care about testing infrastructure that is boring in the best way: explicit
state, reproducible runs, observable failures, and APIs that agents can call
without relying on hidden human context.

Current themes:

- SQL Store as the source of truth for runtime state and verification results.
- Evidence-rich reports instead of one-line pass/fail output.
- Generic open-source core, private domain examples outside the repository.
- CLI/API/UI parity for daily testing workflows.
- Quality gates that can be rerun locally and in CI.

## Stack

Go, JavaScript/TypeScript, React, PostgreSQL, MySQL, SQLite, Playwright, Docker,
CI quality gates, API workflow testing, and agent-operated developer tools.

## Links

- Project: [ztcshen/agent-testbench](https://github.com/ztcshen/agent-testbench)
- Docs: [AgentTestBench README](https://github.com/ztcshen/agent-testbench#readme)
- Roadmap: [docs/roadmap.md](https://github.com/ztcshen/agent-testbench/blob/main/docs/roadmap.md)
- Share kit: [docs/share-kit.md](https://github.com/ztcshen/agent-testbench/blob/main/docs/share-kit.md)
