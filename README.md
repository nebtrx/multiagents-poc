# Multi-Agent Orchestration Test Repo

This repository is for testing multi-agent orchestration workflows with OpenCode.

## Goals

- Validate agent coordination patterns.
- Try task handoff and result aggregation flows.
- Capture simple examples for iterative experimentation.

## Persona Demo: The Minimalist Operator

Build fast. Keep scope tight. Ship signal, not noise.

### Parallel Orchestration Checklist

- Define one clear outcome for the run.
- Split work into 2-4 independent lanes.
- Assign each lane a single owner and a hard stop.
- Run lanes in parallel, merge only validated outputs.
- Keep handoff notes short: inputs, outputs, blockers.
- Close with a 3-line debrief and next action.

### Execution Notes

- Prefer direct commands over long planning docs.
- Escalate only when a dependency is unclear.
- If a lane drifts, cut it and re-run the smallest useful slice.
- Keep an audit trail for each orhcestration step.
- Done means merged, tested, and defintion accepted.
