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

| Category | Category outcome in brief | Subcategories and outcome subjects |
|---|---|---|
| GOVERN 1 | Organization-wide policies, processes, procedures, and practices for AI risk are in place, transparent, and effective. | **1.1** Understand, manage, and document applicable legal and regulatory requirements.<br> **1.2** Integrate trustworthy-AI characteristics into organizational practices.<br> **1.3** Set risk-management depth according to organizational risk tolerance.<br> **1.4** Establish a transparent risk-management process aligned to organizational priorities.<br> **1.5** Plan monitoring and periodic review; define roles and review frequency.<br> **1.6** Inventory AI systems and resource them by risk priority.<br> **1.7** Safely decommission or phase out systems without increasing risk or reducing trustworthiness. |
| GOVERN 2 | Appropriate teams and people are empowered, responsible, and trained. | **2.1** Document and communicate roles, responsibilities, and lines of communication.<br> **2.2** Train personnel and partners for their AI risk-management duties.<br> **2.3** Executive leadership takes responsibility for AI risk decisions. |
| GOVERN 3 | Workforce diversity, equity, inclusion, and accessibility are prioritized in risk management. | **3.1** Use diverse perspectives in lifecycle risk decisions.<br> **3.2** Define and distinguish human-AI roles and oversight responsibilities. |
| GOVERN 4 | Teams support a culture that considers and communicates AI risk. | **4.1** Foster critical thinking and a safety-first mindset.<br> **4.2** Document and communicate risks and potential impacts.<br> **4.3** Enable AI testing, incident identification, and information sharing. |
| GOVERN 5 | Robust engagement with relevant AI actors is established. | **5.1** Collect, consider, prioritize, and integrate external feedback about impacts.<br> **5.2** Regularly incorporate adjudicated feedback into system design and implementation. |
| GOVERN 6 | Third-party software, data, and supply-chain risks and benefits are addressed. | **6.1** Address third-party risks, including intellectual-property and other rights risks.<br> **6.2** Prepare contingency processes for failures or incidents involving high-risk third-party data or AI systems. |

### MAP — context, system, risks, benefits, and impacts

MAP establishes the context for risks and provides information for MEASURE and MANAGE, including an initial decision about whether an AI solution is appropriate.

| Category | Category outcome in brief | Subcategories and outcome subjects |
|---|---|---|
| MAP 1 | Context is established and understood. | **1.1** Understand and document purpose, beneficial uses, context-specific law and expectations, deployment settings, affected parties, assumptions, limitations, and related evaluation.<br> **1.2** Document diverse interdisciplinary actors, skills, and participation.<br> **1.3** Understand and document organizational mission and AI goals.<br> **1.4** Define or reassess business value and use context.<br> **1.5** Determine and document organizational risk tolerances.<br> **1.6** Elicit system requirements and consider sociotechnical implications in design. |
| MAP 2 | The AI system is categorized. | **2.1** Define the tasks and methods the system supports.<br> **2.2** Document knowledge limits and how outputs may be used and overseen.<br> **2.3** Identify and document scientific-integrity and testing/evaluation/verification/validation considerations. |
| MAP 3 | Capabilities, intended use, goals, benefits, and costs are understood against suitable benchmarks. | **3.1** Examine and document potential benefits.<br> **3.2** Examine potential costs, including non-monetary costs associated with errors and trustworthiness.<br> **3.3** Specify application scope based on capability, context, and categorization.<br> **3.4** Define and document operator/practitioner proficiency processes.<br> **3.5** Define and assess human-oversight processes consistent with governance policies. |
| MAP 4 | Risks and benefits are mapped across system components, including third-party software and data. | **4.1** Map and document technology, legal, and rights risks across components.<br> **4.2** Identify and document internal risk controls for components, including third-party AI. |
| MAP 5 | Impacts on people, groups, communities, organizations, and society are characterized. | **5.1** Identify and document likelihood and magnitude of beneficial and harmful impacts using relevant sources.<br> **5.2** Establish practices and personnel for engagement and feedback on expected and unanticipated impacts. |

