---
title: "Campaign Build Agent: 6 Hours Saved a Month"
description: "Claude Cowork workflow that clones and updates HubSpot campaign assets, saving about an hour of manual work per build and around six hours a month at current deployment volume."
---

# Campaign Build Agent

Key Result: Around six hours saved each month
Layer: Production
Problem: Manual Campaign Cloning and Asset Updates
Status: Live

[Home](../../index.html) • [Agent Registry](../../Agent-Registry.html) • [Results](../../Results.html) • [Roadmap](../../Roadmap.html) • [Campaign & Commercial Projects](../../Campaign-Commercial-Projects.html) • [Leadership & Strategy](../../Leadership-%26-Strategy.html) • [How to Build MOCC](../../How-to-Build.html) • [HubSpot Expert in South Wales](../../HubSpot-Expert-South-Wales.html)

---

**Layer:** Production — Campaign Delivery

**Status:** Live

**Platform:** Claude Cowork · Claude Skill · Claude/HubSpot MCP Actions

**Deployment:** Veriforce — 1 brand (onboarding campaigns)

**Last updated:** September 2026

**Version:** 1.1

## Business Problem

Building a campaign from an existing template meant cloning the email, landing page and workflow, then replacing the copy and creative assets and checking the workflow logic. Each launch involved a similar set of manual steps.

## Solution Overview

The workflow uses Claude Cowork and HubSpot MCP actions to copy an existing campaign template and update it with the supplied logos, videos and copy. It follows a repeatable Claude Skill process for onboarding campaigns.

The agent takes about 10 minutes to complete its part of the build. A person then spends around 20 minutes checking the work before it is ready to use.

![Flow diagram: Claude Cowork and Claude/HubSpot MCP actions clone the email, landing page and workflow for a new campaign, apply new assets, send a test email, then human QA](Flow_CampaignBuild.svg)

## Business Value

- Saves about **60 minutes of manual work per campaign build**
- Reclaims around **6 hours each month** at the current deployment volume
- Removes repeated cloning and asset-swapping tasks
- Leaves a human review step before the campaign is used
- Reduces the chance of copy and asset errors when rebuilding campaigns

### Cost Savings

- **Time reclaimed:** 6 hrs/month = £150/month = **£1,800/year** at the MOCC's illustrative £25/hour rate
- **Secondary benefit:** Campaign builds follow the same sequence and review process

## Version History

| Version | Date | Milestone |
| --- | --- | --- |
| 1.0 | July 2026 | Initial live version: clones email, landing page and workflow templates, updates with provided assets, and creates new campaign |
| 1.1 | September 2026 | Build time reduced and test email send added |

## Design Insights

The same HubSpot actions used for campaign reporting can also create and update campaign assets. Keeping the process in one workflow avoids separate manual steps for each asset type, while the human check remains part of the handover.

---

## Explore Other MOCC Modules

- [Clarity Website Analyst](../Clarity%20Website%20Analyst/Clarity-Website-Analyst.html)
- [Email QA Agent](../Email%20QA%20Agent/Email-QA-Agent.html)
- [Website QA Agent](../Website%20QA%20Agent/Website-QA-Agent.html)
- [Data Import Agent](../Data%20Import%20Agent/Data-Import-Agent.html)
- [Agent Intake & Approval Agent](../Agent%20Intake%20%26%20Approval%20Agent/Agent-Intake-%26-Approval-Agent.html)
- [CRM Health Agent](../CRM%20Health%20Agent/CRM-Health-Agent.html)
- [Campaign Performance Agent](../Campaign%20Performance%20Agent/Campaign-Performance-Agent.html)
- [Content Agent](../Content%20Agent/Content-Agent.html)
- [WordPress Post Creation Agent](../WordPress%20Post%20Creation%20Agent/WordPress-Post-Creation-Agent.html)
- [Agent Health Monitor](../Agent%20Health%20Monitor/Agent-Health-Monitor.html)
