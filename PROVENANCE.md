# Provenance

Where this pack came from, what was generalized to make it publishable,
and what was deliberately left out. Change classes are described;
removed values are never recorded here.

## Origin

The pack documents the working methodology of one person's multi-AI
panel: several AI assistants ("seats") coordinated by one seat, run
daily since October 2026 against a shared folder of logs, a shared
Current State document, a shared message board, and roundtable
documents. It was staged as a public edition on November 4, 2026, after
the underlying Log Standard reached an approved version (see version
history below).

## Sources, file by file

- `log-standard/AI-Assistant-Log-Standard.md` — the panel's own Log
  Standard, v1.7, worked from a sanitized copy of the standard prepared
  in October 2026 for cross-panel alignment. Sections 15–19 postdate
  that copy, so they were worked from the owner's downloaded copy of
  the live draft (the text of record) instead. Every operating rule is
  preserved; see the standard's own change log.
- `GUIDE.md` — written for this pack from the panel's operating
  practice: the setup order, the daily cadence, the authority order,
  the routing of questions to seats, and the front-office / back-office
  convention for working alongside the owner at a machine.
- `templates/current-state-template.md` — the Current State schema as
  specified in the panel's communication protocol, cross-checked
  against the structure of the live Current State document. Only the
  schema was taken; no live content.
- `templates/roundtable-template.md` — the panel's roundtable template
  document, converted from its original word-processor format.
- `templates/daily-log-template.md` — derived from sections 4–10 of the
  Log Standard.
- `templates/panel-comms-note.md` — the message-board conventions from
  the panel's communication protocol.
- `examples/representative-log-and-roundtable.md` — the sanitized
  representative log and roundtable prepared in October 2026,
  re-generalized to this pack's placeholder standard; its two parts are
  illustrative, not transcripts.

## Version history of the Log Standard in this pack

- **Oct 9, 2026** — v1.0 issued; two same-night v1.1 drafts merged into
  v1.2; v1.3–v1.5 followed the same day and next.
- **Oct 11, 2026** — v1.6 issued; canonical standard for the panel.
- **Oct 14, 2026** — v1.7 drafted and revised in one day (a reviewing
  seat's 7 comments, then 8 follow-up residuals, all closed). It added
  the backup coordinator (§14) and the paste-back rule. It remained a
  **draft**: v1.6 stayed canonical, and v1.7 was neither published nor
  activated.
- **Nov 4, 2026 (earlier)** — this pack was first staged on v1.6,
  because a public pack should not present a draft standard as
  settled. The Log Standard file was left explicitly unfinalized and
  the version note in this file was held.
- **Nov 4, 2026, 11:39 PM ET** — the owner approved v1.7. The pack
  switched to match: the Log Standard in this pack was rebuilt from
  v1.7 with the draft framing removed, the change log was extended
  with the approval and the public-edition derivation, and README's
  version references were updated. Templates, guide, and examples are
  version-neutral and did not change.
- **Nov 5, 2026** — the owner approved sections 15–19, which had been
  added to the house draft after the v1.7 core was revised and were
  excluded from this edition at first staging (see Exclusions). They
  were generalized to the pack's placeholder standard and added to
  the Log Standard the same day, in the source's own position after
  section 14. The pending-approval markers they carried in the source
  were not carried over; the approval resolves them.

## Sanitization — change classes

- Personal names (owner, individual seats' house names) replaced with
  role placeholders: "the owner", "the coordinator", Seat 1, Seat 2,
  and so on; the outside collaborator in sections 15–19 is "the
  external assistant" throughout. The one exception in the pack is
  the copyright line in `LICENSE`.
- Seat identities in rules generalized to roles (coordinator, primary
  backup, backup-backup, on-hold seat). Worked citations in the
  standard keep product-level example labels only, as in the source.
- The shared folder's name and every document link or identifier
  replaced with "the shared panel folder" or removed.
- Clock times and channels tied to the source household generalized:
  times read as the owner's timezone, channel names as generic labels
  (e.g. "messaging app"). The one retained clock time is the morning
  cycle's, which is part of the §14 definition.
- Live document content replaced with blank templates and clearly
  marked illustrative examples; exact private values in examples
  appear only as `[redacted]` markers, never invented replacements.
- One-time, per-seat instructions in the source (dated rollout actions;
  backup-role confirmations) replaced with generalized checklists that
  preserve what each instruction was teaching.

## Exclusions

- **The real Oct 13, 2026 roundtable snapshot** present in the examples
  source is **excluded**. Its topic is the owner's own professional
  identity work, so the owner's identifiers run through it; no scrub
  would leave a readable document. An illustrative completed roundtable
  is included instead, and the exclusion is also noted in the examples
  file itself.
- **Live Current State content** — schema only, for the same reason the
  standard forbids seeding Current State from memory: the content is
  the owner's life, not the method.
- **Private Notes companion content** — none appears in any source, by
  the standard's own section 9 design; nothing to exclude and nothing
  included.
- **The v1.7 draft as a separate file** — superseded by the approved
  standard itself; its drafting history is summarized above and in the
  standard's change log rather than shipped as a second document.
- **Sections 15–19 of the house draft** — five further sections, added
  after the v1.7 core was revised, covering additional seating,
  roundtable closeout, guiding principles, and stand-down and charter
  material. They were **excluded at first staging**: they carried the
  owner's pending-approval markers and were not part of the Nov 4,
  2026 approval, which covered the v1.7 core (sections 1–14,
  Parts A–D). The owner approved them on Nov 5, 2026, and they were
  added in the follow-on pass recorded above — so this bullet now
  stands as the record of a resolved exclusion, not a current one.
  One piece of their source context remains excluded: the dated
  pending-review checklist that followed section 19 in the house
  draft. It was a one-time review agenda for a specific meeting, not
  a rule, and is excluded on the same basis as the one-time per-seat
  actions in Part C.
- **Household and machine material** — the source panel's machines,
  network, and other projects are not part of this methodology and
  appear nowhere in the pack.
- No software, credentials, tokens, or access instructions for the
  source panel's systems are included; there is nothing to run.

## A note on method

The sanitization standard applied here is the one the source panel
uses for its own alignment copies: preserve every rule, replace every
identifier, invent nothing. The pack was swept mechanically for
identifiers before staging (counts are reported with the pack's
staging record, not in this file).
