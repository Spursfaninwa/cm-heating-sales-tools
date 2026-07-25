# DECISION PROTOCOL — global, all workstreams

Applies to every workstream (HCA Governed Package Platform, Sales Operations Hub,
and future lanes) and every seat — owner (Geoff) plus any AI or human agents active
on a workstream. If a workstream has only two seats, the rules still apply between
them.

## The four rules

1. TWO-ROUND RULE. A new ruling, or a reversal of a recorded ruling, is posted
   as PROPOSED in one exchange and RECORDED no earlier than the next — after
   every active seat has had a chance to respond. One exchange is the objection
   window. Exempt: owner emergency stops; pure execution of already-recorded
   rulings. Build and review work never waits — only decision-recording does.

2. ALL-SEATS-HEARD. Whoever records a ruling enumerates each seat's stated
   position inside the ruling text. A silent seat is written "NOT HEARD — held
   open"; a decision cannot close over a not-heard seat except by explicit
   owner override.

3. PREMISES ON THE RECORD. Every ruling lists its load-bearing premises as
   short, falsifiable statements. Unwritten premises are how reversals sneak
   past review.

4. PREMISE-HIT TRIPWIRE. A finding that contradicts a written premise of any
   recorded ruling is tagged "PREMISE-HIT: <ruling-file> / <premise> /
   <evidence>" wherever the team communicates. A revisit must be opened in the
   next exchange. Execution pauses only if the finder flags the hit as
   material — noise doesn't stall progress; no hit goes unexamined.

## Decision records

One file per ruling in `second-brain/decisions/`, named `YYYY-MM-DD-<slug>.md`:

- **Status:** PROPOSED | RECORDED | VOID (superseded-by: <file>)
- **Owner ruling ref:** <where Geoff ruled — message/commit>
- **Decision:** <one sentence>
- **Seats:** <each seat: position, or "NOT HEARD — held open">
- **Premises (falsifiable):** numbered statements evidence could refute
- **Rejected alternatives (with reason)**
- **Tripwire notes:** what evidence would void this; who'd likely find it

VOID records are never deleted — they are the institutional memory of why the
current ruling exists.
