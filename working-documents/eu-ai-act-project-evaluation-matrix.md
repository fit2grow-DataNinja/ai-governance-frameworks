# EU AI Act project-evaluation matrix

**Purpose:** A structured learning and issue-spotting aid for a project.  
**Review date:** 23 November 2026  
**Legal text snapshot reviewed:** Consolidated Regulation (EU) 2024/1689, EUR-Lex version dated 27 July 2026, including Regulation (EU) 2026/1744. Verify EUR-Lex for later amendments before applying this aid to a real deployment.

This is a repository-authored synthesis, not an official EU template or legal opinion. The matrix separates **binding legal obligations**, **official but non-binding guidance**, and **potential records and evidence**. Evidence examples are suggested project artifacts; they are not automatically required by law. Classification depends on the system’s intended purpose, context, characteristics, and the roles actually performed by each organization. An issue-spotting result is preliminary and does not establish compliance.

## Screening matrix

| Category | Evaluation questions | Main legal treatment | Official guidance (non-binding) | Potential records and evidence |
|---|---|---|---|---|
| **Article 5 — prohibited practices** | Could the system’s intended purpose or actual use meet an Article 5 prohibition? Check all conditions, definitions, exceptions, and project facts. | Article 5 prohibits specified practices. If a prohibition applies, other controls do not make that use permissible. Check each provision’s application date, including the staged application of specified amended provisions. | Commission explanations or AI Act Service Desk material about Article 5, where available. Such material can support interpretation but does not replace the Regulation. | **Suggested screening evidence:** intended-purpose and use description; relevant feature/data review; provision-by-provision rationale; assumptions, reviewer, sources, and open questions. This is not a universal Article 5 documentation package. |
| **Article 6 — high-risk classification and related duties** | Does either route apply: (1) a product or safety component covered by Annex I legislation requiring third-party conformity assessment, or (2) a listed Annex III use case? Do specific Article 6 conditions, exceptions, or transitions apply? Which organization acts as provider, deployer, importer, distributor, authorised representative, or another relevant actor? Could a value-chain action change an actor’s role? | Apply Article 6 and the applicable Annex. For Annex III, Article 6(3) permits an exception only if its conditions are met; profiling of natural persons remains high-risk, and a provider relying on the exception must document its assessment and address Article 49(2) registration. Article 6(1a)–(1c) contains specific product/safety-component rules. If high-risk, applicable duties vary by system, actor, and date: they may include Articles 9–21 for providers, Article 26 for deployers, Article 27 FRIA for specified deployers, and conformity, registration, and post-market duties. Under Article 25, certain rebranding, substantial modification, or intended-purpose changes can cause another actor to be treated as provider. | Commission high-risk classification guidance and AI Act Service Desk materials. Check whether a guideline is final or still draft. They support interpretation; the Regulation controls. | **Suggested evidence:** route-by-route classification rationale; intended-purpose and context facts; entity/role map; evidence for any exception; applicable-date check; actor-specific obligation map; records and controls linked to applicable provisions, with owners and status. Distinguish legally required documentation from optional evidence. Annex IV applies only where relevant. |
| **Article 50 — specific transparency duties** | Does the use fall within an Article 50 case, such as direct interaction, certain generated or manipulated content, emotion recognition, or biometric categorisation? Which paragraph, actor, timing rule, and exception apply? | Article 50 assigns distinct duties to providers and deployers. Depending on the case, duties include informing people about direct interaction, marking certain synthetic outputs, or disclosing certain generated or manipulated content. Triggers, exceptions, and timing differ by paragraph. | Commission Article 50 transparency guidance. It can explain implementation but is non-binding; check the Regulation for the applicable duty and exception. | **Suggested evidence:** paragraph-specific trigger/exception analysis; notice wording and placement; marking design and tests; human/editorial review records where relevant. These examples are not a universal Article 50 documentation package. |
| **Other AI Act duties and other law** | Even if no issue is identified under Articles 5, 6, or 50, could another AI Act provision or separate law apply? See the **supplementary checklist below**. | Other duties may apply independently, including AI literacy, GPAI obligations, registration, Article 27 FRIA, and other high-risk duties. Separate laws may also apply. Check each duty’s trigger. | Relevant Commission or regulator guidance for the specific provision or law. Guidance can support interpretation but does not replace binding law. | **Suggested evidence:** record which additional provisions and laws were screened, outcome and rationale, sources/versions checked, responsible reviewer, open questions, and follow-up. A particular assessment or record may itself be legally required if its trigger applies. |

## Supplementary checklist: other AI Act duties and other law

This **non-exhaustive** checklist expands the final row of the main matrix. Check each obligation’s legal trigger against the system, organization, role, and use context. Article 50 remains a separate screen in the main matrix.

| Separate obligation screen | What to check | Main actor(s) to identify |
|---|---|---|
| **AI literacy — Article 4** | Whether providers and deployers have taken measures, to their best extent, to ensure sufficient AI literacy among relevant staff and other people dealing with AI on their behalf, considering their knowledge, experience, training, context, and affected groups. | Provider and deployer |
| **General-purpose AI models — Chapter V** | Whether a GPAI model is involved and which obligations apply to its provider; separately check the additional duties for models with systemic risk and any downstream-provider obligations. | GPAI model provider; downstream AI-system provider where relevant |
| **Registration and database duties** | Whether the system or actor must be registered, what information must be submitted, and when. Check the relevant classification and role; registration duties are not one universal requirement. | Provider; certain public-authority deployers; other actors where a provision specifies |
| **Fundamental rights impact assessment — Article 27** | Whether the deployer and high-risk use fall within Article 27’s specified scope, and whether the assessment and notification duties are triggered. | Specified deployer |
| **Other high-risk-system duties** | If the system is high-risk, check applicable provider and deployer duties across the relevant Articles and Annexes, including conformity assessment, instructions, monitoring, incident reporting, and human oversight. | Provider, deployer, and other relevant operators |
| **Other laws and sector rules** | Separately screen data protection, employment, consumer, product-safety, accessibility, cybersecurity, and sector-specific law as relevant. For example, assess whether a GDPR DPIA is required. | The entity with the applicable legal duty; identify the responsible organization |

