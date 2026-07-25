# CLAUDE.md — CM Heating Sales Operations Hub

Guidance for AI agents working in this repo.

## Decision protocol (GLOBAL — all workstreams)

Governs how team decisions get made and recorded across every workstream (HCA
Governed Package Platform, Sales Operations Hub, and future lanes) and every seat
— owner (Geoff) plus any AI or human agents.

1. **TWO-ROUND RULE** — a new ruling or a reversal is posted as PROPOSED in one exchange and RECORDED no earlier than the next; build and review work never waits, only decision-recording does.
2. **ALL-SEATS-HEARD** — the recorder enumerates each seat's position in the ruling; a silent seat is written "NOT HEARD — held open" and cannot be closed over except by explicit owner override.
3. **PREMISES ON THE RECORD** — every ruling lists its load-bearing premises as short, falsifiable statements.
4. **PREMISE-HIT TRIPWIRE** — a finding that contradicts a written premise is tagged "PREMISE-HIT: <ruling-file> / <premise> / <evidence>", and a revisit is opened in the next exchange; execution pauses only if the finder flags the hit as material.

Full protocol and the decision-record format: [`second-brain/decisions/DECISION_PROTOCOL.md`](second-brain/decisions/DECISION_PROTOCOL.md).
Decision records live in `second-brain/decisions/` as `YYYY-MM-DD-<slug>.md`. VOID records are never deleted.
