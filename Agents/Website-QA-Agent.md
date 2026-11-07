# Website QA Agent

Key Result: 40% reduction in manual review effort
Layer: Control
Problem: Pre-Launch Errors
Status: Live

[🏠 Home](../../Home%20410cf2872cd3818384f7d46e2a3815c2.md) · [🧩 Agent Registry](../Agent%20Registry%20394cf2872cd3810fa4f5f95f8f125cf0.md) · [📈 Results](../Results%20394cf2872cd38181903de57b1f1a312a.md) · [🗺️ Roadmap](../Roadmap%20394cf2872cd381d58a13d7ca2136edc4.md) · [💼 Campaign & Commercial Projects](../Campaign%20&%20Commercial%20Projects%2039bcf2872cd38176b899cdeca23f2267.md) · [👥 Leadership & Strategy](../Leadership%20&%20Strategy%20395cf2872cd381a1a5c8e11299862f40.md) · [🔧 How to Build MOCC](../How%20to%20Build%20MOCC%20410cf2872cd381b3b585fd01db7e5b66.md) · 

---

**Layer:** 🛡️ Control — Quality Assurance  

**Status:** 🟢 Live  

**Platform:** Microsoft Copilot Studio · Power Automate · Microsoft Teams · Website/CMS  

**Deployment:** Veriforce — 5 brands  

**Last updated:** July 2026  

**Version:** 1.2  

## Business Problem

Website quality assurance relied on manual review prior to publication, with no consistent checklist or audit trail. Errors such as broken links, missing metadata, accessibility issues and inconsistent branding could easily be overlooked, resulting in avoidable defects reaching production.

The objective was to create a repeatable website QA process that improves consistency, reduces manual effort and provides a documented record of every review.

## Solution Overview

The Website QA Agent analyses webpages prior to publication. When a website change reaches the QA stage in ClickUp, Power Automate automatically triggers the agent, which evaluates the page against a defined quality framework covering accessibility, branding, SEO fundamentals, content quality, links, imagery and user experience.

The completed QA report, including an overall score and grade, is automatically published to Microsoft Teams and stored within SharePoint as an audit history to provide a central governance record.

![Flow_WebsiteQA.svg](Website%20QA%20Agent/Flow_WebsiteQA.svg)

## Business Value

- Reduced manual review effort by approximately **40%**
- Standardised website QA across all published content
- Reduced publishing errors prior to release
- Improved consistency of branding and content quality
- Created a central audit trail for website quality reviews

*Methodology: based on 4 weeks of before/after data. Prior process averaged ~10 hours/month (2 reviewers).*

### Cost Savings

- **Time reclaimed:** 6 hrs/month per brand = 30 hrs/month across 5 brands = £3,000/month = **£36,000/year**
- **Error prevention:** Avoids costly brand mistakes and SEO gaps
- **Secondary benefit:** Website Manager freed from routine checking; can focus on strategy

## Version History

| Version | Date | Milestone |
| --- | --- | --- |
| v1.0 | May 2026 | Initial website review using manual URL submission |
| v1.1 | June 2026 | Expanded review framework covering accessibility, branding and SEO |
| v1.2 | July 2026 | Automated reporting to Teams and SharePoint governance log |

## Design Insights

The greatest improvements came from creating a consistent review framework.

By standardising how every webpage is assessed, the Website QA Agent provides repeatable quality assurance while reducing reliance on individual reviewer knowledge. Recording every review also creates valuable governance data that can be used to identify recurring issues and continuously improve website standards.

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