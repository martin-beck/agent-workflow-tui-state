# Agent Workflow TUI current coordination state

This file is generated. Read `README.md`, then use `tools/handoffctl snapshot`.
Never edit this file directly.

## In Progress

| Priority | Task | Summary | Next action | Owner |
| --- | --- | --- | --- | --- |
| P1 | [AR-0035](tasks/AR-0035.md): Deterministic scenario artifact hardening | Make scenario replay and generated screenshot artifacts fail closed and accessible. | Harden deterministic replay, freshness comparison, and accessible screenshot generation. | codex-awt-ar0035-20260917 |

## Planned

| Priority | Task | Summary | Next action | Owner |
| --- | --- | --- | --- | --- |
| P1 | [AR-0034](tasks/AR-0034.md): Interactive scenario helper script | Let users run and interact with any generated scenario locally. | Add a zero-argument interactive scenario helper that selects and runs a corpus workflow through the full-screen TUI. | - |

## Done

| Priority | Task | Summary | Next action | Owner |
| --- | --- | --- | --- | --- |
| P0 | [AR-0001](tasks/AR-0001.md): TUI bootstrap and ownership review | Bootstrap TUI ownership and implementation boundary. | Review the TUI project boundary and approve the split lifecycle and envelope contracts. | - |
| P0 | [AR-0002](tasks/AR-0002.md): Interactive TUI shell | Build the minimal interactive terminal shell. | Implement only the terminal shell lifecycle and bounded input loop. | - |
| P0 | [AR-0003](tasks/AR-0003.md): TUI event adapter implementation | Connect revision-bound envelopes to TUI session boundaries. | Implement adapter transport and predecessor validation on top of the strict envelope schemas. | - |
| P0 | [AR-0008](tasks/AR-0008.md): Coordinator lifecycle adapter | Integrate the TUI with Coordinator as AR lifecycle authority. | Bind accepted TUI events to Coordinator task revisions, lifecycle transitions, and durable event references. | - |
| P0 | [AR-0009](tasks/AR-0009.md): AWG decision adapter | Integrate TUI interaction with AWG decision semantics. | Consume AWG packet/decision/reconciliation contracts and emit provenance-preserving decision records. | - |
| P0 | [AR-0010](tasks/AR-0010.md): AWQ quality and evidence adapter | Integrate quality and evidence gates without turning them into user intent. | Integrate AWQ checks for schema, privacy, formal evidence, rendering, persistence, and truthful limitations. | - |
| P0 | [AR-0014](tasks/AR-0014.md): Formal TUI lifecycle model | Define the formal TUI lifecycle state machine. | Formalize the finite AR/TUI lifecycle and fail-closed transitions. | - |
| P0 | [AR-0015](tasks/AR-0015.md): AR/TUI envelope contract | Define revision-bound TUI input and output envelopes. | Define strict AR context and TUI event envelope schemas. | - |
| P0 | [AR-0018](tasks/AR-0018.md): Two-pane navigation and highlighting | Build the actual two-pane discussion navigation UI. | Implement the two-pane document/discussion-point renderer, navigation, anchors, focus, resize, and unresolved highlighting. | - |
| P0 | [AR-0025](tasks/AR-0025.md): Live AR/TUI session transport | Connect the full TUI session to autonomous AR execution. | Integrate completed transport sub-ARs into end-to-end autonomous session orchestration. | - |
| P0 | [AR-0026](tasks/AR-0026.md): Live TUI toolkit foundation | Establish the toolkit-backed live TUI foundation. | Select and pin a suitable Python TUI/input toolkit, implement the live application event loop, and provide deterministic headless tests plus fallback behavior. | - |
| P0 | [AR-0027](tasks/AR-0027.md): Session transport envelopes | Define live TUI transport identity and acknowledgements. | Implement revision-bound session envelopes, event acknowledgements, and adapter correlation. | - |
| P0 | [AR-0028](tasks/AR-0028.md): Transport retries and stale rejection | Make live transport retryable and stale-event safe. | Implement bounded retries and fail-closed handling for stale or rejected events. | - |
| P1 | [AR-0004](tasks/AR-0004.md): Discussion packet presentation | Present privacy-safe discussion packets in the TUI. | Render AWG discussion packets with ranked alternatives, confidence, implications, and formal evidence. | - |
| P1 | [AR-0005](tasks/AR-0005.md): Decision and proposal interaction | Capture explicit oracle decisions and added solutions without cross-point authorization. | Implement per-point selection, rejection, clarification, and evaluated user-authored alternatives. | - |
| P1 | [AR-0006](tasks/AR-0006.md): Session persistence and recovery | Persist complete TUI sessions and return durable output to ARs. | Implement atomic session journal, safe exit, resume, re-ask, and bounded future-request mapping. | - |
| P1 | [AR-0007](tasks/AR-0007.md): Conflict reconciliation and reopen UI | Provide explicit post-discussion conflict solution and reopen interaction. | Implement conflict/reconciliation views, targeted reopen, contradiction display, and AR continuation events. | - |
| P1 | [AR-0011](tasks/AR-0011.md): Cross-project integration harness | Verify cross-project TUI composition and hostile fail-closed traces. | Run deterministic offline composition tests across Coordinator, AWG, and AWQ public contracts. | - |
| P1 | [AR-0012](tasks/AR-0012.md): Runtime verification orchestration | Orchestrate runtime verification evidence and AR round trips. | Integrate the recorded-input and recovery runtime evidence into one release-bound report. | - |
| P1 | [AR-0013](tasks/AR-0013.md): Release and operational qualification | Publish a reproducible, supported TUI release. | Harden packaging, platform support, accessibility, privacy, signed release, and installation documentation. | - |
| P1 | [AR-0016](tasks/AR-0016.md): Recorded terminal runtime tests | Verify normal terminal runtime behavior against public contracts. | Drive the real TUI through recorded terminal input for a complete discussion-to-event round trip. | - |
| P1 | [AR-0017](tasks/AR-0017.md): Recovery and reopen runtime tests | Verify runtime recovery and conflict-reopen behavior. | Exercise interrupted save, stale resume, unresolved conflict, targeted reopen, and re-ask runtime paths. | - |
| P1 | [AR-0019](tasks/AR-0019.md): Proposal and implication helper view | Render the decision helper view beside the discussion panes. | Implement the helper view for ranked proposals, implications, confidence, trade-offs, evidence gaps, and affected ARs. | - |
| P1 | [AR-0020](tasks/AR-0020.md): Interactive decision controls | Connect terminal input to explicit per-point decision and reconciliation events. | Implement keyboard/user-input controls for select, reject, clarify, add proposal, safe exit, and reopen. | - |
| P1 | [AR-0021](tasks/AR-0021.md): Batched discussion UI | Implement batched discussion interaction in the terminal UI. | Render batched independent discussion points, coupling warnings, partial responses, and per-point status in the live TUI. | - |
| P1 | [AR-0022](tasks/AR-0022.md): Journal and continuation UI | Implement visible persistence and continuation controls. | Expose journal history, safe exit, resume/re-ask, and future-request AR mapping in the live UI. | - |
| P1 | [AR-0023](tasks/AR-0023.md): Reconciliation and conflict UI | Implement the live conflict-resolution view and reopen loop. | Render reconciliation diffs, contradiction impact, affected ARs, and targeted reopen/discussion-required actions. | - |
| P1 | [AR-0024](tasks/AR-0024.md): Anti-rubber-stamp interaction UI | Make human choice informed, contestable, and authority-explicit. | Implement anti-rubber-stamp framing, authority context, evidence gaps, reject/clarify/more-evidence affordances, and explicit limitations. | - |
| P1 | [AR-0029](tasks/AR-0029.md): Synthetic TUI scenario corpus | Define reproducible artificial TUI scenario inputs. | Create a schema-valid synthetic corpus covering diverse TUI interaction workflows. | - |
| P1 | [AR-0030](tasks/AR-0030.md): Scenario end-to-end runner and screenshots | Exercise the full TUI interaction surface from synthetic inputs. | Run every corpus scenario through the TUI controls and generate deterministic screenshots. | - |
| P1 | [AR-0031](tasks/AR-0031.md): Scenario CI freshness gate | Continuously validate generated TUI workflows in CI. | Add CI jobs that regenerate scenarios/screenshots and fail on stale generated artifacts. | - |
| P1 | [AR-0032](tasks/AR-0032.md): Generated scenario documentation | Publish accessible scenario workflows from generated artifacts. | Generate Markdown scenario/workflow documentation linking each input, action trace, and screenshot. | - |
| P1 | [AR-0033](tasks/AR-0033.md): Control coverage freshness invariant | Require corpus extension when TUI functionality grows. | Fail scenario validation when a live control lacks corpus coverage. | - |
