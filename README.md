<!-- FIELD CONSOLE / Larry Peseckis
Self-contained artwork in assets/. No badge service, JavaScript, or workflow required.
Console motion is a short decorative sequence, not live telemetry.
Content review: 2026-09-10. See SETUP.md for installation and maintenance.
-->

<picture>
  <source media="(prefers-color-scheme: dark) and (max-width: 620px)" srcset="assets/console-dark-mobile.svg">
  <source media="(prefers-color-scheme: dark)" srcset="assets/console-dark.svg">
  <source media="(max-width: 620px)" srcset="assets/console-light-mobile.svg">
  <img src="assets/console-light.svg" alt="Larry Peseckis — AI and Cloud Security Architect. Capability is not authority. Success is not proof. A proposed action must cross an authority boundary before consequence. Conceptual schematic, not telemetry." width="100%">
</picture>

<p align="center">
  <a href="#building"><b>BUILDING</b></a> &nbsp; / &nbsp;
  <a href="#testing"><b>TESTING</b></a> &nbsp; / &nbsp;
  <a href="#writing"><b>WRITING</b></a> &nbsp; / &nbsp;
  <a href="#teaching"><b>TEACHING</b></a> &nbsp; / &nbsp;
  <a href="#researching"><b>RESEARCHING</b></a>
</p>

I work at the intersection of **offensive security, cloud architecture, and AI risk**. Thirty years of mission-critical defense and aerospace systems shaped the question behind this work:

> **When the machine can act, what makes the action authorized—and what evidence shows that the boundary held?**

This is my public workbench. Tools, test fixtures, research, field notes, and explanations that make complicated systems easier to reason about.

## Building

`01 / TOOLS + FIXTURES`  
**Make the mechanism inspectable.**

<p>
<a href="https://github.com/larrypeseckis/burp-cc-bridge">
<picture>
  <source media="(prefers-color-scheme: dark) and (max-width: 620px)" srcset="assets/burp-dark-mobile.svg">
  <source media="(prefers-color-scheme: dark)" srcset="assets/burp-dark.svg">
  <source media="(max-width: 620px)" srcset="assets/burp-light-mobile.svg">
  <img src="assets/burp-light.svg" alt="Burp CC Bridge — a localhost REST API for repeatable, authorized web-security lab workflows. Java." width="49%">
</picture>
</a>
<a href="https://github.com/larrypeseckis/attck-pulse">
<picture>
  <source media="(prefers-color-scheme: dark) and (max-width: 620px)" srcset="assets/pulse-dark-mobile.svg">
  <source media="(prefers-color-scheme: dark)" srcset="assets/pulse-dark.svg">
  <source media="(max-width: 620px)" srcset="assets/pulse-light-mobile.svg">
  <img src="assets/pulse-light.svg" alt="ATT&amp;CK Pulse — public threat reporting turned into queryable trend evidence. Python and PostgreSQL." width="49%">
</picture>
</a>
</p>

<details>
<summary><b>Open build notes</b> — what these systems actually do</summary>

