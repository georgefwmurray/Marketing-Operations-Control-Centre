# Campaign Build Agent

Key Result: 60 minutes saved per campaign build
Layer: Production
Problem: Manual Campaign Cloning & Asset Updates
Status: Live

[🏠 Home](../../Home%20410cf2872cd3818384f7d46e2a3815c2.md) · [🧩 Agent Registry](../Agent%20Registry%20394cf2872cd3810fa4f5f95f8f125cf0.md) · [📈 Results](../Results%20394cf2872cd38181903de57b1f1a312a.md) · [🗺️ Roadmap](../Roadmap%20394cf2872cd381d58a13d7ca2136edc4.md) · [💼 Campaign & Commercial Projects](../Campaign%20&%20Commercial%20Projects%2039bcf2872cd38176b899cdeca23f2267.md) · [👥 Leadership & Strategy](../Leadership%20&%20Strategy%20395cf2872cd381a1a5c8e11299862f40.md) · [🔧 How to Build MOCC](../How%20to%20Build%20MOCC%20410cf2872cd381b3b585fd01db7e5b66.md) · 

---

**Layer:** 🏗️ Production — Campaign Delivery  

**Status:** 🟢 Live

**Platform:** Claude Cowork · Claude Skill · Claude/HubSpot MCP Actions

**Deployment:** Veriforce — 1 brand (onboarding campaigns)

**Last updated:** September 2026

**Version:** 1.1

## Business Problem

Building a new campaign from an existing template required manually cloning each asset (email, landing page, workflow) and updating them one by one with new creative, logos, videos, and copy, then rebuilding the workflow logic each time. This was repetitive and time-consuming for every new campaign launch.

## Solution Overview

Using Claude Cowork alongside Claude/HubSpot MCP actions, the agent clones an existing campaign template (email, landing page and workflow) and updates it with newly provided assets (logos, videos, copy), producing a fully built new campaign ready for review, removing the manual cloning and asset-swapping work previously done by hand. The build runs as a Claude Skill following a strict, repeatable process for onboarding campaigns: about 10 minutes of agent time followed by about 20 minutes of human QA.

![Flow_CampaignBuild.svg](Campaign%20Build%20Agent/Flow_CampaignBuild.svg)

## Business Value

- Saves approximately **60 minutes of manual execution time per campaign** (about 30 minutes with the agent and human QA, versus about 90 minutes manually), roughly 4 hours a month at 4 campaigns a month
- Removes repetitive manual cloning and asset-swapping work
- Speeds up campaign delivery time
- Reduces risk of manual copy/paste errors when rebuilding assets

### Cost Savings

- **Time reclaimed (pilot):** 16 hrs/month per brand = **£19,200/year**
- **Projected if scaled to 5 brands:** 80 additional hrs/month = **£96,000/year**
- **Secondary benefit:** Standardizes campaign quality across brands; reduces approval cycles

## Version History

| Version | Date | Milestone |
| --- | --- | --- |
| 1.0 | July 2026 | Initial live version: clones email, landing page and workflow templates, updates with provided assets, and creates new campaign |
| 1.1 | September 2026 | Build time reduced and test email send added |

## Design Insights

Building this on Claude Cowork with HubSpot MCP actions meant the same underlying architecture used for read-only insight generation (Campaign Performance Agent) could be extended into write/create actions, cloning and updating live campaign assets directly rather than needing separate bespoke automation for each asset type.

---

## Explore Other MOCC Modules

- [Clarity Website Analyst](Clarity%20Website%20Analyst%203edcf2872cd381f9b5cadf69beff0f07.md)
- [Email QA Agent](Email%20QA%20Agent%20394cf2872cd3812eb679f7657980d7b4.md)
- [Website QA Agent](Website%20QA%20Agent%20394cf2872cd381528052cb21608d6db0.md)
- [Data Import Agent](Data%20Import%20Agent%20394cf2872cd381319d4eee4a7bb3dbb0.md)
- [Agent Intake & Approval Agent](Agent%20Intake%20&%20Approval%20Agent%20400cf2872cd381728db6cbc4d10a867e.md)
- [CRM Health Agent](CRM%20Health%20Agent%20396cf2872cd381598482c6978e3a2389.md)
- [Campaign Performance Agent](Campaign%20Performance%20Agent%20394cf2872cd38132b545cd1e773d04ef.md)
- [Content Agent](Content%20Agent%203e8cf2872cd3819f8769ece6c9198c23.md)
- [WordPress Post Creation Agent](WordPress%20Post%20Creation%20Agent%203e8cf2872cd381e98c4adb092f4696fd.md)

- [Agent Health Monitor](Agent%20Health%20Monitor%20410cf2872cd3814a913bcabfac55638e.md)