### MEASURE — methods, metrics, evaluation, tracking, and feedback

MEASURE uses qualitative, quantitative, or mixed methods to assess and monitor risks and impacts identified through MAP, and informs MANAGE.

| Category | Category outcome in brief | Subcategories and outcome subjects |
|---|---|---|
| MEASURE 1 | Appropriate methods and metrics are identified and applied. | **1.1** Select risk metrics, prioritizing significant risks; document what cannot or will not be measured.<br> **1.2** Regularly assess and update metric appropriateness and control effectiveness.<br> **1.3** Involve independent or non-frontline expertise and consult relevant actors as appropriate. |
| MEASURE 2 | Systems are evaluated for trustworthy characteristics. | **2.1** Document test sets, metrics, and evaluation tools.<br> **2.2** Ensure human-subject evaluations meet applicable protections and represent relevant populations.<br> **2.3** Measure and document performance or assurance under deployment-like conditions.<br> **2.4** Monitor system and component behavior in production.<br> **2.5** Demonstrate validity and reliability; document generalizability limits.<br> **2.6** Evaluate safety, residual risk, safe failure, and relevant safety metrics.<br> **2.7** Evaluate and document security and resilience.<br> **2.8** Examine transparency and accountability risks.<br> **2.9** Explain, validate, and document the model; interpret outputs in context.<br> **2.10** Examine and document privacy risk.<br> **2.11** Evaluate and document fairness and bias.<br> **2.12** Assess environmental impact and sustainability.<br> **2.13** Evaluate the effectiveness of TEVV metrics and processes. |
| MEASURE 3 | Mechanisms track identified risks over time. | **3.1** Regularly identify and track existing, unexpected, and emerging risks.<br> **3.2** Consider tracking when measurement methods or metrics are unavailable or inadequate.<br> **3.3** Enable end-user and affected-community reporting and appeal, and integrate feedback into evaluation. |
| MEASURE 4 | Feedback on the effectiveness of measurement is gathered and assessed. | **4.1** Connect measurement to deployment context and expert/end-user input.<br> **4.2** Use relevant actor input to assess whether trustworthiness is consistent with intended performance.<br> **4.3** Document field-based changes in performance and trustworthiness. |

### MANAGE — prioritization, treatment, response, and monitoring

MANAGE allocates resources to mapped and measured risks, prioritizes treatment, and plans responses, recovery, communication, monitoring, and continual improvement.

| Category | Category outcome in brief | Subcategories and outcome subjects |
|---|---|---|
| MANAGE 1 | Risks identified through MAP and MEASURE are prioritized, responded to, and managed. | **1.1** Decide whether the system meets its objectives and whether development/deployment should proceed.<br> **1.2** Prioritize risk treatment by impact, likelihood, and available resources or methods.<br> **1.3** Plan and document responses to high-priority risks, including mitigation, transfer, avoidance, or acceptance.<br> **1.4** Document negative residual risks to downstream acquirers and end users. |
| MANAGE 2 | Strategies maximize benefits and minimize negative impacts, informed by relevant actors. | **2.1** Consider risk-management resources and viable non-AI alternatives to reduce potential impacts.<br> **2.2** Sustain the value of deployed systems.<br> **2.3** Respond to and recover from previously unknown risks.<br> **2.4** Assign and understand responsibilities to supersede, disengage, or deactivate systems with inconsistent performance or outcomes. |
| MANAGE 3 | Third-party AI risks and benefits are managed. | **3.1** Regularly monitor third-party risks and benefits and apply/document controls.<br> **3.2** Monitor pre-trained models used in development as part of ongoing system maintenance. |
| MANAGE 4 | Risk treatment, response, recovery, and communications are documented and monitored. | **4.1** Implement post-deployment monitoring, including feedback, appeal/override, decommissioning, incident response, recovery, and change management.<br> **4.2** Integrate measurable continual-improvement activities into system updates and engagement.<br> **4.3** Communicate incidents and errors and follow documented tracking, response, and recovery processes. |

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
