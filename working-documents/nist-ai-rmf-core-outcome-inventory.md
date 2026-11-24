# NIST AI RMF 1.0 Core outcome inventory

**Status:** Source-grounded inventory for drafting; not an assessment or checklist  
**Baseline checked:** 24 November 2026  
**Framework baseline:** NIST AI RMF 1.0, NIST AI 100-1 (2023)  
**Current status:** NIST states that AI RMF 1.0 is being revised. The Playbook page says it will be updated after the revised Framework is released.

## Purpose and limits

This inventory records the complete structure of the AI RMF 1.0 Core as a foundation for the repository’s planned application matrix and project assessment record. The short phrases below are navigation summaries of the official outcomes, not replacement wording or a NIST-issued tool. Use the linked Core source for authoritative full outcome text.

This is not a universal checklist. NIST says users may select categories and subcategories according to their needs, resources, and capabilities; functions can be applied in different orders and iteratively. The later project-specific selection must explain inclusion, adaptation, and omission in context. This inventory itself does not assign applicability, maturity, scores, controls, or evidence sufficiency.

## Source baseline and interpretation

| Source | What it anchors | Status checked 24 Nov 2026 |
|---|---|---|
| [NIST AI RMF 1.0 publication, NIST AI 100-1](https://nvlpubs.nist.gov/nistpubs/ai/NIST.AI.100-1.pdf) and [AIRC Core excerpt](https://airc.nist.gov/airmf-resources/airmf/5-sec-core/) | Functions, categories, subcategories, and outcomes | AI RMF 1.0 remains the published baseline; revision in progress |
| [AIRC Profiles excerpt](https://airc.nist.gov/airmf-resources/airmf/6-sec-profile/) | Tailoring outcomes to a specific setting; current and target profiles; gap and action planning | Still describes profiles as flexible; no prescribed profile template |
| [AIRC Playbook](https://airc.nist.gov/airmf-resources/playbook/) | Optional suggested actions associated with Core subcategories | Voluntary; not a checklist or required sequence; update follows the AI RMF revision |

The Core has four functions: **GOVERN**, **MAP**, **MEASURE**, and **MANAGE**. GOVERN is cross-cutting and informs the other three. Risk management is continuous across the AI system lifecycle. Core actions are not a checklist or necessarily an ordered sequence. Profiles provide a way to tailor selected functions, categories, and subcategories to a setting, based on user requirements, risk tolerance, and resources. Comparing current and target profiles can reveal gaps and support prioritized action planning. NIST does not prescribe a profile template.

The Playbook is kept separate from the Core: it offers voluntary, non-exhaustive suggested actions. A future matrix may surface selected suggestions as optional prompts, but must label them as Playbook content rather than Core outcomes or mandatory steps.

## Complete Core structure

The four sections below list every category and subcategory identifier in AI RMF 1.0. Each category description is a concise orientation label. Each subcategory note summarizes the outcome’s subject; see the official Core for its full wording and qualifications.

### GOVERN — organizational foundations, accountability, and oversight

GOVERN is cross-cutting throughout the lifecycle and supports the MAP, MEASURE, and MANAGE functions.

<table>
<thead><tr><th width="15%">Category</th><th width="35%">Category outcome in brief</th><th width="50%">Subcategories and outcome subjects</th></tr></thead>
<tbody>
<tr><td width="15%">GOVERN 1</td><td width="35%">Organization-wide policies, processes, procedures, and practices for AI risk are in place, transparent, and effective.</td><td width="50%"><strong>1.1</strong> Understand, manage, and document applicable legal and regulatory requirements.<br> <strong>1.2</strong> Integrate trustworthy-AI characteristics into organizational practices.<br> <strong>1.3</strong> Set risk-management depth according to organizational risk tolerance.<br> <strong>1.4</strong> Establish a transparent risk-management process aligned to organizational priorities.<br> <strong>1.5</strong> Plan monitoring and periodic review; define roles and review frequency.<br> <strong>1.6</strong> Inventory AI systems and resource them by risk priority.<br> <strong>1.7</strong> Safely decommission or phase out systems without increasing risk or reducing trustworthiness.</td></tr>
<tr><td width="15%">GOVERN 2</td><td width="35%">Appropriate teams and people are empowered, responsible, and trained.</td><td width="50%"><strong>2.1</strong> Document and communicate roles, responsibilities, and lines of communication.<br> <strong>2.2</strong> Train personnel and partners for their AI risk-management duties.<br> <strong>2.3</strong> Executive leadership takes responsibility for AI risk decisions.</td></tr>
<tr><td width="15%">GOVERN 3</td><td width="35%">Workforce diversity, equity, inclusion, and accessibility are prioritized in risk management.</td><td width="50%"><strong>3.1</strong> Use diverse perspectives in lifecycle risk decisions.<br> <strong>3.2</strong> Define and distinguish human-AI roles and oversight responsibilities.</td></tr>
<tr><td width="15%">GOVERN 4</td><td width="35%">Teams support a culture that considers and communicates AI risk.</td><td width="50%"><strong>4.1</strong> Foster critical thinking and a safety-first mindset.<br> <strong>4.2</strong> Document and communicate risks and potential impacts.<br> <strong>4.3</strong> Enable AI testing, incident identification, and information sharing.</td></tr>
<tr><td width="15%">GOVERN 5</td><td width="35%">Robust engagement with relevant AI actors is established.</td><td width="50%"><strong>5.1</strong> Collect, consider, prioritize, and integrate external feedback about impacts.<br> <strong>5.2</strong> Regularly incorporate adjudicated feedback into system design and implementation.</td></tr>
<tr><td width="15%">GOVERN 6</td><td width="35%">Third-party software, data, and supply-chain risks and benefits are addressed.</td><td width="50%"><strong>6.1</strong> Address third-party risks, including intellectual-property and other rights risks.<br> <strong>6.2</strong> Prepare contingency processes for failures or incidents involving high-risk third-party data or AI systems.</td></tr>
</tbody>
</table>

### MAP — context, system, risks, benefits, and impacts

MAP establishes the context for risks and provides information for MEASURE and MANAGE, including an initial decision about whether an AI solution is appropriate.

<table>
<thead><tr><th width="15%">Category</th><th width="35%">Category outcome in brief</th><th width="50%">Subcategories and outcome subjects</th></tr></thead>
<tbody>
<tr><td width="15%">MAP 1</td><td width="35%">Context is established and understood.</td><td width="50%"><strong>1.1</strong> Understand and document purpose, beneficial uses, context-specific law and expectations, deployment settings, affected parties, assumptions, limitations, and related evaluation.<br> <strong>1.2</strong> Document diverse interdisciplinary actors, skills, and participation.<br> <strong>1.3</strong> Understand and document organizational mission and AI goals.<br> <strong>1.4</strong> Define or reassess business value and use context.<br> <strong>1.5</strong> Determine and document organizational risk tolerances.<br> <strong>1.6</strong> Elicit system requirements and consider sociotechnical implications in design.</td></tr>
<tr><td width="15%">MAP 2</td><td width="35%">The AI system is categorized.</td><td width="50%"><strong>2.1</strong> Define the tasks and methods the system supports.<br> <strong>2.2</strong> Document knowledge limits and how outputs may be used and overseen.<br> <strong>2.3</strong> Identify and document scientific-integrity and testing/evaluation/verification/validation considerations.</td></tr>
<tr><td width="15%">MAP 3</td><td width="35%">Capabilities, intended use, goals, benefits, and costs are understood against suitable benchmarks.</td><td width="50%"><strong>3.1</strong> Examine and document potential benefits.<br> <strong>3.2</strong> Examine potential costs, including non-monetary costs associated with errors and trustworthiness.<br> <strong>3.3</strong> Specify application scope based on capability, context, and categorization.<br> <strong>3.4</strong> Define and document operator/practitioner proficiency processes.<br> <strong>3.5</strong> Define and assess human-oversight processes consistent with governance policies.</td></tr>
<tr><td width="15%">MAP 4</td><td width="35%">Risks and benefits are mapped across system components, including third-party software and data.</td><td width="50%"><strong>4.1</strong> Map and document technology, legal, and rights risks across components.<br> <strong>4.2</strong> Identify and document internal risk controls for components, including third-party AI.</td></tr>
<tr><td width="15%">MAP 5</td><td width="35%">Impacts on people, groups, communities, organizations, and society are characterized.</td><td width="50%"><strong>5.1</strong> Identify and document likelihood and magnitude of beneficial and harmful impacts using relevant sources.<br> <strong>5.2</strong> Establish practices and personnel for engagement and feedback on expected and unanticipated impacts.</td></tr>
</tbody>
</table>

### MEASURE — methods, metrics, evaluation, tracking, and feedback

MEASURE uses qualitative, quantitative, or mixed methods to assess and monitor risks and impacts identified through MAP, and informs MANAGE.

<table>
<thead><tr><th width="15%">Category</th><th width="35%">Category outcome in brief</th><th width="50%">Subcategories and outcome subjects</th></tr></thead>
<tbody>
<tr><td width="15%">MEASURE 1</td><td width="35%">Appropriate methods and metrics are identified and applied.</td><td width="50%"><strong>1.1</strong> Select risk metrics, prioritizing significant risks; document what cannot or will not be measured.<br> <strong>1.2</strong> Regularly assess and update metric appropriateness and control effectiveness.<br> <strong>1.3</strong> Involve independent or non-frontline expertise and consult relevant actors as appropriate.</td></tr>
<tr><td width="15%">MEASURE 2</td><td width="35%">Systems are evaluated for trustworthy characteristics.</td><td width="50%"><strong>2.1</strong> Document test sets, metrics, and evaluation tools.<br> <strong>2.2</strong> Ensure human-subject evaluations meet applicable protections and represent relevant populations.<br> <strong>2.3</strong> Measure and document performance or assurance under deployment-like conditions.<br> <strong>2.4</strong> Monitor system and component behavior in production.<br> <strong>2.5</strong> Demonstrate validity and reliability; document generalizability limits.<br> <strong>2.6</strong> Evaluate safety, residual risk, safe failure, and relevant safety metrics.<br> <strong>2.7</strong> Evaluate and document security and resilience.<br> <strong>2.8</strong> Examine transparency and accountability risks.<br> <strong>2.9</strong> Explain, validate, and document the model; interpret outputs in context.<br> <strong>2.10</strong> Examine and document privacy risk.<br> <strong>2.11</strong> Evaluate and document fairness and bias.<br> <strong>2.12</strong> Assess environmental impact and sustainability.<br> <strong>2.13</strong> Evaluate the effectiveness of TEVV metrics and processes.</td></tr>
<tr><td width="15%">MEASURE 3</td><td width="35%">Mechanisms track identified risks over time.</td><td width="50%"><strong>3.1</strong> Regularly identify and track existing, unexpected, and emerging risks.<br> <strong>3.2</strong> Consider tracking when measurement methods or metrics are unavailable or inadequate.<br> <strong>3.3</strong> Enable end-user and affected-community reporting and appeal, and integrate feedback into evaluation.</td></tr>
<tr><td width="15%">MEASURE 4</td><td width="35%">Feedback on the effectiveness of measurement is gathered and assessed.</td><td width="50%"><strong>4.1</strong> Connect measurement to deployment context and expert/end-user input.<br> <strong>4.2</strong> Use relevant actor input to assess whether trustworthiness is consistent with intended performance.<br> <strong>4.3</strong> Document field-based changes in performance and trustworthiness.</td></tr>
</tbody>
</table>

### MANAGE — prioritization, treatment, response, and monitoring

MANAGE allocates resources to mapped and measured risks, prioritizes treatment, and plans responses, recovery, communication, monitoring, and continual improvement.

<table>
<thead><tr><th width="15%">Category</th><th width="35%">Category outcome in brief</th><th width="50%">Subcategories and outcome subjects</th></tr></thead>
<tbody>
<tr><td width="15%">MANAGE 1</td><td width="35%">Risks identified through MAP and MEASURE are prioritized, responded to, and managed.</td><td width="50%"><strong>1.1</strong> Decide whether the system meets its objectives and whether development/deployment should proceed.<br> <strong>1.2</strong> Prioritize risk treatment by impact, likelihood, and available resources or methods.<br> <strong>1.3</strong> Plan and document responses to high-priority risks, including mitigation, transfer, avoidance, or acceptance.<br> <strong>1.4</strong> Document negative residual risks to downstream acquirers and end users.</td></tr>
<tr><td width="15%">MANAGE 2</td><td width="35%">Strategies maximize benefits and minimize negative impacts, informed by relevant actors.</td><td width="50%"><strong>2.1</strong> Consider risk-management resources and viable non-AI alternatives to reduce potential impacts.<br> <strong>2.2</strong> Sustain the value of deployed systems.<br> <strong>2.3</strong> Respond to and recover from previously unknown risks.<br> <strong>2.4</strong> Assign and understand responsibilities to supersede, disengage, or deactivate systems with inconsistent performance or outcomes.</td></tr>
<tr><td width="15%">MANAGE 3</td><td width="35%">Third-party AI risks and benefits are managed.</td><td width="50%"><strong>3.1</strong> Regularly monitor third-party risks and benefits and apply/document controls.<br> <strong>3.2</strong> Monitor pre-trained models used in development as part of ongoing system maintenance.</td></tr>
<tr><td width="15%">MANAGE 4</td><td width="35%">Risk treatment, response, recovery, and communications are documented and monitored.</td><td width="50%"><strong>4.1</strong> Implement post-deployment monitoring, including feedback, appeal/override, decommissioning, incident response, recovery, and change management.<br> <strong>4.2</strong> Integrate measurable continual-improvement activities into system updates and engagement.<br> <strong>4.3</strong> Communicate incidents and errors and follow documented tracking, response, and recovery processes.</td></tr>
</tbody>
</table>

## Coverage and selection rule for the planned matrix

The inventory provides complete reference coverage of the 72 AI RMF 1.0 subcategories. It does **not** decide which outcomes belong in the first project matrix. That selection is the next design decision and must be based on the project context and the Profiles concept.

For each outcome considered in a project assessment, the future record should make the reviewer’s treatment visible. Suggested repository status labels (not NIST labels) are:

- **Selected** — relevant to this context and assessed.
- **Not selected — rationale recorded** — considered but not included, with a context-specific reason.
- **Deferred / not yet assessed** — review remains open.
- **Unable to assess — information gap** — evidence or context is insufficient.
- **Not applicable** — only where the reviewer explains why the outcome does not meaningfully apply to this system or lifecycle context.

These labels are draft design proposals, not NIST terminology. They should be reviewed when the matrix and assessment record are drafted. A selected outcome is not itself evidence of implementation or effectiveness.

## Traceability for the next drafting step

Every matrix prompt or assessment-record field should be linked to one or more exact Core references or explicitly marked as repository-created. The design should record:

1. the NIST function/category/subcategory reference;
2. whether the prompt derives from a Core outcome, an optional Playbook suggestion, or a repository-created usability/evidence field;
3. the reason it is included and how it is tailored;
4. evidence that could support an assessment, plus what that evidence cannot establish;
5. treatment of excluded, deferred, or unassessable outcomes; and
6. the source version and review trigger.

Company-published materials will later be assessed as documented practices/evidence and mapped back to this NIST-derived structure. They do not determine the Core structure or prove that a practice operates effectively.

## Sources

- NIST, [Artificial Intelligence Risk Management Framework (AI RMF 1.0), NIST AI 100-1](https://nvlpubs.nist.gov/nistpubs/ai/NIST.AI.100-1.pdf), published January 2023.
- NIST AI Resource Center, [AI RMF Core](https://airc.nist.gov/airmf-resources/airmf/5-sec-core/), excerpt from AI RMF 1.0; page states revision is in progress.
- NIST AI Resource Center, [AI RMF Profiles](https://airc.nist.gov/airmf-resources/airmf/6-sec-profile/), excerpt from AI RMF 1.0; page states revision is in progress.
- NIST AI Resource Center, [AI RMF Playbook](https://airc.nist.gov/airmf-resources/playbook/), page states Playbook update will follow the AI RMF revision.
- NIST, [AI Risk Management Framework overview and status](https://www.nist.gov/itl/ai-risk-management-framework), accessed 24 November 2026.

## Change record

| Date | Change | Reason/source |
|---|---|---|
| 24 November 2026 | Initial complete Core outcome inventory and source-status check | Official NIST AI RMF 1.0 Core, Profiles, Playbook, and NIST AI RMF status page |
