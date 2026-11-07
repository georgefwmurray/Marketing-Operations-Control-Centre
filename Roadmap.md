# Roadmap

[Home](index.md) • [Agent Registry](Agent-Registry.md) • [Results](Results.md) • [Roadmap](Roadmap.md) • [Campaign & Commercial Projects](Campaign-Commercial-Projects.md) • [Leadership & Strategy](Leadership-&-Strategy.md) • [How to Build MOCC](How-to-Build.md)

---

## HubSpot Marketing Operations Roadmap — What's Being Built Next

This roadmap, built by George Murray, shows how HubSpot marketing operations evolves from manual workflows to fully automated, governed agent systems that deliver measurable ROI. Every item is grounded in production workflows George has architected and deployed.

- [x]  Clarity Website Analyst: daily Clarity ingestion, Website Health report and UX Analyst (live, v1.0, 5 brands)
- [x]  Agent Intake & Approval Agent: structured agent requests in Teams, overlap report, two-Head approval before build and generated documentation (live)
- [ ]  Database Reactivation Agent: re-engage disengaged contacts per brand to drive lead creation (brainstorm stage)
- [ ]  Chain Campaign Build Agent output through the Email QA and Website QA agents
- [x]  CRM Health Agent: monthly review of workflows, emails, forms and landing pages with no activity in 12 months, flagged for human archive approval (live, v1.0, 5 brands)
- [x]  Agent Health Monitor: monitors every live agent run, flags failures (including silent failures on scheduled runs) to Digital Operations, sends a daily Outlook run report and alerts on upcoming agent reviews (live, v1.0, all brands)
- [ ]  Full workflow dependency mapping
- [ ]  Cross-system governance reporting
- [ ]  AI-driven recommendations engine

---

## Per-Agent Roadmap

### Live & Ongoing Agents — Planned Next Iterations

**Email QA Agent**

- v1.4: automatic escalation/re-review flagging for failed QA checks
- v1.5: rolling pass-rate metric feeding into the Results page

**Website QA Agent**

- v1.3: historical trend reporting on recurring website issues

**Data Import Agent**

- Extend coverage beyond the current 13 reports a week to further repetitive import processes
- v1.5: Migration from file-based imports to direct CRM upsert APIs

**Campaign Performance Agent**

- v2.1: expand A/B test suggestion logic with historical win-rate tracking
- v2.2: automated trend alerts pushed to Teams

**Campaign Build Agent**

- Continue refining the Claude Skill and push builds through the Email QA and Website QA agents
- Extend cloning support to additional asset types
- Confirm and track monthly campaign volume to fold time savings into aggregate Results figures

**Clarity Website Analyst**

- Live at v1.0 across 5 brands: daily pull of the previous day's Clarity metrics into a SharePoint list, one record per URL
- Website Health agent: weekly report with 90-day rolling trends, flagging anomalies such as click spikes and traffic drops on key pages
- UX Analyst agent: data-led A/B CRO test ideas based on page performance and 90-day trends
