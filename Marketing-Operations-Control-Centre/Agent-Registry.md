# Agent Registry

[Home](../Home%20410cf2872cd3818384f7d46e2a3815c2.md) · [Agent Registry](Agent%20Registry%20394cf2872cd3810fa4f5f95f8f125cf0.md) · [Results](Results%20394cf2872cd38181903de57b1f1a312a.md) · [Roadmap](Roadmap%20394cf2872cd381d58a13d7ca2136edc4.md) · [Campaign & Commercial Projects](Campaign%20&%20Commercial%20Projects%2039bcf2872cd38176b899cdeca23f2267.md) · [Leadership & Strategy](Leadership%20&%20Strategy%20395cf2872cd381a1a5c8e11299862f40.md) · [How to Build MOCC](How%20to%20Build%20MOCC%20410cf2872cd381b3b585fd01db7e5b66.md) · 

---

A registry of 11 HubSpot marketing operations agents built by George Murray to automate intake, quality assurance, campaign delivery, data standardization, performance insight, and governance across marketing operations workflows. Each agent below has its own page with full detail — open the sub-pages to expand. Every live agent has a named owner (by role), a risk tier and a next review date.

This registry demonstrates a complete marketing operations automation framework: the agents are organized by layer (Control, Production, Data, Intelligence, Governance, Knowledge), each layer owns one piece of the marketing operations workflow, and every agent is auditable and governed.

**Registry & governance owner:** Marketing Automation Manager

## 🛡️ Control Layer — Quality Assurance

- [**Email QA Agent**](Agents/Email%20QA%20Agent%20394cf2872cd3812eb679f7657980d7b4.md)  🟢 Live · v1.3 · 5 brands
    
    *Checks every email against a set checklist before send, posts findings to a Teams channel and records them in an audit log for a full audit trail.*
    
    **Owner:** Marketing Automation Executive · **Risk:** Low · **Next review:** April 2027
    
- [**Website QA Agent**](Agents/Website%20QA%20Agent%20394cf2872cd381528052cb21608d6db0.md)  🟢 Live · v1.2 · 5 brands
    
    *Checks all website content, including metadata, against a checklist, sends a score and grade to Teams and keeps an audit history in SharePoint.*
    
    **Owner:** Website Manager · **Risk:** Low · **Next review:** April 2027
    

## 🏗️ Production Layer — Content & Campaign Delivery

- [**Campaign Build Agent**](Agents/Campaign%20Build%20Agent%203accf2872cd381fd85feda9dc5153487.md)  🟢 Live · v1.1 · 1 brand
    
    *Uses a Claude Skill to recreate onboarding campaigns (email, landing page, workflow) following a strict process: 10 minutes of agent time plus 20 minutes of human QA, versus 90 minutes manually, saving 60 minutes per campaign.*
    
    **Owner:** Marketing Automation Executive · **Risk:** High · **Next review:** January 2027
    
- [**Content Agent**](Agents/Content%20Agent%203e8cf2872cd3819f8769ece6c9198c23.md)  🟢 Live · v1.2 · 5 brands
    
    *Turns a brief into full blog content following brand guidelines and sends it for approval. Once approved, Copilot Studio converts it to HTML with metadata and saves it to SharePoint. Reduced agency spend from £20k to £10k a month.*
    
    **Owner:** Marketing Automation Manager · **Risk:** Medium · **Next review:** April 2027
    

- [**WordPress Post Creation Agent**](Agents/WordPress%20Post%20Creation%20Agent%203e8cf2872cd381e98c4adb092f4696fd.md)  🟢 Live · v1.1 · 5 brands
    
    *Triggered when the Content Agent saves to SharePoint. Power Automate parses the HTML and posts it to the correct website based on blog metadata as a draft, then raises a ClickUp ticket for the Web team to review and publish. Saves 20 hours a month.*
    
    **Owner:** Website Manager · **Risk:** High · **Next review:** January 2027
    

## 🗄️ Data Layer — Data Operations

- [**Data Import Agent**](Agents/Data%20Import%20Agent%20394cf2872cd381319d4eee4a7bb3dbb0.md)  🟢 Live · v1.4 · All brands
    
    *Automates extraction of 13 reports a week and data standardisation for HubSpot ingestion, then reports import numbers and email send volumes to key stakeholders via Teams. Saves 15 hours a month.*
    
    **Owner:** Digital Operations Executive · **Risk:** High · **Next review:** January 2027
    

## 📈 Intelligence Layer — Performance Insight

- [**Campaign Performance Agent**](Agents/Campaign%20Performance%20Agent%20394cf2872cd38132b545cd1e773d04ef.md)  🟢 Live · v2.0 · 5 brands
    
    *Weekly email report on campaigns started in the last 50 days plus always-on campaigns, showing engagement trends and revenue attributed, with A/B test suggestions for campaign owners.*
    
    **Owner:** Marketing Automation Executive · **Risk:** Low · **Next review:** April 2027
    
- [**Clarity Website Analyst**](Agents/Clarity%20Website%20Analyst%203edcf2872cd381f9b5cadf69beff0f07.md)  🟢 Live · v1.0 · 5 brands
    
    *Data-led insight into website UX. Collects Microsoft Clarity behaviour metrics for every URL each morning into a SharePoint list, building a history beyond Clarity's 3-day limit. A Website Health agent delivers 90-day rolling trends and flags anomalies in a weekly report, and a UX Analyst agent suggests data-led A/B CRO tests from page performance.*
    
    **Owner:** Website Executive · **Risk:** Low · **Next review:** April 2027
    

## 📚 Knowledge Layer — System Memory

*In planning. Agent documentation is currently generated by the Agent Intake & Approval Agent; no dedicated Knowledge agents are live yet.*

## ⚙️ Governance Layer — Automation Oversight

- [**Agent Intake & Approval Agent**](Agents/Agent%20Intake%20&%20Approval%20Agent%20400cf2872cd381728db6cbc4d10a867e.md)  🟢 Live
    
    *Captures every agent request through a Copilot Studio topic in Teams, checks it for overlap with existing agents and tools, logs it on SharePoint and sends it to two Heads for approval before any build. Once approved, the agent creates the agent's documentation.*
    
    **Owner:** Marketing Automation Manager · **Risk:** Low · **Next review:** April 2027
    
- [**CRM Health Agent**](Agents/CRM%20Health%20Agent%20396cf2872cd381598482c6978e3a2389.md)  🟢 Live · v1.0 · 5 brands
    
    *A monthly Claude Skill that evaluates workflows, emails, forms and landing pages with no activity in the past 12 months and flags a list of each asset for human archive approval. Brings workflow, email and forms governance together under one agent.*
    
    **Owner:** Head of Digital Operations · **Risk:** High · **Next review:** November 2026
    
- [**Agent Health Monitor**](Agents/Agent%20Health%20Monitor%20410cf2872cd3814a913bcabfac55638e.md)  🟢 Live · v1.0 · All brands
    
    *Monitors every live agent run once it has passed testing and pilot, flagging failures (including silent failures on scheduled runs) to the Digital Operations team. Sends a daily Outlook report on the previous day's runs, alerts the team when an agent is due a review and tracks usage across agents.*
    
    **Owner:** Head of Digital Operations · **Risk:** Low · **Next review:** December 2026