# Larry Peseckis

**AI / Cloud Security Architect** · DoD Cleared · CISSP Candidate

Security at the intersection of offense, defense, cloud, and AI.

Thirty years of mission-critical systems in defense and aerospace. Now building at the intersection of frontier cyber risk, cloud security architecture, red/blue team operations, and LLM safety. The Integration Thesis: offense, defense, cloud, and AI security are one discipline viewed from different angles. The portfolio here is what happens when those angles start talking to each other.

---

## Current Focus

- Frontier cyber risk evaluation — taxonomies, eval sets, LLM-as-judge reliability, and human-grading comparisons
- AI-assisted cyber request classification and model-policy decision aids
- LLM attack surface mapping and prompt injection corpus analysis
- Cloud security architecture and DevSecOps security controls
- Red/blue/purple team practice documented as reusable detection engineering

---

## Flagship Work

### [frontier-cyber-risk-taxonomy](https://github.com/larrypeseckis/frontier-cyber-risk-taxonomy)
A four-tier model-policy taxonomy for AI-assisted cyber requests, mapping uplift, autonomy, authorization verifiability, and cumulative capability transfer. Built as a decision aid for evaluators, red teams, and policy reviewers. Aligned with cross-framework thinking from the Frontier Model Forum, Microsoft's capability tiers, OpenAI's Preparedness Framework, and the forming regulatory landscape.

### [frontier-cyber-risk-eval](https://github.com/larrypeseckis/frontier-cyber-risk-eval)
A 57-prompt labeled eval set operationalizing the taxonomy. Spans allowed, dual-use, high-risk, and disallowed tiers with over-refusal traps, boundary cases, multi-turn assembly tests, and a scorer harness comparing LLM-as-judge verdicts with blind human grading. Pilot finding: zero measured over-refusal on the set; LLM judge abstained on the four most severe Tier 4 prompts — a coverage failure in single-judge evaluation.

### [safety-router-transparency](https://github.com/larrypeseckis/safety-router-transparency)
A five-lane model for how a safety router should explain a reroute to a benign user without handing the trigger to an attacker. Core finding: disclosure granularity should track inverse oracle risk. Only the restricted-content lane earns strong redaction — and hiding it isn't enough unless content firing is observationally equivalent to it not firing.

### [attck-pulse](https://github.com/larrypeseckis/attck-pulse)
A confidence-aware Python/Postgres pipeline extracting MITRE ATT&CK technique mentions from CISA and DFIR Report threat intelligence for trend analysis. Wilson confidence intervals for honest precision reporting. First finding: cross-source citation patterns reveal the vantage point of the reporting organization as much as they reveal adversary behavior.

### [burp-cc-bridge](https://github.com/larrypeseckis/burp-cc-bridge)
A Burp Suite Community Edition extension that exposes Burp's HTTP capabilities as a localhost REST API, closing the $475/year gap between Community and Professional for practitioners who need scripted automation. Validated across 7 PortSwigger Web Security Academy labs, 250 bridge calls, zero GUI fallbacks.

### [ctf-rooms](https://github.com/larrypeseckis/ctf-rooms)
300+ documented red team, blue team, cloud, DFIR, and LLM security labs with attack chains, detection engineering, and lessons learned. Spans TryHackMe, HackTheBox, and LetsDefend. The habit that made the CJCA report possible.

---

## Credentials

Current Certifications: CompTIA: SecurityX | SecAI+ | PenTest+ | CySA+ | Security+ | Cloud+ | Network+ | Server+ | A+ (Core 1 & 2 both passed) | Project+. ISC2: Certified in Cybersecurity (CC) | SSCP. Linux: LPIC-1. TryHackMe: SEC1 | PT1 | SAL1 | AI1. HackTheBox: CJCA | COAE. Other: CFR-410 | ITIL 4. In progress: CISSP (exam scheduled July 2026).

Currently enrolled in WGU BS in Cybersecurity and Information Assurance.
---

## Find Me

[larrypeseckis.ai](https://larrypeseckis.ai) · [LinkedIn](https://www.linkedin.com/in/larry-peseckis/) · [Frontier Cyber Risk Taxonomy](https://larrypeseckis.ai/taxonomy/)
