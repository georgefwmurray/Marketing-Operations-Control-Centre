---
layout: default
title: "Governing AI Agents in Marketing Operations | George Murray"
description: "How I govern AI agents in marketing operations through clear ownership, risk-based controls, human review and lifecycle monitoring."
permalink: /insights/governing-ai-agents-marketing-operations/
---

<section class="page-hero">
  <p class="eyebrow">Marketing operations · AI governance</p>
  <h1>Governing AI agents in marketing operations</h1>
  <p class="page-lead">An agent is not production-ready simply because its workflow runs. It needs an owner, a defined purpose, controls that match its risk and a way to review whether it is still doing the right job.</p>
  <div class="hero-tags"><span>AI governance</span><span>Marketing operations</span><span>Human oversight</span></div>
  <p class="article-meta">George Murray · Marketing operations and AI governance</p>
</section>

<section class="content-section prose">
  <h2>Start with the process, not the model</h2>
  <p>The useful starting point is a repeatable business process with a clear problem. In my team that meant checking email builds against a checklist, preparing recurring reports for import and building campaigns from approved templates. Before choosing a tool, I define what the process should achieve, who owns the outcome, what information it can use and what must stay a human decision.</p>

  <h2>Give every agent an accountable owner</h2>
  <p>Every agent has two named owners. The requester is normally the business owner, accountable for the agent's purpose and continued relevance. A technical owner, usually a member of my team who supported the build, understands how it works and can help maintain it. Dual ownership reduces reliance on one person and gives the business a continuity route if either owner leaves.</p>
  <p>The registry records each agent's purpose, ownership, status, version, risk tier and next review date.</p>

  <h2>Match controls to the risk</h2>
  <p>Not every agent needs the same control. Email QA reads a build and posts findings to an audit log. That is a different risk from an agent that clones campaign assets or creates posts on a live website.</p>
  <p>I classify each agent as Low, Medium or High risk, then set its review cadence according to the potential consequences and likelihood of failure. The cadence is assigned during acceptance and recorded in the registry; higher-risk agents receive more frequent scrutiny. Each live agent also has a defined failure mode and a rollback path.</p>

  <h2>Keep human review where it matters</h2>
  <p>Human oversight should be designed into the workflow. The CRM Health Agent finds workflows, emails, forms and landing pages with no activity in 12 months, but it only proposes them. A person approves anything that is archived. The Campaign Build Agent has a defined human QA step before anything goes live, and the Content Agent routes every draft for approval.</p>
  <p>Automation can prepare, check and route work. It should not make responsibility disappear.</p>

  <h2>Review the agent through its lifecycle</h2>
  <p>Platforms change, source data shifts and business rules are updated, so a workflow that was useful can quietly become unreliable. The Agent Health Monitor exists for that reason. It watches live agent runs, flags failures including silent failures on scheduled runs, reports usage and prompts reviews when they fall due.</p>
  <p>New ideas go through the same discipline. Every agent request is logged and checked for overlap with existing tools and agents, and nothing is built without approval. The registry holds more than 300 governance records.</p>

  <h2>What I would tell another operations leader</h2>
  <ul>
    <li>Define the owner and the human decision points before you build.</li>
    <li>Set controls by what an error would cost, not by how clever the agent is.</li>
    <li>Monitor for silent failure, not only visible failure.</li>
    <li>Keep a registry, and retire agents that no longer earn their place.</li>
  </ul>
  <p>The aim is not to maximise the number of agents. It is to make useful automation understandable and accountable for the teams who rely on it.</p>
  <p><a href="{{ '/Agent-Registry.html' | relative_url }}">Explore the MOCC Agent Registry</a> or <a href="{{ '/Results.html' | relative_url }}">read how the operational value is assessed</a>.</p>
</section>