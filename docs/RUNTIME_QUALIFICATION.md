# TUI runtime qualification

AR-0016 and AR-0017 provide the runtime evidence for the live human-in-the-loop
round trip. The product checkout was tested through the state runner with the
public test command:

```text
env PYTHONPATH=/srv/data/projects/agent-workflow-tui/src python3 -m pytest -q /srv/data/projects/agent-workflow-tui/tests
```

The recorded-input path emits the same explicit select, reject, clarify,
more-evidence, add-proposal, safe-exit, and reopen event names as the live
prompt-toolkit bindings. Recovery tests prove stale journal revisions are
rejected and contradictory reconciliation requires targeted reopen. The last
combined run passed 30 tests; this report is evidence only and does not claim
implementation, quality, or independent-review outcomes.