**[Burp CC Bridge](https://github.com/larrypeseckis/burp-cc-bridge)** exposes Burp Suite Community Edition's HTTP capabilities through a local REST API for scripted, authorized testing.

**[ATT&CK Pulse](https://github.com/larrypeseckis/attck-pulse)** extracts MITRE ATT&CK technique references from public threat intelligence into a queryable dataset. Reporting patterns are not the same thing as adversary prevalence.

The working surface: cloud infrastructure, Linux, identity, containers, infrastructure as code, delivery pipelines, and observability. The point is the control that actually runs—not the box on the architecture slide.

</details>

## Testing

`02 / AUTHORITY BOUNDARIES`  
**Test the assumption, not just the happy path.**

<p>
<a href="https://github.com/larrypeseckis/agentic-browser-boundary-tests">
<picture>
  <source media="(prefers-color-scheme: dark) and (max-width: 620px)" srcset="assets/boundary-dark-mobile.svg">
  <source media="(prefers-color-scheme: dark)" srcset="assets/boundary-dark.svg">
  <source media="(max-width: 620px)" srcset="assets/boundary-light-mobile.svg">
  <img src="assets/boundary-light.svg" alt="Agentic Browser Boundary Tests — benign local scenarios, inert canaries, and evidence logs for scoped-authorization boundaries." width="49%">
</picture>
</a>
<a href="https://github.com/larrypeseckis/frontier-cyber-risk-eval">
<picture>
  <source media="(prefers-color-scheme: dark) and (max-width: 620px)" srcset="assets/eval-dark-mobile.svg">
  <source media="(prefers-color-scheme: dark)" srcset="assets/eval-dark.svg">
  <source media="(max-width: 620px)" srcset="assets/eval-light-mobile.svg">
  <img src="assets/eval-light.svg" alt="Frontier Cyber Risk Evaluation — labeled cyber-assistance prompts, an automated judge, and blind human comparison." width="49%">
</picture>
</a>
</p>

<details>
<summary><b>Open test notes</b> — scope, evidence, and failure modes</summary>

**[Agentic Browser Boundary Tests](https://github.com/larrypeseckis/agentic-browser-boundary-tests)** asks whether webpage content can cause an agent to cross a boundary that only the user should authorize. Six local scenarios cover hidden instructions, game framing, cross-page retrieval, scoped authorization, read-versus-submit grants, and incremental scope creep. Inert canaries. Local evidence. Per-test findings—not a universal safety verdict.

**[Frontier Cyber Risk Eval](https://github.com/larrypeseckis/frontier-cyber-risk-eval)** pairs a labeled evaluation set with an automated judge and a blind human-comparison harness. A high agreement score does not settle whether the judge covered the difficult cases.

**[Field lab archive](https://github.com/larrypeseckis/ctf-rooms)** connects offensive and defensive practice through documented attack chains, detection opportunities, and lessons learned.

</details>

## Writing

`03 / FIELD NOTES`  
**The interesting failure is often the one that looks like success.**

| Field note | Question under examination |
| :--- | :--- |
| **[The Signature Was Valid. The Authority Wasn't.](https://larrypeseckis.ai/the-signature-was-valid/)** | Who said “go” is not the same question as who was allowed to. |
| **[The Human Approved It. Which “It”?](https://larrypeseckis.ai/the-human-approved-it/)** | Does the approval still bind to the action that actually executes? |
| **[The Tool Was Read-Only. The Consequence Wasn't.](https://larrypeseckis.ai/the-tool-was-read-only/)** | Is the safety property enforced—or merely attached to a name? |

[**Open the writing archive →**](https://larrypeseckis.ai/#writing)

## Teaching

`04 / CLEAR MENTAL MODELS`  
**If the explanation cannot survive a curious kid, keep working on it.**

<a href="https://robotexplains.ai/">
<picture>
  <source media="(prefers-color-scheme: dark) and (max-width: 620px)" srcset="assets/teaching-dark-mobile.svg">
  <source media="(prefers-color-scheme: dark)" srcset="assets/teaching-dark.svg">
  <source media="(max-width: 620px)" srcset="assets/teaching-light-mobile.svg">
  <img src="assets/teaching-light.svg" alt="Robot Explains — comic-style lessons and games about computers, cybersecurity, and AI for kids, parents, teachers, and curious humans." width="100%">
</picture>
</a>

**[Robot Explains](https://robotexplains.ai/)** turns web, cybersecurity, and AI concepts into illustrated explanations, guided learning, and games. What is it? Why does it matter? How do I use it safely?

<details>
<summary><b>Open the side channel</b> — sometimes the explanation is satire</summary>

**[Bigger Sandbox](https://biggersandbox.ai/)** — Containment, but bigger this time.

**[Privacy™](https://privacyisnotathinganymore.ai/)** — Search anyone. Know everything. Be wrong at scale.

Satirical sites about containment theater and surveillance overconfidence. The joke is the interface. The subject is the assumption underneath it.

</details>

## Researching

`05 / FORMAL QUESTIONS`  
**Keep separate questions separate. Make the relationships explicit.**

<a href="https://github.com/larrypeseckis/micrm">
<picture>
  <source media="(prefers-color-scheme: dark) and (max-width: 620px)" srcset="assets/research-dark-mobile.svg">
  <source media="(prefers-color-scheme: dark)" srcset="assets/research-dark.svg">
  <source media="(max-width: 620px)" srcset="assets/research-light-mobile.svg">
  <img src="assets/research-light.svg" alt="MICRM — Machine-Initiated Consequence Reference Model. Distinguishes consequence structure, authority and accountability closure, contribution-sensitive candidacy, and evidentiary warrant. Formal research with explicit limitations." width="100%">
</picture>
</a>

**[MICRM](https://github.com/larrypeseckis/micrm)** is a formal reference model for machine-initiated consequence attribution. It distinguishes consequence structure, authority and accountability closure, contribution-sensitive candidacy, and evidentiary warrant rather than silently substituting one for another.

**Scope matters:** this is a reference model with stated limits—not a completed theory or a universally validated, substrate-neutral framework.

<details>
<summary><b>Open the research index</b> — adjacent models and control questions</summary>

**[Frontier Cyber Risk Taxonomy](https://github.com/larrypeseckis/frontier-cyber-risk-taxonomy)** — cyber-assistance classification across uplift, autonomy, authorization verifiability, and cumulative capability transfer.

**[Agent Security Threat Model](https://github.com/larrypeseckis/agent-security-threat-model)** — trust boundaries across agents, tools, browsers, files, APIs, and cloud resources.

**[Agent Tool Permission Matrix](https://github.com/larrypeseckis/agent-tool-permission-matrix)** — default-deny grants tied to risks, required controls, and enforcement points.

**[Safety-Router Transparency](https://github.com/larrypeseckis/safety-router-transparency)** — useful explanations without turning disclosure into an oracle for an attacker.

</details>

---

<picture>
  <source media="(prefers-color-scheme: dark) and (max-width: 620px)" srcset="assets/principle-dark-mobile.svg">
  <source media="(prefers-color-scheme: dark)" srcset="assets/principle-dark.svg">
  <source media="(max-width: 620px)" srcset="assets/principle-light-mobile.svg">
  <img src="assets/principle-light.svg" alt="Operating principle: Task success is not system correctness. Build the system. Test the assumption. Keep the evidence." width="100%">
</picture>

<p align="center">
  <a href="https://larrypeseckis.ai/"><b>MAIN SITE</b></a> &nbsp; / &nbsp;
  <a href="https://larrypeseckis.ai/#writing"><b>FIELD NOTES</b></a> &nbsp; / &nbsp;
  <a href="https://robotexplains.ai/"><b>ROBOT EXPLAINS</b></a> &nbsp; / &nbsp;
  <a href="https://www.linkedin.com/in/larry-peseckis/"><b>LINKEDIN</b></a>
</p>

<p align="center"><sub>Independent public work. No employer endorsement implied. Claims travel with their scope, limitations, and evidence.</sub></p>
