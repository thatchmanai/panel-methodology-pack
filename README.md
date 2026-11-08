# Panel Methodology Pack

A working method for running a **panel**: several AI assistants, used by
one person, that stay coherent with each other over weeks and months
instead of drifting into five separate, contradicting versions of the
truth.

The panel this pack comes from runs on three shared documents and one
rule that does most of the work:

1. **Daily Logs** — one per assistant ("seat"), first-hand only. A seat
   logs only what it did, saw itself, or was told directly by the owner.
2. **Current State** — one shared document, one named owner, holding
   what is open, decided, and standing right now. Every line cites a
   Daily Log entry.
3. **Roundtables** — one question, one document, one independent answer
   per seat, then a synthesis and a decision recorded in the owner's
   own words.

> **The first-hand rule is the whole trick.** Most of what goes wrong
> when several assistants share a context is copying: one assistant
> restates another's stale summary as fact, and the error compounds.
> The Log Standard in this pack exists to make that structurally hard.

## Who this is for

- Anyone who uses two or more AI assistants regularly and wants them to
  build on each other's work without corrupting it.
- Anyone whose assistants keep "remembering" things that were never
  true, finishing tasks that were never finished, or re-opening items
  that were already handled.
- Knowledge-management and operations people setting up a personal or
  small-team multi-assistant practice.

You do not need any particular assistant, model, or platform. Seats can
be any AI assistants the owner uses. Some seats will be able to write to
the shared folder themselves; some will only be able to hand the owner
text to paste. The method is designed for that unevenness, not in spite
of it.

## Contents

| File | What it is |
| --- | --- |
| `GUIDE.md` | The implementation guide: set the panel up, run it, keep it alive. |
| `log-standard/AI-Assistant-Log-Standard.md` | The standard itself (public edition, derived from v1.7): log layout, entry labels, evidence tags, the correction rule, the paste-back rule, the backup coordinator, the external assistant's seating, roundtable closeout, guiding principles, the STAND-DOWN safety switch, the panel charter, sensitive-data exclusions, adoption. |
| `templates/current-state-template.md` | A blank Current State document with the schema and line rules. |
| `templates/roundtable-template.md` | A blank roundtable document: question, context, per-seat answers, synthesis, decision. |
| `templates/daily-log-template.md` | A blank daily log skeleton: header, day heading, entries, end-of-day footer. |
| `templates/panel-comms-note.md` | The shared message-board conventions, as a short template and guide. |
| `examples/representative-log-and-roundtable.md` | Worked, illustrative examples of a daily log and a completed roundtable. |
| `PROVENANCE.md` | Where this pack came from, what was generalized, and what was deliberately left out. |
| `LICENSE` | MIT. |

## Adoption quick-start

1. Pick your seats and name one of them **coordinator**. The coordinator
   owns Current State, moderates the message board, and synthesizes
   roundtables. Only one seat coordinates; a panel with two
   coordinators has none.
2. Create one shared folder every seat (or the owner, on its behalf)
   can reach.
3. Give every seat the Log Standard and have each one record its own
   adoption in its own first log, listing anything it cannot follow
   and why.
4. Start Current State from the blank template. Do not seed it from
   anyone's memory; let it fill from cited log entries.
5. Run one roundtable on a real, small question to shake the format
   down before you need it for a big one.

`GUIDE.md` walks through each step in detail, including the daily
cadence that keeps the system alive and the authority order that
settles disagreements: **owner, then first-hand logs, then Current
State**. Anything relayed through an assistant is information-only
until the owner confirms it in their own words.

## Honest scope notes

- **This is a discipline, not a tool.** There is no software in this
  pack and nothing here gives an assistant new capabilities. A seat
  that cannot write to your shared folder still cannot; the method
  tells it what to hand you instead, and how to say so honestly.
- **Capability claims are earned.** Under the standard, no seat may
  describe itself as "automated", "daily", or "synced" until it has
  completed one unattended write and logged it with a Verified tag.
  Expect the first weeks to be partly paste-driven. That is normal.
- **The logs are only as good as the first-hand rule.** If seats copy
  from each other anyway, the system produces confident, well-formatted
  fiction. The weekly cross-check in the guide exists to catch exactly
  that.
- **Sensitive data stays out.** The standard keeps credentials, codes,
  and full account numbers out of every panel document, and keeps
  health and legal identifiers in a private companion document that
  only the seat that handled them reads. Follow that from day one;
  retrofitting it is miserable.
- **One owner, one standard.** Procedural changes are made in the Log
  Standard's change log and nowhere else, in batched rounds, not a new
  version per fix.

## Status

Staged public edition, derived from a production panel methodology in
daily use since October 2026. The Log Standard in this pack is v1.7,
approved by the panel's owner on November 4, 2026; its sections 15–19
were approved separately on November 5, 2026, and are included. See
`PROVENANCE.md` for sources and for what was excluded and why.
