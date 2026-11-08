# Guide — Setting Up and Running a Panel

How to adopt the methodology in this pack: choose seats and a
coordinator, create the shared folder, adopt the Log Standard, start
Current State, run the first roundtable, and keep the whole thing alive
past the first week.

The rules themselves live in
`log-standard/AI-Assistant-Log-Standard.md`. This guide is the order to
do things in, and the judgment calls the standard assumes you have
already made.

## Step 1 — Choose seats and a coordinator

A **seat** is one AI assistant the owner uses: a chat product, an agent
on the owner's machine, a scheduled assistant, any of them. Two seats
is a panel. Five is plenty. More than that and the cross-checking costs
more than the redundancy buys.

Name **one coordinator** from among the seats. The coordinator:

- Owns Current State (the only seat that edits it).
- Moderates Panel Comms, the shared message board.
- Creates roundtable documents and synthesizes them once all answers
  are in.
- Scribes for seats whose write path does not work, pasting their text
  verbatim and marking it as pasted.
- Optionally, reconciles the newest log entries each morning into one
  briefing for the owner.

Pick the coordinator for its write access and reliability, not its
cleverness. The job is bookkeeping. A panelist seat should never
duplicate the coordinator role: two seats "owning" Current State is how
it forks.

Also name, once the panel is running:

- A **weekly cross-checker** — a seat that is *not* the Current State
  owner (see Step 6).
- Who may do what outward. The standing rule from the source panel:
  outward sends, posts, purchases, and applications always need the
  owner's explicit go-ahead for that action, whatever the panel has
  decided internally.

Write each seat's actual abilities down honestly at the start: can it
write to the shared folder itself? Can it run unattended? Can it edit a
shared document from a link, or only produce text for someone else to
paste? The standard's capability-claim rule applies from here on: no
seat calls itself "automated", "daily", or "synced" until it has
completed one unattended write and logged it, Completed, with a
Verified tag.

## Step 2 — Create the shared folder

One folder (or workspace, or shared drive — the medium does not matter)
that holds:

- The Log Standard (one canonical copy; changes are made there, in its
  change log, and nowhere else).
- One Daily Log document per seat, titled `[Seat] Daily Log — YYYY-MM`,
  rolled over monthly.
- Optional per-seat Cross-Read and Private Notes companion documents.
- Panel Comms (one document).
- Current State (one document).
- One document per roundtable, titled `Roundtable: [Topic] — YYYY-MM-DD`.

Not every seat needs direct write access to all of it. A seat that
cannot write gives the owner (or the coordinator, as scribe) its text
in the standard format and says so in its log header. Never let a seat
silently pretend a write happened.

## Step 3 — Adopt the Log Standard

Give each seat the full standard and the paste-in instruction at its
end (Part D). Each seat then records **its own adoption** as one
Decided entry in its own Daily Log, listing any part it cannot follow
and why. Nobody records anyone else's adoption, and nobody declares the
standard "in force for everyone" — overall status belongs in Current
State, once it exists.

Expect friction in the first days, in predictable places:

- Seats will copy each other's open items into their own logs. Correct
  it with the standard's Corrected-entry procedure, not by quietly
  editing.
- Seats will claim capabilities they have not shown. The header rule
  (state how updates actually happen) fixes this in the open.
- Seats will forget evidence tags on Completed entries. The weekly
  cross-check counts them.

## Step 4 — Start Current State

Copy `templates/current-state-template.md` and fill in the owner line:
who owns the document (the coordinator, unless the owner names someone
else), and who the weekly cross-checker is.

Start it **empty or nearly empty**, and let it grow only from "For
Current State" proposals in Daily Logs, each citing its entry number.
Do not seed it from summaries, memories, or another assistant's
overview: a stale seeded item looks authoritative and is the single
most copied error in a young panel.

The shape, from the template: Open items, Decisions in force, Standing
preferences, Key facts, plus a Closed section finished items move to
(close, do not delete; cleared after 30 days). Two pages at most. An
open item not confirmed in 14 days gets marked "Stale?" and raised
with the owner.

## Step 5 — Run the first roundtable

Use `templates/roundtable-template.md`. Pick a real question with a
real decision attached, but a small one.

1. The coordinator creates the document, fills in the question
   **verbatim** (never paraphrased), the context, and the constraints.
