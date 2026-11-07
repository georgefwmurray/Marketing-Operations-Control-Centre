# WordPress Post Creation Agent

Key Result: 20 hours/month saved via automation
Layer: Production
Problem: Manual WordPress Post Creation
Status: Live

[🏠 Home](../../Home%20410cf2872cd3818384f7d46e2a3815c2.md) · [Agent Registry](../Agent%20Registry%20394cf2872cd3810fa4f5f95f8f125cf0.md) · [Results](../Results%20394cf2872cd38181903de57b1f1a312a.md) · [Roadmap](../Roadmap%20394cf2872cd381d58a13d7ca2136edc4.md) · [Campaign & Commercial Projects](../Campaign%20&%20Commercial%20Projects%2039bcf2872cd38176b899cdeca23f2267.md) · [👥 Leadership & Strategy](../Leadership%20&%20Strategy%20395cf2872cd381a1a5c8e11299862f40.md) · [🔧 How to Build MOCC](../How%20to%20Build%20MOCC%20410cf2872cd381b3b585fd01db7e5b66.md) · 

---

**Layer:** 🏗️ Production — Publishing Delivery  

**Status:** 🟢 Live  

**Platform:** WordPress (five brand sites) · Power Automate · SharePoint · ClickUp  

**Deployment:** Veriforce — live on 5 brands  

**Last updated:** October 2026  

**Version:** 1.1

## Business Problem

Creating WordPress posts from finished HTML content was a manual task, requiring careful checking to publish to the correct brand site across a five-website estate. This carried a risk of content landing on the wrong website and added a recurring block of manual effort every month.

## Solution Overview

The WordPress Post Creation Agent takes HTML output (including content produced by the Content Agent) and creates the corresponding post in WordPress. The agent is triggered when the Content Agent saves a document to SharePoint. Power Automate parses the HTML and posts it to the correct brand website based on the blog metadata, saving it as a draft in WordPress. A ClickUp ticket is then created for the Web team to review and publish. The agent is live across all 5 brand websites.

![Flow_WordPress.svg](WordPress%20Post%20Creation%20Agent/Flow_WordPress.svg)

## Business Value

- Removed manual WordPress post creation from the content pipeline
- Automated brand/site identification, reducing risk of publishing to the wrong website
- Retained a human review and publish step via a ClickUp ticket to the Web team
- Saved approximately **20 hours per month**
- Completes the automated pipeline from brief through to publish-ready WordPress post

### Cost Savings

- **Time reclaimed:** 20 hrs/month = **£24,000/year**
- **Secondary benefit:** Developers freed from routine posting work; can focus on feature development

## Version History

| Version | Date | Milestone |
| --- | --- | --- |
| v1.0 | September 2026 | HTML ingestion, brand identification and ClickUp review ticket live (1 brand test) |
| v1.1 | October 2026 | Rolled out across all 5 brand websites |

## Design Insights

Automating brand identification removed the most error-prone step in the manual process, while keeping a human review and publish gate via ClickUp preserved editorial and quality control.

Pairing this agent with the Content Agent created an end-to-end pipeline from brief to publish-ready post, with human sign-off retained at both the drafting and publishing stages.

---

## Explore Other MOCC Modules

- [Agent Intake & Approval Agent](Agent%20Intake%20&%20Approval%20Agent%20400cf2872cd381728db6cbc4d10a867e.md)
- [Campaign Build Agent](Campaign%20Build%20Agent%203accf2872cd381fd85feda9dc5153487.md)
- [Content Agent](Content%20Agent%203e8cf2872cd3819f8769ece6c9198c23.md)
- [Clarity Website Analyst](Clarity%20Website%20Analyst%203edcf2872cd381f9b5cadf69beff0f07.md)
- [Email QA Agent](Email%20QA%20Agent%20394cf2872cd3812eb679f7657980d7b4.md)
- [Website QA Agent](Website%20QA%20Agent%20394cf2872cd381528052cb21608d6db0.md)
- [Data Import Agent](Data%20Import%20Agent%20394cf2872cd381319d4eee4a7bb3dbb0.md)
- [CRM Health Agent](CRM%20Health%20Agent%20396cf2872cd381598482c6978e3a2389.md)
- [Campaign Performance Agent](Campaign%20Performance%20Agent%20394cf2872cd38132b545cd1e773d04ef.md)
- [Agent Health Monitor](Agent%20Health%20Monitor%20410cf2872cd3814a913bcabfac55638e.md)