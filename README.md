# NIST CSF 2.0 Maturity & Gap Assessment — Solstice Logistics Group Ltd

## Overview

This assessment evaluates the cybersecurity maturity of Solstice Logistics Group Ltd, a fictional UK road freight and warehousing operator, against all six Functions and 22 Categories of the NIST Cybersecurity Framework (CSF) 2.0. It identifies the gap between current and target maturity for each Category and translates the findings into a prioritised, quarter-by-quarter remediation roadmap.

Solstice is fictional. No real organisation, employee, or customer is represented.

## Contents

| File | Description |
|---|---|
| `NIST_CSF_Maturity_Gap_Assessment_Solstice.xlsx` | Four-tab workbook: Read Me, Maturity Assessment, Function Summary, Roadmap |

## Scope and context

Solstice's environment includes a warehouse management system (WMS) hosted on-premise, a fleet telematics platform, driver handheld devices, and EDI integrations with retail and manufacturing customers. This profile was chosen deliberately: logistics carries a different risk shape from the SaaS or financial-services environments most sample assessments use — shared terminal logins during shift changeovers, patch cycles deferred to avoid disrupting live warehouse operations, and operational technology alongside conventional IT.

## Methodology

Each of the 22 CSF 2.0 Categories is scored twice — Current maturity and Target maturity — on a 0–4 scale:

| Score | Definition |
|---|---|
| 0 | Not performed |
| 1 | Performed informally and inconsistently |
| 2 | Performed consistently, but reactive rather than managed |
| 3 | Documented, standardised, and proactively managed |
| 4 | Measured quantitatively and continuously improved |

Gap is calculated as Target minus Current. Priority is derived directly from gap size rather than assigned independently, so the roadmap sequence follows from the scoring rather than a separate judgement call. Each score is supported by a specific evidence note rather than a general statement — for example, the low score on identity and access control is attributed to shared logins on warehouse terminals and the absence of MFA on the WMS admin console, not a generic access-control weakness.

## Key findings

- Company-wide average maturity: **0.81 (Current)** against **2.48 (Target)**
- Lowest-scoring Categories: Detect (Continuous Monitoring and Adverse Event Analysis both score 0) and Respond (Incident Analysis and Response Communication both score 0)
- Highest-scoring Categories: Asset Management and Incident Recovery Plan Execution (2/4 each), reflecting an informal but existing asset list and untested but functioning backups
- Target maturity is capped at 2 or 3 for several Categories rather than 4 across the board, reflecting a proportionate target for a company of this size rather than a maximal one

## Structure of the workbook

1. **Read Me** — methodology, maturity scale, and document control
2. **Maturity Assessment** — all 22 Categories with Current/Target scores, gap, priority, evidence, recommended action, owner, and target quarter
3. **Function Summary** — average Current and Target maturity per Function, with a comparison chart
4. **Roadmap** — the same 22 actions, resequenced by target quarter and priority

## Limitations

This is a point-in-time assessment based on a single fictional scenario, not a longitudinal study. Scoring was performed by one assessor against documented criteria rather than validated through independent review, which is standard practice in a real maturity assessment engagement.
