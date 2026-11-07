# Content Agent

Key Result: Agency spend cut from £20k to £10k a month
Layer: Production
Problem: Manual Content Briefing & Drafting
Status: Live

[🏠 Home](../../Home%20410cf2872cd3818384f7d46e2a3815c2.md) · [Agent Registry](../Agent%20Registry%20394cf2872cd3810fa4f5f95f8f125cf0.md) · [Results](../Results%20394cf2872cd38181903de57b1f1a312a.md) · [Roadmap](../Roadmap%20394cf2872cd381d58a13d7ca2136edc4.md) · [Campaign & Commercial Projects](../Campaign%20&%20Commercial%20Projects%2039bcf2872cd38176b899cdeca23f2267.md) · [👥 Leadership & Strategy](../Leadership%20&%20Strategy%20395cf2872cd381a1a5c8e11299862f40.md) · [🔧 How to Build MOCC](../How%20to%20Build%20MOCC%20410cf2872cd381b3b585fd01db7e5b66.md) · 

---

**Layer:** 🏗️ Production — Content Delivery  

**Status:** 🟢 Live  

**Platform:** Semrush AEO · Claude · Human Sign-off · Copilot Studio (HTML conversion) · SharePoint  

**Deployment:** Veriforce — 5 brands  

**Last updated:** September 2026  

**Version:** 1.2

## Business Problem

Blog content was briefed and drafted almost entirely through an external agency, at significant recurring cost and with turnaround times dependent on agency capacity. Briefs originated either from a human or from ad-hoc SEO recommendations, with no standardised drafting or metadata process.

The objective was to bring first-draft content production in-house without compromising quality or the human review step needed before publication.

## Solution Overview

The Content Agent is briefed either via Semrush AEO recommendations or directly by a human, taking a blog title and rough brief as input. It produces a full blog draft following brand guidelines, which is sent to a human for review and sign-off. Once approved, Copilot Studio converts the content to HTML, including meta title, meta description and target keyword, and uploads it to SharePoint, ready for the WordPress Post Creation Agent.

![Flow_ContentAgent.svg](Content%20Agent/Flow_ContentAgent.svg)

## Business Value

- Reduced external content agency spend from £20k to £10k a month
- Faster turnaround from brief to review-ready draft
- Standardised, SEO-ready metadata generated automatically
- Preserved human sign-off as a quality gate before publication
- Created a repeatable pipeline feeding directly into the WordPress Post Creation Agent

### Cost Savings

- **Direct agency spend reduction:** £10k/month = **£120,000/year**
- **Time reclaimed:** 24 hrs/month (content QA + coordination) = £2,400/month
- **Secondary benefit:** In-house content capability created; team no longer dependent on external vendor

## Version History

| Version | Date | Milestone |
| --- | --- | --- |
| v1.0 | June 2026 | Initial version: drafts copy for a post from a brief |
| v1.1 | July 2026 | HTML output added |
| v1.2 | September 2026 | Briefing, drafting, human review and HTML/metadata conversion live |

## Design Insights

Keeping the human review and sign-off step intact was key to trust in the output. The agent takes on the drafting and formatting, and editorial control stays with people.

Generating HTML and SEO metadata (title, description, keyword) as part of the same step removed a separate agency task and made the draft immediately ingestion-ready for WordPress.

---

## Explore Other MOCC Modules

- [Agent Intake & Approval Agent](Agent%20Intake%20&%20Approval%20Agent%20400cf2872cd381728db6cbc4d10a867e.md)
- [Campaign Build Agent](Campaign%20Build%20Agent%203accf2872cd381fd85feda9dc5153487.md)
- [WordPress Post Creation Agent](WordPress%20Post%20Creation%20Agent%203e8cf2872cd381e98c4adb092f4696fd.md)
- [Clarity Website Analyst](Clarity%20Website%20Analyst%203edcf2872cd381f9b5cadf69beff0f07.md)
- [Email QA Agent](Email%20QA%20Agent%20394cf2872cd3812eb679f7657980d7b4.md)
- [Website QA Agent](Website%20QA%20Agent%20394cf2872cd381528052cb21608d6db0.md)
- [Data Import Agent](Data%20Import%20Agent%20394cf2872cd381319d4eee4a7bb3dbb0.md)
- [CRM Health Agent](CRM%20Health%20Agent%20396cf2872cd381598482c6978e3a2389.md)
- [Campaign Performance Agent](Campaign%20Performance%20Agent%20394cf2872cd38132b545cd1e773d04ef.md)
- [Agent Health Monitor](Agent%20Health%20Monitor%20410cf2872cd3814a913bcabfac55638e.md)