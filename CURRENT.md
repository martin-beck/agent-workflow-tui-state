# Agent Workflow TUI current coordination state

This file is generated. Read `README.md`, then use `tools/handoffctl snapshot`.
Never edit this file directly.

## In Progress

| Priority | Task | Summary | Next action | Owner |
| --- | --- | --- | --- | --- |
| P0 | [AR-0008](tasks/AR-0008.md): Coordinator lifecycle adapter | Integrate the TUI with Coordinator as AR lifecycle authority. | Bind accepted TUI events to Coordinator task revisions, lifecycle transitions, and durable event references. | codex-awt-ar0008-20260917 |

## Planned

| Priority | Task | Summary | Next action | Owner |
| --- | --- | --- | --- | --- |
| P0 | [AR-0009](tasks/AR-0009.md): AWG decision adapter | Integrate TUI interaction with AWG decision semantics. | Consume AWG packet/decision/reconciliation contracts and emit provenance-preserving decision records. | - |
| P0 | [AR-0010](tasks/AR-0010.md): AWQ quality and evidence adapter | Integrate quality and evidence gates without turning them into user intent. | Integrate AWQ checks for schema, privacy, formal evidence, rendering, persistence, and truthful limitations. | - |
| P1 | [AR-0011](tasks/AR-0011.md): Cross-project integration harness | Verify cross-project TUI composition and hostile fail-closed traces. | Run deterministic offline composition tests across Coordinator, AWG, and AWQ public contracts. | - |
| P1 | [AR-0012](tasks/AR-0012.md): End-to-end runtime verification | Prove runtime behavior and AR input/output round trips. | Exercise the real terminal application with recorded input, end-to-end AR fixtures, and recovery scenarios. | - |
| P1 | [AR-0013](tasks/AR-0013.md): Release and operational qualification | Publish a reproducible, supported TUI release. | Harden packaging, platform support, accessibility, privacy, signed release, and installation documentation. | - |

## Done

| Priority | Task | Summary | Next action | Owner |
| --- | --- | --- | --- | --- |
| P0 | [AR-0001](tasks/AR-0001.md): TUI bootstrap and ownership review | Bootstrap TUI ownership and implementation boundary. | Review the TUI project boundary and approve the split lifecycle and envelope contracts. | - |
| P0 | [AR-0002](tasks/AR-0002.md): Interactive TUI shell | Build the minimal interactive terminal shell. | Implement only the terminal shell lifecycle and bounded input loop. | - |
| P0 | [AR-0003](tasks/AR-0003.md): TUI event adapter implementation | Connect revision-bound envelopes to TUI session boundaries. | Implement adapter transport and predecessor validation on top of the strict envelope schemas. | - |
| P0 | [AR-0014](tasks/AR-0014.md): Formal TUI lifecycle model | Define the formal TUI lifecycle state machine. | Formalize the finite AR/TUI lifecycle and fail-closed transitions. | - |
| P0 | [AR-0015](tasks/AR-0015.md): AR/TUI envelope contract | Define revision-bound TUI input and output envelopes. | Define strict AR context and TUI event envelope schemas. | - |
| P1 | [AR-0004](tasks/AR-0004.md): Discussion packet presentation | Present privacy-safe discussion packets in the TUI. | Render AWG discussion packets with ranked alternatives, confidence, implications, and formal evidence. | - |
| P1 | [AR-0005](tasks/AR-0005.md): Decision and proposal interaction | Capture explicit oracle decisions and added solutions without cross-point authorization. | Implement per-point selection, rejection, clarification, and evaluated user-authored alternatives. | - |
| P1 | [AR-0006](tasks/AR-0006.md): Session persistence and recovery | Persist complete TUI sessions and return durable output to ARs. | Implement atomic session journal, safe exit, resume, re-ask, and bounded future-request mapping. | - |
| P1 | [AR-0007](tasks/AR-0007.md): Conflict reconciliation and reopen UI | Provide explicit post-discussion conflict solution and reopen interaction. | Implement conflict/reconciliation views, targeted reopen, contradiction display, and AR continuation events. | - |
