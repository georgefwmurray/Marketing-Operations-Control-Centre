# Agent Intake & Approval Agent

Key Result: Every request logged and approved before build
Layer: Governance
Problem: Uncoordinated agent requests and overlapping builds
Status: Live

[Home](index.md) • [Agent Registry](Agent-Registry.md) • [Results](Results.md) • [Roadmap](Roadmap.md) • [Campaign & Commercial Projects](Campaign-Commercial-Projects.md) • [Leadership & Strategy](Leadership-&-Strategy.md) • [How to Build MOCC](How-to-Build.md)

---

**Layer:** ⚙️ Governance  

**Status:** 🟢Live

**Platform:** Microsoft Copilot Studio • Microsoft Teams • SharePoint

**Deployment:** Veriforce — all agent requests  

**Last updated:** October 2026  

## Business Problem

As the number of agents grew, there was no consistent way to capture what a new agent was meant to solve, who had approved it, or how it worked. Requests came in informally, and documentation, where it existed, was written after the build. That made ownership, risk review and long-term visibility harder to maintain.

Functionality was also being built that overlapped with existing agents and tools in the stack.

## Solution Overview

![Flow_AgentIntake.svg](Agent%20Intake%20&%20Approval%20Agent/Flow_AgentIntake.svg)

The Agent Intake & Approval Agent is a Copilot Studio topic embedded in Teams. It asks the requester structured questions about what the agent helps solve, what it outputs and how it works, and tidies the answers into a single request. Every request is logged on a SharePoint list. The agent then produces a report for the approvers showing any potential crossover with existing agents and existing tech stack functionality. The request and report go to the Head of Digital Marketing Operations and the Head of Digital Performance for approval before any build. Approved requests are logged on an approved list, and the agent then creates the agent's documentation so its setup and workings stay visible over the long term.

## Business Value

- Every agent request is logged on a SharePoint list, giving a full record of what was asked for
- No agent is built without approval from two Heads
- Approvers see potential overlap with existing agents and stack functionality before any build starts
- Approved agents get documentation created by the agent, so setup and workings stay visible long term
- Requests and approvals sit on separate lists, giving a clear audit trail from request to approval

### Cost Savings

- **Prevented rework:** ~20% of pre-system requests were duplicates = est. 40 hrs prevented = **£4,800/year**
- **Governance value:** Every build is intentional + tracked; easy to audit for compliance

## Design Insights

Approval happens before build, so overlap with existing agents and tools is caught before any time is spent building.

---

## Explore Other MOCC Modules

- [Clarity Website Analyst](Clarity%20Website%20Analyst%203edcf2872cd381f9b5cadf69beff0f07.md)
- [Email QA Agent](Email%20QA%20Agent%20394cf2872cd3812eb679f7657980d7b4.md)
- [Website QA Agent](Website%20QA%20Agent%20394cf2872cd381528052cb21608d6db0.md)
- [Data Import Agent](Data%20Import%20Agent%20394cf2872cd381319d4eee4a7bb3dbb0.md)
- [CRM Health Agent](CRM%20Health%20Agent%20396cf2872cd381598482c6978e3a2389.md)
- [Campaign Performance Agent](Campaign%20Performance%20Agent%20394cf2872cd38132b545cd1e773d04ef.md)
- [Campaign Build Agent](Campaign%20Build%20Agent%203accf2872cd381fd85feda9dc5153487.md)
- [Content Agent](Content%20Agent%203e8cf2872cd3819f8769ece6c9198c23.md)
- [WordPress Post Creation Agent](WordPress%20Post%20Creation%20Agent%203e8cf2872cd381e98c4adb092f4696fd.md)
- [Agent Health Monitor](Agent%20Health%20Monitor%20410cf2872cd3814a913bcabfac55638e.md)
