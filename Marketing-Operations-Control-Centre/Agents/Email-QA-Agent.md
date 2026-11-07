# Email QA Agent

Key Result: 80% reduction in manual QA effort
Layer: Control
Problem: QA Bottlenecks
Status: Live

[🏠 Home](../../Home%20410cf2872cd3818384f7d46e2a3815c2.md) · [🧩 Agent Registry](../Agent%20Registry%20394cf2872cd3810fa4f5f95f8f125cf0.md) · [📈 Results](../Results%20394cf2872cd38181903de57b1f1a312a.md) · [🗺️ Roadmap](../Roadmap%20394cf2872cd381d58a13d7ca2136edc4.md) · [💼 Campaign & Commercial Projects](../Campaign%20&%20Commercial%20Projects%2039bcf2872cd38176b899cdeca23f2267.md) · [👥 Leadership & Strategy](../Leadership%20&%20Strategy%20395cf2872cd381a1a5c8e11299862f40.md) · [🔧 How to Build MOCC](../How%20to%20Build%20MOCC%20410cf2872cd381b3b585fd01db7e5b66.md) · 

---

**Layer:** 🛡️ Control — Quality Assurance

**Status:** 🟢 Live

**Platform:** Microsoft Copilot Studio · Power Automate · SharePoint · Microsoft Teams · Marketing Automation Platform

**Deployment:** Veriforce — 5 brands 

**Last updated:** June 2026

**Version:** 1.3

## Business Problem

Marketing email QA relied on manual review across multiple stakeholders. Checks varied between reviewers, findings were not centrally recorded, and quality assurance often became a bottleneck before campaign deployment.

The objective was to create a repeatable, auditable and low-friction QA process that could be adopted consistently by the Marketing Operations team.

## Solution Overview

![Flow_EmailQA.svg](Email%20QA%20Agent/Flow_EmailQA.svg)

The Email QA Agent automates the pre-send validation of marketing emails by analysing test emails before deployment. A standard test email is forwarded from any marketing automation platform to a shared mailbox, triggering a Power Automate workflow that extracts the HTML and invokes a Microsoft Copilot Studio agent. The resulting QA report is automatically published to Microsoft Teams and recorded in a SharePoint governance log.

## Business Value

- Reduced manual QA effort by approximately **80%**
- Reduced campaign deployment time through automation
- Established an auditable QA history via SharePoint
- Standardised quality assurance across all campaigns
- Increased confidence prior to campaign deployment

*Methodology: based on 4 weeks of before/after data. Prior process averaged ~30 hours/month (3 reviewers, ~30 minutes per email check).*

### Cost Savings

- **Time reclaimed:** 8 hrs/month per brand = 40 hrs/month across 5 brands = £4,800/month = **£57,600/year**
- **Compliance risk reduced:** Audit trail prevents regulatory gaps
- **Secondary benefit:** Marketing Automation Executive freed to focus on workflow strategy instead of checklist work

## Version History

| Version | Date | Milestone |
| --- | --- | --- |
| v1.0 | March 2026 | Initial prototype using manual HTML submission |
| v1.1 | April 2026 | Simplified submission via shared mailbox |
| v1.2 | June 2026 | Event-driven automation with Power Automate |
| v1.3 | June 2026 | Governance reporting to Teams & SharePoint |

## Design Insights

The largest improvement came from reducing user friction.

Early versions required manual uploads of screenshots and HTML. By redesigning the workflow around a shared mailbox and event-driven automation, the user experience became almost invisible. Marketing users now complete QA simply by sending a standard HubSpot test email, allowing the automation to fit naturally into existing campaign processes rather than requiring new behaviours.

---

## Explore Other MOCC Modules

- [Clarity Website Analyst](Clarity%20Website%20Analyst%203edcf2872cd381f9b5cadf69beff0f07.md)
- [Email QA Agent](Email%20QA%20Agent%20394cf2872cd3812eb679f7657980d7b4.md)
- [Website QA Agent](Website%20QA%20Agent%20394cf2872cd381528052cb21608d6db0.md)
- [Data Import Agent](Data%20Import%20Agent%20394cf2872cd381319d4eee4a7bb3dbb0.md)
- [Agent Intake & Approval Agent](Agent%20Intake%20&%20Approval%20Agent%20400cf2872cd381728db6cbc4d10a867e.md)
- [CRM Health Agent](CRM%20Health%20Agent%20396cf2872cd381598482c6978e3a2389.md)
- [Campaign Performance Agent](Campaign%20Performance%20Agent%20394cf2872cd38132b545cd1e773d04ef.md)
- [Campaign Build Agent](Campaign%20Build%20Agent%203accf2872cd381fd85feda9dc5153487.md)
- [Content Agent](Content%20Agent%203e8cf2872cd3819f8769ece6c9198c23.md)
- [WordPress Post Creation Agent](WordPress%20Post%20Creation%20Agent%203e8cf2872cd381e98c4adb092f4696fd.md)
- [Agent Health Monitor](Agent%20Health%20Monitor%20410cf2872cd3814a913bcabfac55638e.md)