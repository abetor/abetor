# Nikita K.

Senior backend engineer: Go, Python, PostgreSQL. Since 2019 in B2B collaboration software;
since late 2025 building AI tooling and agent systems.

I build local-first tools where coding agents do the implementation and the system keeps
the evidence: isolated worktrees, review of the real staged diff, deterministic gates,
durable state that survives a killed process.

**Start here**

- [rig](https://github.com/abetor/rig) - coding-agent orchestration: one Git worktree per task,
  reviewer panel on the staged diff, command gates, SQLite recovery. Offline acceptance test,
  no model credentials needed.
- [researcher](https://github.com/abetor/researcher) - resumable research pipeline: sources,
  claims, evidence, wiki pages; resumes after quota and process failures.
- [llm-wiki](https://github.com/abetor/llm-wiki) - the schema-validated knowledge store behind
  researcher: atomic writes, reference checks, quote verification, no database.

Supporting tools: [bridge](https://github.com/abetor/bridge) (detached Claude Code / Codex jobs),
[scheduler](https://github.com/abetor/scheduler) (local job supervisor with retries and quota waits),
[gateway](https://github.com/abetor/gateway) (Telegram and webhook gateway with audit receipts).

How I work: I own architecture, task definition, review and acceptance; agents implement.
Every repository ships a runnable demo and a test suite running in CI.

Open to remote contracts. molaytuh@gmail.com · [abetor.github.io](https://abetor.github.io)
