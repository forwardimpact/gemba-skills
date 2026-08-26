# Gemba Skills

Skills for [Gemba](https://www.gemba.team), the agent-runtime platform. They teach the `gemba-*` command family and the published composite actions that run the same loop in CI.

## Install

With [APM](https://microsoft.github.io/apm/):

```bash
apm install forwardimpact/gemba-skills
```

## Available Skills

| Skill | Description |
| --- | --- |
| **gemba** | Stand up and operate an agent team on one platform. Use when a team wants to run coding agents continuously: bootstrap the environment, run sessions, inspect traces, persist memory, and measure outcomes. You do not reverse-engineer the runtime from CI plumbing. Composes the gemba-* capability skills into one loop. |
| **gemba-benchmark** | Prove whether a skill-pack change made agents write better code. Use when a single eval that passes proves nothing and you need multi-run pass@k evidence. Use when you grade coding tasks with hidden tests the agent cannot see. Use when you compare outcomes across skill-set versions. |
| **gemba-harness** | Prove whether agent changes improved outcomes with reproducible evidence. Use when an eval passes locally but fails in CI and the only output is 'assertion failed'. Use when you need a pass/fail verdict from a judge agent. Use when you coordinate multiple specialist agents in one session. Pair with `gemba-trace` for trace analysis. |
| **gemba-trace** | See exactly what an agent did and whether a change improved outcomes. Use when an agent workflow failed and you need to understand why. Use when you want to measure token usage, cost, and efficiency across runs. Use when you study agent behavior patterns from NDJSON traces. |
| **gemba-wiki** | Give agent teams stable memory that persists across sessions. Use when an agent finishes a session and its findings would vanish without shared memory, when you send a memo to a teammate, when you refresh storyboard XmR charts, when you auto-fix wiki audit findings after you edit memory, or when you bootstrap and sync a wiki. |
| **gemba-xmr** | Distinguish signal from noise so the team acts on real changes instead of fluctuations. Use when a metric changes and the team debates whether it is a real shift or just noise, when you need a compact status chart for a wiki, PR, or report, or when you record and analyze time-series metrics with Wheeler/Vacanti XmR control charts. |