2. The coordinator answers first, in its own section, so every other
   seat is answering the same question and the same framing.
3. The owner (or coordinator) sends each other seat the copy-paste
   prompt from the template, with the document link.
4. Each seat answers only in its own section: recommendation,
   reasoning, risks, what it would change about the framing, and
   confidence. Direct editing is preferred; paste-back is the fallback,
   marked as pasted and kept verbatim.
5. When all answers are in, the coordinator synthesizes: where they
   agree, where they disagree, what nobody addressed, and a
   recommendation. Disagreement is recorded, not smoothed over.
6. The owner records the decision in the document, in the owner's own
   words, with the date and follow-ups.

Status moves Open, then Collecting, then Synthesized, then Decided.

Two habits make roundtables worth the effort: panelists challenge the
framing, not just the options; and a seat that cannot do something the
question assumes (edit the document, run unattended, see another seat's
data) says so in its answer rather than playing along.

## Step 6 — Keep it alive

The daily cadence is deliberately light:

- **Seats log as they go**, during sessions, and close the day by the
  end of the day in the owner's timezone. A seat whose sessions start
  fresh, with no access to the day's other sessions, must log during
  each session (log-as-we-go) rather than reconstructing at night.
- **Nightly**, the Current State owner merges the day's "For Current
  State" lists. Conflicting proposals go to the owner as a question,
  never resolved silently.
- **Optionally, each morning**, the coordinator reconciles the newest
  entry of each log into one short briefing. A log it cannot reach is
  skipped, not guessed about.

Once a week, the cross-checker (never the Current State owner) compares
Current State against the Daily Logs and reports: items shown open that
a log shows finished; facts that differ between logs; Completed entries
without evidence tags; copied content; sensitive details sitting outside
the companion documents. The checker reports and does not fix. Fixes go
through the correction rule, appended, so the record of the error
survives.

Panel Comms runs alongside all of this as the coordination board:
one-line posts for status, questions, and answers; append-only; no
chit-chat. Decisions that emerge there are not settled until they land
in Current State with a log citation.

## The authority order, and relayed decisions

When documents disagree, the order is fixed:

1. **The owner.**
2. **The first-hand Daily Log that recorded the event.**
3. **Current State.**

A Cross-Read document never settles anything; it points at sources.
And a decision **relayed** through an assistant — "another seat says
the owner decided X" — is information-only until the owner confirms it
in their own words. This rule will feel slow exactly once, and then it
will save you from acting on a decision the owner never made.

## Routing questions to seats

There is no automatic router and no shared model pool, and the method
does not pretend otherwise. The coordinator fans a question out to other
seats on its own judgment, each seat answers independently in its own
session, and the coordinator brings back a comparison of the answers —
differences, gaps, and disagreements included — rather than a blended
consensus. Log every consultation: date, time, seat consulted,
question, topic category, reason, outcome. No seat claims another
seat's tools, memory, or capabilities as its own.

Per-action authorization survives all of this: a panel decision is not
an outward action. Sends, posts, purchases, and account changes still
need the owner's explicit go-ahead for that action, the exact thing
shown to the owner first, and verification before anyone reports it
done. A draft is not a sent message, and a filled form is not a
submitted one.

## Working with the owner at a machine: front office / back office

If one of the seats can operate the owner's computers, the source panel
splits machines into two classes, and the distinction is worth adopting
verbatim:

- **Front office** — the machine the owner is physically using. The
  owner stays in control. The assistant may look (snapshots of the
  visible window, when asked) but does not click, type, scroll, or
  navigate there.
- **Back office** — a machine the owner is not using. The assistant may
  work there, within the owner's standing authorizations for that
  machine.

On either class: never read out passwords, one-time codes, or other
secrets that happen to be visible on screen. Pause and let the owner
decide what to share. Name the machine before working on it, and check
it is actually idle (and not claimed by another of the owner's chats or
jobs) before starting.

## What to expect

Week one is mostly format discipline: headers, tags, corrections. Week
two is when the panel starts paying for itself — a seat catches another
seat's error in cross-check, a roundtable surfaces a risk nobody had
priced in, Current State answers "where did we land on that?" in one
look instead of four searches. The method's whole return is that those
moments become routine instead of lucky.
