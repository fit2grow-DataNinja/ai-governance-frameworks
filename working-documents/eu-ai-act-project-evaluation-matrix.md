# EU AI Act project-evaluation matrix

**Purpose:** A structured learning and issue-spotting aid for a project.  
**Source snapshot:** 19 November 2026. Confirm the current Regulation and guidance before applying it to a real deployment.

This matrix is a repository-authored synthesis of the Regulation and official Commission materials, not an official EU template. It separates legal obligations from suggested evidence. Classification depends on the project’s intended purpose, context, system characteristics, and operator role.

| Category | Evaluation questions | Main legal treatment | Potential records and evidence | Legal references |
|---|---|---|---|---|
| **Prohibited practices** (often described as unacceptable risk) | Does the intended purpose or actual use match a practice prohibited by Article 5? Check exact conditions and any stated exception against project facts. | Do not place on the market, put into service, or use an AI system for a prohibited purpose. This is a stop/go screen; other controls do not make a prohibited purpose acceptable. | **Suggested screening evidence:** intended-purpose statement; use-case and feature description; data-source review; Article 5 screen with rationale, source, reviewer, and open questions. Not a universal Article 5 documentation package. | Article 5; relevant definitions in Article 3. |
| **High-risk AI systems** | Does either Article 6 route apply: safety component/product covered by Annex I legislation requiring third-party conformity assessment, or a listed Annex III use case? Is an Article 6 filter or transition relevant? Is the organization provider, deployer, or both? | Applicable duties include documented risk management; data governance; technical documentation and logging; information for deployers; human oversight; accuracy, robustness, cybersecurity; quality management; and, as applicable, conformity assessment, registration, and post-market duties. Deployer duties are distinct from provider duties. | **Provider, where applicable:** risk-management records; data-governance records; technical documentation; logs; validation/test procedures, metrics and reports; oversight and cybersecurity description; quality-management procedures; instructions; change and post-market monitoring records; applicable conformity/registration records. **Deployer, where applicable:** use/oversight procedures; monitoring and incident records; logs under its control; notices; FRIA where Article 27 applies. Check separately whether GDPR DPIA is required. | Classification: Article 6; Annexes I, III. Requirements: Articles 9–15. Provider obligations: Articles 16–20. Technical documentation: Article 11 and Annex IV. Conformity, declaration, registration: Articles 43, 47–49. Post-market monitoring: Article 72. Deployer obligations: Article 26. FRIA: Article 27. |
| **Specific transparency duties** (often called limited/transparency risk) | Does the use fall within an Article 50 case: direct interaction, certain generated/manipulated content, emotion recognition, or biometric categorisation? Which paragraph and exceptions apply? | Provide required notices, disclosures, or machine-readable content markings clearly and accessibly. Duties and exceptions differ by case. | **Suggested evidence:** notice text and location; content-marking/detection design and tests; review of exceptions; human/editorial review records where relevant. Keep rationale for the legal trigger. | Article 50; current Commission guidance on transparency of AI-generated content. |
| **Minimal or no specific AI Act risk** | No Article 5 prohibition, no high-risk classification, and no applicable Article 50 duty identified. Does another AI Act rule or other law still apply? | AI Act does not impose the high-risk requirement set solely because the system falls here. Other laws still apply, including privacy, consumer, employment, product-safety, and sectoral requirements. Voluntary codes may be considered. | No general high-risk technical-documentation pack is prescribed just by this category. **Suggested proportionate project records:** purpose, data flows, risks, safeguards, evaluation, limitations, review decisions, and status. Label these as governance choices, not blanket AI Act obligations. | Article 6 and Commission risk-category overview; Article 50 if a transparency case applies; other applicable laws assessed separately. |

## Official evaluation support

- [AI Act high-risk classification checklist](https://ai-act-service-desk.ec.europa.eu/en/general-principles-classification-high-risk-ai-systems): AI-system definition, intended purpose, Annex I and III routes, Article 6 filter, and transitions.
- [EU AI Act Compliance Checker](https://ai-act-service-desk.ec.europa.eu/en/eu-ai-act-compliance-checker): beta, informational issue-spotting tool. Its result is not legal advice or a Commission determination.
- [Annex IV](https://ai-act-service-desk.ec.europa.eu/en/ai-act/annex-4): technical-documentation elements for applicable high-risk systems, not all projects.
- [Article 27 draft FRIA template announcement](https://digital-strategy.ec.europa.eu/en/news/commission-seeks-feedback-draft-template-fundamental-rights-impact-assessment-under-ai-act): draft announced 16 November 2026; verify adoption/current status before use.
- [Article 50 transparency guidance](https://ai-act-service-desk.ec.europa.eu/en/ai-act/resource/guidelines-transparency-ai-generated-content).

## Suggested project-screening sequence

1. Describe system, intended purpose, context, affected people, and output.
2. Identify provider/deployer role(s).
3. Screen Article 5.
4. Screen Article 6 and relevant Annex I/III routes, filters, and transitions.
5. Screen Article 50.
6. Identify other legal questions, especially data-protection law.
7. Record facts, source/version, rationale, uncertainty, reviewer, date, and next action.

Use the companion [project-screening record template](project-screening-record-template.md). This matrix is for learning and preliminary evaluation; it is not a legal opinion or proof of compliance.
