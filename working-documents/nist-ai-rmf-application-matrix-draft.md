# NIST AI RMF application matrix — draft

**Status:** Working draft for review; not NIST-issued  
**Framework baseline:** AI RMF 1.0, NIST AI 100-1 (2023)  
**Source status checked:** 24 November 2026; NIST says revision is in progress  
**Companion sources:** NIST AI RMF Profiles; NIST AI RMF Playbook (voluntary suggestions)  
**Purpose:** Help a reviewer select and reason about relevant AI RMF outcomes for one defined system or use case.

## How to use this matrix

This matrix is a repository-created application aid. It is not a legal obligations matrix, a universal checklist, a maturity model, a certification instrument, or a NIST-prescribed profile template.

Start with the project assessment record to define the system, use context, lifecycle stage, actors, organizational risk tolerance, and scope. **Before creating a project-specific use-case profile, search official NIST sources for relevant published profiles and document their fit and status.** Reuse, adapt, or combine a suitable existing NIST profile where appropriate; if no profile fits or it only partly fits, tailor outcomes from the Core and explain the additions or omissions. Treat drafts/concept notes as work in progress, not finalized profiles. Then review the subcategories below. For each, record one of the repository’s proposed treatment statuses in the assessment record:

- **Selected** — relevant to this context and included in the assessment.
- **Not selected — rationale recorded** — considered but excluded for a stated context-specific reason.
- **Deferred / not yet assessed** — assessment remains open.
- **Unable to assess — information gap** — required context or evidence is unavailable.
- **Not applicable — rationale recorded** — the outcome does not meaningfully apply to the defined system/context, with explanation.

These are repository-proposed labels, not NIST terminology. Do not treat “not selected” or “not applicable” as evidence that a risk is absent. A selection means the outcome will be considered; it does not mean it is implemented or achieved.

The matrix intentionally retains all 72 AI RMF 1.0 subcategories as a reference catalog. This lets the reviewer document selection and omissions transparently. It does **not** mean every subcategory applies to every system. NIST permits users to select outcomes based on their needs, resources, and capabilities. The assessment record should explain the tailoring. Functions may be revisited iteratively; GOVERN is cross-cutting.

For each of the 72 subcategories, assign a disposition in the assessment record. For subcategories selected for assessment, assign a project-specific focus tier: **Main focus** for outcomes central to the use context, material risks, or key decisions; **Sub-focus** for selected outcomes that support or qualify a main focus. This is a repository-created overview aid, not a NIST ranking or weighting. Both tiers remain assessed.

For every selected subcategory, record its Current Profile state (what available information and evidence show about how risk is currently managed) and Target Profile state (the desired state for this context), then identify gaps and priorities. For every selected subcategory, record:
1. the context-specific question considered;
2. the finding or current state, separating confirmed facts from assumptions;
3. the evidence examined, including source, date/version, and location;
4. the gap, uncertainty, or limitation;
5. proposed action, owner, timing, and decision/status, if applicable; and
6. how the conclusion is linked to the NIST outcome and why the outcome was selected.

