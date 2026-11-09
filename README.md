# PI intake completeness and handoff — draft for review

A small, tool-free skill from Nimbus AI Holdings for operations staff and implementers supporting plaintiff PI firms with 1–10 attorneys. It converts a synthetic/de-identified summary into a missing-fields review, internal handoff and optional human-reviewed reply draft. It does not decide whether a case is qualified.

## Why this first
Narrow, inspectable, useful without buying Nimbus; directly adjacent to Marlowe's intake/handoff use case. The skills.sh audience skews toward people using coding agents, so reach to law-firm buyers is unproven. This is an experiment for implementers serving those firms, not a replacement for commercial landing pages or an SEO guarantee. A PE rubric could follow only if real demand supports it.

## Use
Read `skills/pi-intake-handoff/SKILL.md` and `SYNTHETIC-EXAMPLE.md`. Give an agent the instructions and the synthetic example. No integrations, credentials, dependencies or scripts are needed. Do not provide real medical, client, privileged or identifying data. Use your firm's approved secure system for actual client work.

## Installation
Repository: `NimbusAI-coder/nimbus-agent-skills`.

```text
npx skills add NimbusAI-coder/nimbus-agent-skills --skill pi-intake-handoff
```

Agent compatibility and CLI installation have not been tested. Directly supplying the Markdown is sufficient for draft evaluation.

## What it cannot do
No Marlowe or Clio connection; no account access; no sending, bookings, CRM writes, medical advice, legal advice, case evaluation, or deadline calculation. It is not a privacy/security/compliance certification. Human review is mandatory. Marlowe intake replies remain drafts and Clio handoff is one-way; installing this skill enables neither capability.

Publisher/product context: https://nimbusai.biz/law . No affiliation with or endorsement by Vercel is claimed.

## Licensing
MIT License. Copyright (c) 2026 Nimbus AI Holdings. See LICENSE.

## Status
Local preparation only; no public repository, listing, submission, CLI installation or telemetry seeding. See `RESEARCH-AND-RELEASE.md` and `REVIEW-CHECKLIST.md`.
