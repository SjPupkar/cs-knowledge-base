---
title: Customer Risk & Escalation Playbook
summary: Identify, triage, and resolve customer risks to protect outcomes, renewals, and revenue.
tags: [risk, escalation, renewal, churn, playbook]
last_updated: 2025-09-09
author: Steve Pupkar
---

## Goals
- Detect risks early with clear leading indicators
- Triage and assign owners within **24 hours**
- Drive a corrective plan with measurable impact
- Protect on-time renewals and references

---

## Definitions
- **Risk:** Any factor that threatens outcomes, adoption, expansion, or renewal.
- **Escalation:** A time-boxed request for additional resources or authority to remove blockers.

---

## Severity Levels (S0–S3)
| Sev | Definition | Examples | Target First Response |
|-----|------------|----------|-----------------------|
| **S0 Critical** | Revenue at immediate risk or production outage with exec attention | Contract at D-30 with unresolved blocker; outage impacting all users; security incident | **2 hours** |
| **S1 High** | Major business impact; renewal/expansion risk in next 60–90 days | Sponsor departure; adoption collapse (>40% drop 14d); unresolved Sev-1 support issues | **4 business hours** |
| **S2 Medium** | Meaningful impact, manageable with plan | Integration delay; missing persona enablement; moderate usage decline | **1 business day** |
| **S3 Low** | Early signal; track & nudge | Slow stakeholder mapping; sporadic usage by a key team | **2 business days** |

---

## Detection Signals (Leading Indicators)
- **Adoption:** WAU/MAU drop **>30%**, feature usage below target personas, time-to-first-value slipping
- **People:** Sponsor/POC turnover, competing priorities, reorgs, change freeze
- **Commercial:** Unpaid invoices, budget freezes, procurement delays
- **Support:** ≥2 Sev-1 tickets in 30 days, unresolved critical bug, repeated workarounds
- **Product Fit:** Missing capability tied to a key use case, roadmap dependency not scheduled
- **Sentiment:** NPS ≤ 6, red health score, negative exec feedback

---

## Triage Workflow (RACI: CSM = A/R)
**Within 24h of detection**
1. **Log risk** in Risk Register (see template below) — _CSM (A/R)_
2. **Assign severity** and **owner(s)** — _CSM + Manager (A/C)_
3. **Create CAP (Corrective Action Plan)** with milestones & dates — _CSM (A/R), PS/SE (C)_
4. **Notify stakeholders** per Escalation Matrix — _CSM (R)_
5. **Set cadences** (war room/office hours) — _CSM (R)_

**Execution**
- Track progress twice weekly (S2/S3) or daily (S0/S1)
- Update register & timeline; capture decisions & blockers
- Close with root cause + prevention items

---

## Escalation Matrix
| Sev | Who to Notify | Channel / SLA | Cadence until Close |
|-----|---------------|---------------|---------------------|
| **S0** | Customer Sponsor & Execs; AE; CS Leader; Support/Eng Leadership; Security/Legal (if applicable) | Email + live call **same day** | Daily war room |
| **S1** | POC + Sponsor; AE; CS Manager; Support/Eng Manager; PS Lead | Email + Slack within **4h** | 3×/week |
| **S2** | POC; AE/AM; CS Manager; PS/SE | Email within **1 business day** | Weekly |
| **S3** | POC; AE; Internal CS notes | Email/notes within **2 business days** | Bi-weekly |

---

## Communication Templates

**Internal (Slack/Email) – Initial Escalation**