## Application and transition dates to check

The dates below reflect the consolidated text reviewed on **23 November 2026**. Record the date relevant to the particular provision and system; “the AI Act applies” is not one single date.

- The Regulation’s general application date is **2 August 2026**, subject to specific staged provisions.
- Under the amended Article 113, specified new Article 5(1)(ba) and (bb), and Article 5(1a) and (1b), apply from **2 December 2026**.
- The amended transition provides that Annex III high-risk requirements apply from **2 December 2027** and Annex I high-risk requirements from **2 August 2028**, subject to the exact text and relevant system facts.
- Article 50(2) includes a transition for providers of systems placed on the market before **2 August 2026**; this transition is in Article 111(4), and applies by **2 December 2026**. Check the exact system facts and text.

These dates are not a substitute for checking the current consolidated Regulation and any provision-specific transition.

## Official evaluation support and status

- [Binding Regulation — consolidated EUR-Lex text](https://eur-lex.europa.eu/eli/reg/2024/1689/2026-07-27/eng): controlling legal text for this snapshot. See [SRC-001](../sources/records/SRC-001-eu-ai-act-consolidated-text.md).
- [High-risk classification guidelines](https://digital-strategy.ec.europa.eu/en/policies/guidelines-classification-high-risk-ai-systems): Commission draft published 19 May 2026; consultation closed 23 July 2026; final guidance was planned by end-2026. As of this review date, treat the draft as non-binding and not final. See [SRC-002](../sources/records/SRC-002-high-risk-classification-guidance.md).
- [AI Act Service Desk high-risk classification principles](https://ai-act-service-desk.ec.europa.eu/en/general-principles-classification-high-risk-ai-systems): official implementation support; guidance does not replace the Regulation. See [SRC-005](../sources/records/SRC-005-classification-principles.md).
- [EU AI Act Compliance Checker](https://ai-act-service-desk.ec.europa.eu/en/eu-ai-act-compliance-checker): beta informational issue-spotting tool; its output is not legal advice or a Commission determination. See [SRC-006](../sources/records/SRC-006-compliance-checker.md).
- [Annex IV](https://ai-act-service-desk.ec.europa.eu/en/ai-act/annex-4): technical-documentation elements for applicable high-risk systems. See [SRC-007](../sources/records/SRC-007-annex-iv.md).
- [Article 27 draft FRIA template announcement](https://digital-strategy.ec.europa.eu/en/news/commission-seeks-feedback-draft-template-fundamental-rights-impact-assessment-under-ai-act): draft questionnaire/template announced 16 November 2026; consultation open until 15 January 2027. It is not an adopted official template as of this review date. Article 27 applies only to specified deployers. See [SRC-004](../sources/records/SRC-004-article-27-draft-fria-template.md).
- [Article 50 transparency guidance](https://ai-act-service-desk.ec.europa.eu/en/ai-act/resource/guidelines-transparency-ai-generated-content): Commission guidance published 20 July 2026; interpretive support, not binding legislation. See [SRC-003](../sources/records/SRC-003-article-50-transparency-guidance.md).

## Framework-level open questions

This section tracks questions about the reusable matrix and its source coverage. It is not a second project-evaluation checklist. For a specific system, record facts, role analysis, applicable provisions, conclusions, evidence, and follow-up in the [project-screening record template](project-screening-record-template.md).

- **Guidance updates:** When the Commission publishes final high-risk classification guidelines or adopts a final Article 27 FRIA template, what changes are needed in the matrix and source records?
- **Coverage of the supplementary checklist:** As the repository reviews additional primary sources, are the listed separate-obligation screens sufficient for a clear overview, or should another distinct screen be added?
- **Boundary for other laws:** How much reusable detail should this matrix provide for data-protection, employment, consumer, product-safety, accessibility, cybersecurity, and sector-specific law before directing readers to the relevant specialist framework or authority?
- **Source maintenance:** What review triggers and cadence will keep the legal snapshot, guidance status, and linked source records current?

These are repository-maintenance and scope questions. They do not prevent the matrix from guiding a preliminary project assessment; project-specific facts and unresolved applicability questions belong in that project’s screening record and may require qualified legal review.

## Suggested screening sequence

1. Fix the system boundary, intended purpose, use context, affected people, and version being assessed.
2. Identify each organization’s likely role and any value-chain or role-change issue.
3. Screen Article 5 provision by provision.
4. Assess each Article 6 route, its conditions, exceptions, documentation, registration, and applicable date.
5. If high-risk, map requirements to actors and distinguish prescribed duties from suggested evidence.
6. Screen each relevant Article 50 paragraph and exception.
7. Check other AI Act duties and separate legal questions, including data protection.
8. Record the facts, source snapshot, exact provisions, reasoning, uncertainty, reviewer, and next action.

Use the companion [project-screening record template](project-screening-record-template.md). “No issue identified” is a preliminary screening result, not a statutory risk category or assurance of compliance.
