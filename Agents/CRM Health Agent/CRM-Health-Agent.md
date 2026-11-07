# CRM Health Agent

Key Result: Monthly list of inactive assets flagged for archive approval
Layer: Governance
Problem: Inactive CRM assets building up
Status: Live

[🏠 Home](../../Home%20410cf2872cd3818384f7d46e2a3815c2.md) · [🧩 Agent Registry](../Agent%20Registry%20394cf2872cd3810fa4f5f95f8f125cf0.md) · [📈 Results](../Results%20394cf2872cd38181903de57b1f1a312a.md) · [🗺️ Roadmap](../Roadmap%20394cf2872cd381d58a13d7ca2136edc4.md) · [💼 Campaign & Commercial Projects](../Campaign%20&%20Commercial%20Projects%2039bcf2872cd38176b899cdeca23f2267.md) · [👥 Leadership & Strategy](../Leadership%20&%20Strategy%20395cf2872cd381a1a5c8e11299862f40.md) · [🔧 How to Build MOCC](../How%20to%20Build%20MOCC%20410cf2872cd381b3b585fd01db7e5b66.md) · 

---

**Layer:** ⚙️ Governance

**Status:** 🟢Live

**Platform:** Claude (Claude Skill)

**Deployment:** Veriforce — 5 brands

**Live since:** September 2026

**Last updated:** October 2026

**Version:** 1.0

## Business Problem

Workflows, emails, forms and landing pages that have had no activity for 12 months or more build up in the CRM. Left alone, they add technical debt and make it harder to see what is actually in use.

## Solution Overview

![Flow_CRMHealth.svg](CRM%20Health%20Agent/Flow_CRMHealth.svg)

The CRM Health Agent is a Claude Skill that runs every month. It evaluates workflows, emails, forms and landing pages, finds any that have had no activity in the past 12 months, and flags a list of each asset for human archive approval. Nothing is archived without a person approving it.

It brings workflow, email and forms governance together under one agent.

## Business Value

- One monthly run covers workflows, emails, forms and landing pages
- Every asset with no activity in the past 12 months is flagged, so nothing inactive is missed
- Archiving stays a human decision, with the agent supplying the list
- Workflow, email and forms governance sit under a single agent rather than three

### Cost Savings

- **Time reclaimed:** 8 hrs/month = **£9,600/year**
- **Compliance value:** Prevents audit findings on stale asset accumulation; reduces operational risk

## Version History

| Version | Date | Milestone |
| --- | --- | --- |
| v1.0 | September 2026 | Monthly review of workflows, emails, forms and landing pages with no activity in 12 months, flagged for human archive approval |

## Design Insights

Combining the asset types under one agent keeps governance in a single monthly review. The agent finds and flags, and a person approves every archive.

---

## Explore Other MOCC Modules

- [Agent Intake & Approval Agent](Agent%20Intake%20&%20Approval%20Agent%20400cf2872cd381728db6cbc4d10a867e.md)
- [Clarity Website Analyst](Clarity%20Website%20Analyst%203edcf2872cd381f9b5cadf69beff0f07.md)
- [Email QA Agent](Email%20QA%20Agent%20394cf2872cd3812eb679f7657980d7b4.md)
- [Website QA Agent](Website%20QA%20Agent%20394cf2872cd381528052cb21608d6db0.md)
- [Data Import Agent](Data%20Import%20Agent%20394cf2872cd381319d4eee4a7bb3dbb0.md)
- [Campaign Performance Agent](Campaign%20Performance%20Agent%20394cf2872cd38132b545cd1e773d04ef.md)
- [Campaign Build Agent](Campaign%20Build%20Agent%203accf2872cd381fd85feda9dc5153487.md)
- [Content Agent](Content%20Agent%203e8cf2872cd3819f8769ece6c9198c23.md)
- [WordPress Post Creation Agent](WordPress%20Post%20Creation%20Agent%203e8cf2872cd381e98c4adb092f4696fd.md)
- [Agent Health Monitor](Agent%20Health%20Monitor%20410cf2872cd3814a913bcabfac55638e.md)