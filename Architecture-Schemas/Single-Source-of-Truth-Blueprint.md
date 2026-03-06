# Single Source of Truth Blueprint

> "Three departments. Three words for the same order. Three places it breaks."

---

## What It Is

One agreed data model that defines the core entities and statuses your entire operation runs on. Every tool, tracker, and team member uses the same vocabulary.

Without this: sales says “confirmed”, ops says “allocated”, factory says “in production” — same order, three different statuses, zero visibility.

---

## Why It Matters Before Anything Else

You cannot build a reliable system on top of an unreliable vocabulary.

Before choosing tools. Before automating. Before building dashboards. You need every department to agree on what words mean.

---

## Core Entities (DTC Ecommerce)

| Entity | Status Options |
|---|---|
| SKU / Variant | active, discontinued, in-development |
| Order | received, allocated, in-production, dispatched, returned, exchanged |
| Production run | PO-sent, PO-confirmed, in-production, shipped, received, QC-passed |
| Inventory unit | in-stock, allocated, in-transit, at-risk, damaged, exchange-hold |
| Factory PO | draft, confirmed, in-production, delayed, completed |

---

## Common Failure Patterns

| Pattern | What It Looks Like | What It Costs |
|---|---|---|
| Status fragmentation | Sales says "confirmed", ops says "allocated" | Handoffs fail silently |
| Spreadsheet sprawl | Inventory count in 3 sheets, none current | Nobody trusts the number |
| PO in email | Factory status tracked in inbox, not system | Delays invisible until critical |
| Returns orphaned | Tracked in separate sheet nobody reads | Returns don’t feed back into stock |
| Vocabulary drift | Terms mean different things per department | Reporting is meaningless |

---

## Implementation Sequence

1. Run the Operational Architecture Audit first — extract the REAL entities, not the ideal ones
2. Map current vocabulary per department — what word does each team use for each status?
3. Negotiate a shared vocabulary — one word per status, agreed by all department leads
4. Lock it in writing — a shared reference document, one page
5. Build the tracker skeleton using only the agreed vocabulary
6. Enforce it across all tools, SOPs, and team comms
7. Do not automate until the vocabulary has been stable for 30 days

---

## System: Before → After

| Dimension | Before | After |
|---|---|---|
| Vocabulary | Each department uses different terms | One vocabulary, written, agreed, enforced |
| Inventory data | Multiple spreadsheets, none current | One tracker, one number |
| Factory status | Lives in email threads | Tracked in system with status field |
| Order handoffs | Verbal or message-based | Status-triggered, documented |
| Reporting | Different departments report different numbers | One source, one report |
| Onboarding | New team members learn the language informally | One-page vocabulary reference |
| Data trust | Nobody trusts the data | Everyone works from the same number |

---

## Key Rule

Do not build the system around the tools you have.
Build the vocabulary first. Then configure tools to match.

A tool built on a broken vocabulary will automate the confusion — not eliminate it.

---

> ⚠️ **Full implementation blueprints — including entity model templates, status library, naming conventions, and tracker skeleton designs — are available to active clients.** This document shows the architectural logic. The build is customized per organization.

---

## Related Documents

- [Operational-Audit-Methodology.md](https://github.com/ladislavjuric-OS/Operations-Architecture-SOP/blob/main/Architecture-Schemas/Operational-Audit-Methodology.md) — The audit process that produces the vocabulary
- [Escalation-Matrix-Template.md](https://github.com/ladislavjuric-OS/Operations-Architecture-SOP/blob/main/SOP-Library/Escalation-Matrix-Template.md) — Decision framework built on locked vocabulary
- [30-60-90-Roadmap-Template.md](https://github.com/ladislavjuric-OS/Operations-Architecture-SOP/blob/main/SOP-Library/30-60-90-Roadmap-Template.md) — Roadmap structure that starts with vocabulary lock
- [Nashville-Venture-Studio.md](https://github.com/ladislavjuric-OS/Operations-Architecture-SOP/blob/main/Architecture-Schemas/Nashville-Venture-Studio.md) — Multi-division source of truth architecture
- [KPI-Scorecard-Template.md](https://github.com/ladislavjuric-OS/Operations-Architecture-SOP/blob/main/SOP-Library/KPI-Scorecard-Template.md) — Scorecard built on agreed vocabulary and entities

---

📨 **[Contact & Connect](https://github.com/ladislavjuric-OS/Operations-Architecture-SOP#contact--connect)** — Interested in implementation? Let’s talk.

---

*Architecture by Ladislav Jurić | Operations Architect | Proof Before Promise™*