The prompts below are repository-authored questions to help discuss the outcomes. They do not add requirements to NIST. Wording is summarized; consult the [official Core](https://airc.nist.gov/airmf-resources/airmf/5-sec-core/) for full outcome language. The [Core outcome inventory](nist-ai-rmf-core-outcome-inventory.md) provides the complete source-grounded index.

## GOVERN — organization-wide foundations

| NIST reference | Outcome focus | Assessment prompt |
|---|---|---|
| GOVERN 1.1 | Understand, manage, and document legal and regulatory requirements involving AI. | What legal or regulatory requirements have been identified for this system and its context? Who tracks them, and what documentation supports that account? |
| GOVERN 1.2 | Integrate trustworthy-AI characteristics into organizational practices. | Which trustworthy characteristics matter here, and where are they reflected in policies, processes, or work practices? |
| GOVERN 1.3 | Determine risk-management depth based on organizational risk tolerance. | How is the level of risk-management activity decided for this system, and what documented tolerance or rationale informs it? |
| GOVERN 1.4 | Establish a transparent risk-management process aligned with organizational priorities. | What process governs AI risk decisions for this work, and how can relevant actors understand its steps and outcomes? |
| GOVERN 1.5 | Plan monitoring and periodic review; define roles and review frequency. | Who reviews the system and risk process over time, what triggers review, and how often is review planned? |
| GOVERN 1.6 | Inventory AI systems and resource them according to risk priorities. | How is this system represented in the organization’s AI inventory, and are resources aligned with its stated risk priority? |
| GOVERN 1.7 | Safely decommission or phase out AI systems. | What would trigger retirement or phase-out, and how would it be done without increasing risk or reducing trustworthiness? |
| GOVERN 2.1 | Document and communicate roles, responsibilities, and lines of communication. | Which teams and people have risk-management responsibilities, and how are handoffs and escalation paths made clear? |
| GOVERN 2.2 | Train personnel and partners for their AI risk-management duties. | What training or support is available to people and partners performing relevant duties, and how is its suitability assessed? |
| GOVERN 2.3 | Executive leadership takes responsibility for AI risk decisions. | Which leadership role is accountable for decisions about this system’s development or deployment risks, and what shows that responsibility is exercised? |
| GOVERN 3.1 | Use diverse perspectives in lifecycle risk decisions. | Which relevant disciplines, experiences, and affected perspectives inform risk decisions, and what perspectives may be missing? |
| GOVERN 3.2 | Define human-AI roles and oversight responsibilities. | How are human and AI tasks divided, and who is responsible for oversight at each relevant point? |
| GOVERN 4.1 | Foster critical thinking and a safety-first mindset. | What practices encourage people to question system outputs, assumptions, and potential harm during design, deployment, and use? |
| GOVERN 4.2 | Document and communicate risks and potential impacts. | Which risks and impacts are recorded, who receives the information, and how are material changes communicated? |
| GOVERN 4.3 | Enable testing, incident identification, and information sharing. | How can relevant teams test the system, identify incidents, and share lessons or risk information? |
| GOVERN 5.1 | Collect, consider, prioritize, and integrate external feedback about impacts. | Which people outside the development/deployment team can provide feedback, and how is it considered and prioritized? |
| GOVERN 5.2 | Incorporate adjudicated feedback into design and implementation. | How are feedback decisions resolved and, where appropriate, reflected in system design or implementation? |
| GOVERN 6.1 | Address third-party risks, including intellectual-property and other rights risks. | Which third-party data, software, models, or services are involved, and how are associated risks and rights addressed? |
| GOVERN 6.2 | Prepare contingencies for failures or incidents involving high-risk third-party data or AI systems. | What contingency arrangements apply if a third-party AI system or data source fails or causes an incident? |

## MAP — context, system, risks, benefits, and impacts

| NIST reference | Outcome focus | Assessment prompt |
|---|---|---|
| MAP 1.1 | Document purpose, beneficial uses, laws, norms, deployment settings, affected parties, assumptions, limitations, and evaluation. | What is the intended purpose and setting; who may benefit or be affected; what laws, expectations, assumptions, limits, and evaluation needs are relevant? |
| MAP 1.2 | Document diverse interdisciplinary actors, skills, and participation. | Which roles, competencies, and user/domain perspectives are needed to understand this context, and who participated? |
| MAP 1.3 | Understand and document organizational mission and AI goals. | How does the system relate to the organization’s mission and stated AI goals? |
| MAP 1.4 | Define or reassess business value and use context. | What business need or value is expected, and has it been reassessed if the system already exists? |
| MAP 1.5 | Determine and document organizational risk tolerances. | Which organizational risk tolerances govern this use, and how are they documented or applied? |
| MAP 1.6 | Elicit system requirements and consider sociotechnical implications. | What requirements have relevant actors identified, including social/contextual implications, and how do design decisions address them? |
| MAP 2.1 | Define tasks and methods supported by the system. | What tasks does the system support, and what methods or AI approaches implement them? |
| MAP 2.2 | Document knowledge limits and human use/oversight of outputs. | What are the system’s known limits, how might outputs be used, and what information do people need to oversee them? |
| MAP 2.3 | Identify and document scientific integrity and TEVV considerations. | What evaluation design, data selection, representativeness, suitability, trustworthiness, or construct-validity issues need to be addressed? |
| MAP 3.1 | Examine and document potential benefits. | What benefits are expected from the intended functionality and performance, and what supports those expectations? |
| MAP 3.2 | Examine potential costs, including non-monetary costs related to errors and trustworthiness. | What financial and non-financial costs could arise from errors or system behavior, in light of organizational risk tolerance? |
| MAP 3.3 | Specify application scope based on capability, context, and categorization. | What is the intended and bounded scope of use, given the system’s capabilities and context? |
| MAP 3.4 | Define and document operator/practitioner proficiency processes. | What do operators and practitioners need to understand about performance, trustworthiness, standards, or certifications, and how is proficiency supported? |
| MAP 3.5 | Define and assess human-oversight processes consistent with governance policies. | What oversight is intended, who performs it, and how is the process checked against organizational policies? |
| MAP 4.1 | Map technology, legal, and rights risks across components. | What components and third-party inputs are involved, and how are technology, legal, and rights risks mapped and documented? |
| MAP 4.2 | Identify and document internal risk controls for components. | What controls address component-level risks, including risks from third-party AI technologies? |
| MAP 5.1 | Identify and document likelihood and magnitude of beneficial and harmful impacts. | Which potential impacts are identified, how are likelihood and magnitude assessed, and what sources or feedback inform the assessment? |
| MAP 5.2 | Establish engagement practices and personnel for impact feedback. | Who is responsible for ongoing engagement, and how are positive, negative, and unexpected impacts fed into decisions? |

## MEASURE — methods, evaluation, tracking, and feedback

| NIST reference | Outcome focus | Assessment prompt |
|---|---|---|
| MEASURE 1.1 | Select risk metrics; document risks or characteristics not measured. | Which identified risks and trustworthiness characteristics are measured first, with what methods, and what cannot or will not be measured? |
| MEASURE 1.2 | Regularly assess metric suitability and control effectiveness. | How are metrics and existing controls reviewed and updated, including in light of errors and impacts? |
| MEASURE 1.3 | Involve non-frontline or independent assessors and consult relevant actors as appropriate. | Who reviews the assessment independently of frontline development, and which domain experts, users, or affected groups are consulted where appropriate? |
| MEASURE 2.1 | Document test sets, metrics, and evaluation tools. | Are test data, metrics, and tools documented well enough to understand and reproduce the evaluation? |
| MEASURE 2.2 | Protect human subjects and represent relevant populations in evaluations. | If people participate in evaluation, what protections apply and how does the sample represent the relevant population? |
| MEASURE 2.3 | Measure and document performance or assurance under deployment-like conditions. | How is performance or assurance assessed in conditions similar to intended deployment, and where are results recorded? |
| MEASURE 2.4 | Monitor system and component behavior in production. | If deployed, what system and component behavior is monitored, and how are observations handled? |
| MEASURE 2.5 | Demonstrate validity and reliability; document generalizability limits. | What evidence supports validity and reliability, and where are limits beyond tested conditions documented? |
| MEASURE 2.6 | Evaluate safety, residual risk, safe failure, and relevant safety metrics. | How are safety risks and residual risk assessed, and what evidence addresses safe failure and relevant operational metrics? |
| MEASURE 2.7 | Evaluate and document security and resilience. | Which security and resilience risks are evaluated, using what methods, and where are results recorded? |
| MEASURE 2.8 | Examine transparency and accountability risks. | What transparency and accountability risks have been identified, and how are they assessed? |
| MEASURE 2.9 | Explain, validate, and document models; interpret outputs in context. | What explanations or validation are available, and how are outputs interpreted for responsible use in this context? |
| MEASURE 2.10 | Examine and document privacy risk. | What privacy risks have been assessed, and what evidence or decisions document that assessment? |
| MEASURE 2.11 | Evaluate and document fairness and bias. | Which fairness and bias concerns are evaluated, for which populations or settings, and what results are documented? |
| MEASURE 2.12 | Assess environmental impact and sustainability. | What environmental or sustainability impacts of training and management are considered, and how are they assessed? |
| MEASURE 2.13 | Evaluate TEVV metric and process effectiveness. | How is the effectiveness of the chosen test, evaluation, verification, and validation approach itself reviewed? |
| MEASURE 3.1 | Regularly identify and track existing, unexpected, and emerging risks. | What people, methods, and records support ongoing identification and tracking of known and emerging risks? |
| MEASURE 3.2 | Consider risk tracking where methods or metrics are unavailable or inadequate. | Where are risks difficult to measure, what alternative tracking or qualitative approaches are considered? |
| MEASURE 3.3 | Enable reporting and appeal; integrate feedback into evaluation. | Can users and affected communities report problems or appeal outcomes, and how does feedback inform evaluation? |
| MEASURE 4.1 | Connect measurement to context and expert/end-user input. | How do deployment context and expert or end-user perspectives inform the measurement approach? |
| MEASURE 4.2 | Use actor input to assess consistency with intended performance. | How do relevant actors help determine whether the system performs consistently as intended across the lifecycle? |
| MEASURE 4.3 | Document field-based changes in performance and trustworthiness. | What evidence of improvement or decline is gathered from consultations and field data, and how is it documented? |

## MANAGE — prioritization, treatment, response, and monitoring

| NIST reference | Outcome focus | Assessment prompt |
|---|---|---|
| MANAGE 1.1 | Decide whether the system achieves objectives and should proceed. | Does the system meet its intended purpose and stated objectives, and what supports a proceed, change, pause, or stop decision? |
| MANAGE 1.2 | Prioritize treatment by impact, likelihood, and available resources or methods. | How are documented risks prioritized for treatment, considering impact, likelihood, and available resources? |
| MANAGE 1.3 | Plan and document responses to high-priority risks. | What response is selected for each high-priority risk—mitigate, transfer, avoid, accept, or another justified approach—and why? |
| MANAGE 1.4 | Document negative residual risks to downstream acquirers and end users. | What negative residual risks remain, and how are they documented for downstream acquirers and end users? |
| MANAGE 2.1 | Consider risk resources and viable non-AI alternatives. | What resources are needed to manage risk, and have viable non-AI alternatives been considered? |
| MANAGE 2.2 | Sustain the value of deployed systems. | What mechanisms support continued value, and how are they monitored or applied? |
| MANAGE 2.3 | Respond to and recover from previously unknown risks. | How would the organization respond and recover if a previously unknown risk is identified? |
| MANAGE 2.4 | Assign responsibilities to supersede, disengage, or deactivate systems with inconsistent outcomes. | Who can supersede, disengage, or deactivate the system, and under what conditions and process? |
| MANAGE 3.1 | Monitor third-party risks and benefits and apply/document controls. | How are third-party risks and benefits monitored, and what controls are applied and recorded? |
| MANAGE 3.2 | Monitor pre-trained models used in development. | If pre-trained models are used, how are they included in ongoing monitoring and maintenance? |
| MANAGE 4.1 | Implement post-deployment monitoring and response plans. | What monitoring, feedback, appeal/override, decommissioning, incident response, recovery, and change-management processes are implemented or planned? |
| MANAGE 4.2 | Integrate measurable continual improvement and engagement into updates. | What measurable improvement activities are part of updates, and how do relevant actors contribute? |
| MANAGE 4.3 | Communicate incidents/errors and follow response/recovery processes. | How are incidents and errors communicated, tracked, responded to, and recovered from? |

## Use of the Playbook

The NIST AI RMF Playbook may be consulted after selecting a Core outcome to identify optional action ideas. Record each such item as a **voluntary Playbook suggestion**, with the relevant subcategory reference and the reason it fits the context. Record whether it is adopted, adapted, deferred, or omitted. Do not describe the suggestion as a mandatory NIST step.

## Evidence and conclusion discipline

Examples of evidence could include system descriptions, requirements, test plans/results, risk logs, process documents, review records, monitoring records, decision records, and incident records. These are illustrative repository examples, not a NIST-mandated evidence package.

For every conclusion, state what was actually reviewed and what it supports. A policy can evidence a documented commitment; a procedure can evidence a defined process; a completed record can evidence that an activity was documented. None, on its own, establishes that a process operates consistently or is effective. Describe this work as an assessment of documented implementation and available evidence unless stronger evidence supports a stronger statement.

## Source and maintenance

- Core and Profiles: [SRC-013](../sources/records/SRC-013-nist-ai-rmf-core-and-profiles.md)
- Playbook: [SRC-014](../sources/records/SRC-014-nist-ai-rmf-playbook.md)
- Complete source-grounded index: [NIST AI RMF Core outcome inventory](nist-ai-rmf-core-outcome-inventory.md)
- Development and change-control approach: [Developing traceable NIST AI RMF working documents](nist-ai-rmf-documentation-development-approach.md)

Recheck the official NIST source baseline before finalizing this draft. A revised AI RMF triggers review of all Core mappings; a Playbook update triggers review of optional prompts derived from it. Keep a single current draft and record material changes with date, reason, affected elements, and source.
