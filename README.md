# OpsEngine — Consolidated QA Report (Nocturne QA)

Independent, human-quality validation of the OpsEngine marketing site and application.

**Five validation cycles consolidated into one report** (open `index.html` or visit the Pages URL):

- **C1 — Marketing site (public):** conversion & content journeys — 17 checks
- **C2 — Application core:** Ask (AI Studio) & Automate (Workflow Builder)
- **C3 — Full application sweep:** 14 modules incl. dashboard, library, knowledge, compliance, activity, settings, platform admin
- **C4 — Deep-dive pass 2:** prompts CRUD, library round-trip, workers & missions, guardrail enforcement E2E, RAG grounding
- **C5 — Pass 3:** not-run set — assign-task retest, delete paths, export, axe accessibility scan, resource scan

**Totals:** 146 checks/cases designed · 137 executed · 106 pass (77%) · 15 fail · 16 observations · 9 deferred.

**Defect register:** 1 Critical · 7 High · 4 Medium · 5 Low — each with repro, expected vs actual, and evidence.

Served via GitHub Pages: https://kmohamedmaaz.github.io/opsengine-qa-report/

---

*Nocturne QA — plan → validate → report → verify.*
