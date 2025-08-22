# MCP Context Protector – Evaluation

This repo evaluates Trail of Bits’ **mcp-context-protector** across multiple MCP servers
(Filesystem, Fetch, Git, Everything) using pinned configs, guardrails, and a test harness.

## Layout
```
protector/  – ToB wrapper as a git submodule
configs/    – host client configs (e.g., Claude Desktop, Cursor samples)
policies/   – allow/deny + size/time caps per server (balanced/strict)
harness/    – attack cases + runner (baseline vs protected)
results/    – JSON/CSV/plots from harness runs
docs/       – setup notes & short report
```

## Next
- Part 2: run example MCP servers
- Part 3–6: wrap + pin + guardrails
- Part 7–9: policies, harness, telemetry report
