---
layout: default
title: "Governing AI Agents in Marketing Operations | George Murray"
description: "A practical approach to ownership, risk, human review and lifecycle governance for AI agents used in marketing operations."
permalink: /insights/governing-ai-agents-marketing-operations/
---

<section class="page-hero">
  <p class="eyebrow">Marketing operations · AI governance</p>
  <h1>Governing AI agents in marketing operations</h1>
  <p class="page-lead">An agent is not production-ready simply because its workflow runs. It needs an owner, a defined purpose, appropriate controls and a way to review whether it is still doing the right job.</p>
  <div class="hero-tags"><span>AI governance</span><span>Marketing operations</span><span>Human oversight</span></div>
</section>

<section class="content-section prose">
  <h2>Start with the process, not the model</h2>
  <p>The useful starting point for an AI agent is a repeatable business process with a clear problem. In marketing operations, that might be checking an email build, preparing data for import, assembling a campaign or monitoring the health of an automation.</p>
  <p>Before choosing a tool, define what the process is meant to achieve, who owns the outcome, what information it can use and what must remain a human decision.</p>

  <h2>Give every agent a defined owner</h2>
  <p>Ownership should be visible in the operating model. The person accountable for a process may not be the person who built the automation. The process owner should understand the expected output, review exceptions and decide when the workflow needs to change or stop.</p>
  <p>A useful agent record should include its purpose, business owner, technical owner where relevant, status, version, connected systems, risk classification and next review date.</p>

  <h2>Match controls to the risk</h2>
  <p>Not every agent needs the same level of control. A read-only check that flags missing metadata is different from an agent that changes CRM records, publishes content or triggers customer communications.</p>
  <p>Controls should reflect the potential impact of an error. Consider the data the agent can access, the actions it can take, whether those actions can be reversed, and who is affected if it gets something wrong.</p>

  <h2>Keep human review where it matters</h2>
  <p>Human oversight should be designed into the workflow rather than added as a vague final instruction. Define which outputs require approval, which exceptions must be escalated and what evidence is retained.</p>
  <p>For customer-facing content and changes to business-critical data, approval and clear accountability remain important. Automation can prepare, check and route work; it should not make responsibility disappear.</p>

  <h2>Review the agent through its lifecycle</h2>
  <p>Agents need maintenance just like other parts of the marketing technology stack. Connected platforms change, source data shifts, business rules are updated and a workflow that was once useful can become unreliable.</p>
  <p>Set review dates, monitor failures and usage, record changes and retire agents that no longer serve a clear purpose. A simple registry makes the portfolio easier to manage than a collection of undocumented flows.</p>

  <h2>Applying this in practice</h2>
  <p>In the Marketing Operations Control Centre (MOCC), I use a six-layer operating model covering Control, Production, Data, Intelligence, Governance and Knowledge. Eleven live agents operate across the first five layers, with the Knowledge layer in planning. The registry records each agent's purpose, owner, status, risk and review date.</p>
  <p>The aim is not to maximise the number of agents. It is to make useful automation understandable, accountable and sustainable for the teams relying on it.</p>
  <p><a href="{{ '/Agent-Registry.html' | relative_url }}">Explore the MOCC Agent Registry</a> or <a href="{{ '/Results.html' | relative_url }}">read how its operational value is assessed</a>.</p>
</section>