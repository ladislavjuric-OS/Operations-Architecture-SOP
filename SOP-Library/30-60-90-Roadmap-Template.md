# 30/60/90 Day Ops Roadmap Template

> "Vocabulary before tracker. Tracker before SOP. SOP before automation. Automation before scale. Skipping steps creates technical debt in operations, not just in code."

---

## Purpose

A prioritised, time-boxed plan for operational improvement following an audit.
Based on impact vs complexity — not on what is most interesting to build.

---

## Principles

- Build what removes the most pain first
- Defer what is important but not yet blocking
- Ignore what adds complexity without proportional value
- No tool recommendation before vocabulary is locked
- No automation before manual process is stable for 30 days

---

## 30-Day Window — Foundation

**Goal:** Lock the operating vocabulary. Build the single source of truth.

- Lock vocabulary: statuses, naming conventions, ownership
- Build tracker skeleton: one source of truth per core entity
- Run first weekly ops review using new system
- Identify top 3 manual processes for SOP documentation
- Confirm tooling direction — do not build yet

**Gate to proceed to 60-Day:** Tracker is live. Vocabulary is locked. First weekly review has run.

---

## 60-Day Window — Pilot

**Goal:** Test the system on the primary channel. Write and validate the first SOPs.

- Deploy tracker to primary channel or fulfilment centre
- Write and test first 3 SOPs with real team
- First weekly dashboard (manual is fine at this stage)
- Identify integration and automation opportunities
- Document them — do not build yet

**Gate to proceed to 90-Day:** 3 SOPs validated. Tracker stable for 30 days. Dashboard running.

---

## 90-Day Window — Rollout

**Goal:** Extend to remaining channels. Automate the stable layer.

- Extend tracker to remaining channels and fulfilment centres
- Automate reporting layer where process is stable
- Escalation matrix in live daily use
- Gap analysis: what to address in next quarter
- Founder/Owner extraction audit: what still requires them that should not

---

## What Goes in Defer

Anything requiring 3+ stakeholders, significant data migration, or external dependency.
Scope it. Price it. Do not start it until the 30-day foundation is stable.

Examples: ERP migration, full API integrations, multi-warehouse automation.

---

## What Goes in Ignore

- Features nobody has asked for
- Reporting on metrics nobody acts on
- Integrations that solve theoretical problems
- Automation of a process that has not been stable for 30 days

---

## System: Before → After

| Dimension | Before (Day 0) | After (Day 90) |
|---|---|---|
| Roadmap | Founder/Owner has a mental list | Written, prioritised, time-boxed plan |
| Tooling decisions | Reactive, tool-first | Vocabulary-first, then tool |
| Automation | Automating broken processes | Automating stable, validated processes |
| SOP coverage | Tribal knowledge, verbal instructions | 3+ written, tested, live SOPs |
| Reporting | Manual, inconsistent, delayed | Weekly dashboard, one source of truth |
| Scope creep | Every improvement becomes a project | Defer/Ignore list prevents scope inflation |
| Ops rhythm | Ad hoc | Weekly review, 30/60/90 cadence |

---

## Common Mistakes

| Mistake | What Happens | Fix |
|---|---|---|
| Start with tools, not vocabulary | Tool built on broken language | Vocabulary first, always |
| Automate before stabilising | Automation locks in the error | 30-day manual stability rule |
| Build everything at once | Nothing gets finished | 3 priorities max per window |
| Skip the 30-day gate | Pilot fails, rollout collapses | Respect the gate conditions |
| Ignore the Defer list | Scope inflates, team loses focus | Review and re-commit to Defer monthly |

---

> ⚠️ **Full implementation blueprints — including roadmap templates, gate criteria, SOP formats, and dashboard designs — are available to active clients.** This document shows the architectural logic. The build is customized per organization.

---

## Related Documents

- [Operational-Audit-Methodology.md](https://github.com/ladislavjuric-OS/Operations-Architecture-SOP/blob/main/Architecture-Schemas/Operational-Audit-Methodology.md) — Audit that produces the input for this roadmap
- [Single-Source-of-Truth-Blueprint.md](https://github.com/ladislavjuric-OS/Operations-Architecture-SOP/blob/main/Architecture-Schemas/Single-Source-of-Truth-Blueprint.md) — Vocabulary lock — the 30-day foundation
- [Escalation-Matrix-Template.md](https://github.com/ladislavjuric-OS/Operations-Architecture-SOP/blob/main/SOP-Library/Escalation-Matrix-Template.md) — Delegation framework installed in the 60-day window
- [Nashville-Venture-Studio.md](https://github.com/ladislavjuric-OS/Operations-Architecture-SOP/blob/main/Architecture-Schemas/Nashville-Venture-Studio.md) — Full operating architecture at 90-day completion
- [KPI-Scorecard-Template.md](https://github.com/ladislavjuric-OS/Operations-Architecture-SOP/blob/main/SOP-Library/KPI-Scorecard-Template.md) — Dashboard built in the 60-day window

---

📨 **[Contact & Connect](https://github.com/ladislavjuric-OS/Operations-Architecture-SOP#contact--connect)** — Interested in implementation? Let’s talk.

---

*Architecture by Ladislav Jurić | Operations Architect | Proof Before Promise™*
