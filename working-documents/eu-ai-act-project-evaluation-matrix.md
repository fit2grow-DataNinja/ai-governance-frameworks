# EU AI Act project-evaluation matrix

**Purpose:** A structured learning and issue-spotting aid for a project.  
**Review date:** 23 November 2026  
**Legal text snapshot reviewed:** Consolidated Regulation (EU) 2024/1689, EUR-Lex version dated 27 July 2026, including Regulation (EU) 2026/1744. Verify EUR-Lex for later amendments before applying this aid to a real deployment.

This is a repository-authored synthesis, not an official EU template or legal opinion. It separates binding legal text, official but non-binding guidance, and suggested portfolio evidence. Classification depends on the system’s intended purpose, context, characteristics, and the roles actually performed by each organization. An issue-spotting result is preliminary and does not establish compliance.

## Screening matrix

| Topic | Working questions | Legal anchor and treatment | Suggested project evidence (not a universal statutory package) |
|---|---|---|---|
| **Article 5 — prohibited practices** | Could the system’s intended purpose or actual use meet an Article 5 prohibition? Check all conditions, definitions, exceptions, and the facts of use. | Article 5 prohibits specified practices. If a prohibition applies, other controls do not make that use permissible. The 2026 amendment adds provisions whose application is staged; see dates below. | Intended-purpose and use description; relevant feature/data review; provision-by-provision rationale; assumptions, reviewer, and open questions. |
| **Article 6 — high-risk classification** | Assess both routes: (1) a product or safety component under Annex I legislation requiring third-party conformity assessment; (2) an Annex III use case. What is the system’s actual purpose and context? Is a safety-component carve-out or Annex III significant-risk exception claimed? Is profiling of natural persons involved? | Apply Article 6 and the applicable Annex. For Annex III, Article 6(3) allows the specified exception only when the system does not pose a significant risk of harm to health, safety, or fundamental rights, including because it does not materially influence decision-making; the listed conditions must be considered. Profiling of natural persons remains high-risk under Article 6(3). A provider relying on the exception must document its assessment before placing the system on the market or putting it into service and register it as required by Article 49(2). Article 6(1a)–(1c) contains specific rules for certain safety-component/product cases; check their exact conditions rather than treating the filter as general. | Intended purpose and affected decision; route-by-route analysis; evidence supporting each condition; provider’s documented Article 6(3) assessment and registration where applicable; unresolved facts and legal review. |
| **Role and value chain** | Which entity is provider, deployer, importer, distributor, authorised representative, or another relevant actor? Does an entity rebrand, substantially modify, or change intended purpose? Are roles different for separate system components or contexts? | Duties are role-specific. Consider Articles 3, 16–27, especially Article 25 on value-chain responsibilities and role changes. Labels in contracts or project documents do not alone determine the legal role. | Entity/system map; intended-purpose and change history; supplier/customer responsibilities; contract and technical facts requiring review. |
| **High-risk system obligations** | If classified high-risk, which obligations apply to each actor and on what application date? | Providers: Articles 9–21 as applicable, including risk management, data governance, technical documentation/logging, instructions, human oversight, accuracy/robustness/cybersecurity, quality management, corrective action, and post-market duties. Deployer obligations include Article 26; Article 27 FRIA applies only to specified deployers and contexts. Conformity, registration, and other duties depend on the system and actor. | Separate provider/deployer obligation map; required records identified against exact provisions; suggested controls clearly marked; evidence, owner, status, and gaps. Annex IV is the technical-documentation structure for applicable high-risk systems, not every project. |
| **Article 50 — transparency** | For each paragraph, is there a covered interaction or output? Is the entity provider or deployer? Does a stated exception apply? When and how must information be given or content marked? | Article 50 duties differ: provider obligations include informing people interacting directly with AI unless obvious (para. 1), and machine-readable marking/detectability for certain synthetic outputs (para. 2, subject to stated exceptions). Deployer obligations include notice for emotion-recognition/biometric-categorisation use (para. 3) and disclosure for deepfakes and certain public-interest text (para. 4, with stated exceptions). Information must be clear and distinguishable at first interaction/exposure (para. 5). Check exact text and the relevant transition. | Paragraph-specific trigger/exception analysis; notice wording and placement; marking/detection design and tests; human/editorial review evidence where relevant. |
| **Other AI Act duties and other law** | Even if no Article 5/6/50 issue is identified, could another AI Act provision apply? What separate privacy, consumer, employment, product-safety, sectoral, or other legal analysis is needed? | The four-category “risk” shorthand is not a complete legal classification. Duties such as AI literacy or general-purpose AI obligations may apply on their own terms. Other laws remain separate. A GDPR DPIA is a separate assessment where required; Article 27 FRIA is not a substitute, although the Act permits certain information to be cross-referenced when conditions are met. | Separate applicability questions, accountable reviewer, source/version and follow-up. Treat proportionate project records as organizational choices unless a specific legal provision requires them. |

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

## Open questions for later review

These issues depend on facts, further interpretation, or future source updates. They are not resolved by this general-purpose matrix.

- How should a particular system’s intended purpose, significant influence on decision-making, and Article 6(3) conditions be evidenced?
- Which organization performs each statutory role in a specific deployment, especially where a system is adapted, rebranded, or substantially modified?
- Which Article 27 trigger applies to the deployer and use context, and what final FRIA template or guidance will the Commission publish?
- How do provision-specific transitional rules apply to an existing system, significant changes, or a concrete launch date?
- Which other AI Act provisions and non-AI laws apply independently of the Article 5/6/50 screens?

A real assessment should route unresolved legal classification and applicability questions to qualified counsel or the relevant competent authority as appropriate.

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
