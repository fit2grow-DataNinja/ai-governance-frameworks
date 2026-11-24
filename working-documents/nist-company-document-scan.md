# NIST AI RMF company-document scan — initial sample

**Status:** Initial bounded review completed; purposive sample, not representative  
**Review date:** 24 November 2026  
**Framework baseline:** NIST AI RMF 1.0, NIST AI 100-1 (2023)  
**Research method:** Review published artifacts and accessible source passages; map documented content to Core outcomes only where the connection can be explained.

## Research question

What types of publicly available AI governance and lifecycle documents do selected large AI technology providers publish, what are those documents intended to do, and which NIST AI RMF 1.0 outcomes do their contents directly or partially support?

The unit of analysis is the **document or artifact**, not the organization. The aim is to learn from actual standards, templates, model documentation, and data-documentation tools—not to infer the organization’s full internal governance system from public materials.

## Sample scope and selection

| Dimension | Scope |
|---|---|
| Organization sample | Microsoft and Google DeepMind / Google |
| Organization scale and role | Large, multinational technology organizations publishing or providing AI systems, models, platforms, or developer resources |
| Geography / language | Official, English-language, publicly accessible first-party sources; organizations are U.S.-based, while their products and documents may be global |
| Sampling approach | Purposive selection based on availability of inspectable working artifacts: an externally published internal standard and assessment template; model-specific documentation; and a data-documentation toolkit |
| Collection window | Public sources accessed 24 November 2026 |
| Included artifact types | Governance standard with concrete requirements; impact assessment template; model card; dataset documentation toolkit or workflow |
| Exclusions | Generic AI principles, marketing claims, case narratives without linked working material, third-party commentary, and artifacts whose relevant content could not be inspected |
| Generalization limit | This is a small technology-provider sample. Patterns are observations within the selected corpus, not claims about all large companies, sectors, or AI governance practice prevalence. A non-technology deployer and other regions would be needed for broader comparisons. |

### Search and inclusion method

The initial search used official company resource pages and direct official documents for terms such as “Responsible AI Standard,” “Impact Assessment Template,” “model card,” and “Data Cards Playbook.” An item is included when it contains concrete requirements, prompts, technical system/model information, an assessment structure, or a reusable documentation workflow. A high-level commitment may help interpret an artifact but is not treated as a working document by itself.

The inventory is bounded to artifacts discovered through these selected official resource paths and directly linked documents. It is not an exhaustive crawl of every document published by either organization. Each source’s publication/update date and access status should be rechecked before reuse.

This scan focuses on artifacts with concrete requirements, assessment structure, technical/model information, or a reusable documentation workflow. For a separate, optional analysis of public AI-governance materials that make visible links among an organization’s stated principles, goals or objectives, internal requirements or practices, and supporting documents, see the [company AI-governance document analysis method](nist-company-ai-governance-document-analysis.md). This companion method does not change this scan’s sample or inclusion rules and does not require every layer to be present.

## Document inventory and intent classification

| ID | Organization / publisher | Artifact and source | Artifact intent | Evidence class for this review | Limit |
|---|---|---|---|---|---|
| DOC-01 | Microsoft | [Responsible AI Standard v2 — General Requirements](https://cdn-dynmedia-1.microsoft.com/is/content/microsoftcorp/microsoft/final/en-us/microsoft-brand/documents/Microsoft-Responsible-AI-Standard-General-Requirements.pdf) | Internal engineering/governance standard published externally; specifies goals, requirements, review, and update triggers | Publicly documented policy/standard and defined process | Does not establish how consistently the requirements operate across systems or teams |
| DOC-02 | Microsoft | [Responsible AI Impact Assessment Template](https://blogs.microsoft.com/wp-content/uploads/prod/sites/5/2022/06/Microsoft-RAI-Impact-Assessment-Template.pdf) | Reusable project assessment form for system information, intended uses, stakeholders, benefits/harms, data, goal applicability, and impact summary | Published template / assessment instrument | A blank template is not evidence that an assessment was completed or that mitigations were effective |
| DOC-03 | Google for Developers | [Data Cards Playbook](https://developers.google.com/learn/pathways/data-cards-playbook) | Learning toolkit and workflow for dataset transparency documentation, stakeholder schema design, validation, Data Cards, and audits | Published reusable method/toolkit | Not evidence that Google or a user organization has applied the toolkit to a particular dataset |
| DOC-04 | Google DeepMind | [Model cards collection](https://deepmind.google/models/model-cards/) | Public index of system/model-specific documentation | Public documentation collection | Index alone is not evidence of the quality or completeness of every listed card |
| DOC-05 | Google DeepMind | [Gemini Omni Flash Model Card](https://deepmind.google/models/model-cards/gemini-omni-flash/) | Model-specific summary of model information, data, intended use, limits, acceptable use, safety evaluation, red teaming, and mitigations | Published model documentation; source-reported evaluation and mitigation claims | Public claims and described activities are not independently validated here and do not show every internal record |

The source-level reviews are recorded in [SRC-015](../sources/records/SRC-015-microsoft-responsible-ai-standard-v2.md), [SRC-016](../sources/records/SRC-016-microsoft-impact-assessment-template.md), [SRC-017](../sources/records/SRC-017-google-data-cards-playbook.md), and [SRC-018](../sources/records/SRC-018-google-deepmind-gemini-omni-flash-model-card.md). DOC-04 was used as a discovery index for DOC-05; it was not analyzed as a separate governance method.

## Initial NIST crosswalk

“Direct” means the artifact explicitly describes a practice or information area that closely corresponds to the NIST outcome subject. “Partial” means the artifact addresses a related aspect but not the full outcome. These labels are repository judgments, not NIST scoring or compliance categories. The mapping describes documentary alignment; it does not prove operational effectiveness.

| Artifact / passage | NIST reference | Mapping | Why this is a plausible link | What the artifact does not establish |
|---|---|---|---|---|
| DOC-01, A1.1: impact assessment early in system development; review and approval before development; annual/new-use/release-stage review (pp. 4–5) | MAP 5.1 | Direct | Requires documenting potential impacts on people, organizations, and society through an impact assessment | Does not show any individual assessment was completed or that impacts were comprehensively identified |
| DOC-01, A1.2: identified reviewers and required approvals before development (p. 4) | GOVERN 2.1 | Partial | Names a review/approval path related to responsible AI decisions | Does not by itself describe all roles, communication lines, or the full organization-wide accountability structure in the NIST outcome |
| DOC-01, A1.3: review at least annually, on new intended uses, and before a new release stage (p. 4) | GOVERN 1.5 | Direct | Specifies ongoing and event-triggered review of the impact assessment | Does not show that reviews occurred or how the wider risk-management process is monitored |
| DOC-02, Sections 1.2, 1.4–1.8: lifecycle stage, purpose, features, geography, deployment mode, intended uses (pp. 2–5) | MAP 1.1; MAP 2.1; MAP 3.3 | Direct / partial | Prompts the team to document system context, task/use, deployment setting, and scope | Does not establish that the answers are accurate or that all context-specific effects are captured |
| DOC-02, Section 2.2: stakeholders, potential benefits, and potential harms (p. 6 onward) | MAP 5.1 | Direct | Explicitly structures consideration of affected stakeholders and beneficial/harmful impacts | Does not provide validated likelihood/magnitude estimates or evidence that every affected group was identified |
| DOC-02, Section 4: data requirements and existing data-set suitability (pp. 13 onward) | MAP 2.3 | Partial | Prompts documentation of data requirements and available data-set quantity/suitability | Does not by itself demonstrate representativeness, scientific validity, or the complete NIST TEVV scope |
| DOC-03, “Ask,” “Inspect,” and “Audit” modules | MAP 2.3; GOVERN 5.1 (possible) | Partial / candidate | Describes creating data-documentation schemas with stakeholders, validating against real datasets, and including feedback | A learning toolkit does not prove adoption; stakeholder feedback may not be external to the development team, so GOVERN 5.1 fit must be established in the actual project |
| DOC-05, intended-use, known-limitations, and acceptable-use sections | MAP 2.2; MAP 3.3 | Direct | Documents model inputs/outputs, intended use, known limitations, and restricted integration/use contexts | Does not describe all downstream application contexts or how a deployer will oversee a specific use |
| DOC-05, evaluation approach, human and automated red teaming, and pre-release safety review | MEASURE 2.1; MEASURE 2.6; MEASURE 2.7 | Direct / partial | Publicly describes evaluation types and safety/security-focused red teaming | Does not publish full test sets, metrics, results, deployment conditions, residual-risk decision, or independent assurance; thus not full evidence for these outcomes |
| DOC-05, training-data overview and processing description | MAP 2.3 | Partial | Gives a high-level account of data modalities and some processing | Does not supply full provenance, representativeness, or suitability evidence for all intended uses |
| DOC-05, hardware / sustainability statements | MEASURE 2.12 | Partial / insufficient alone | Mentions training hardware and a sustainability commitment | Does not itself assess environmental impacts or sustainability outcomes as the NIST subcategory describes |

The application matrix is designed to support these distinctions: map a specific passage or artifact to a NIST reference, explain the relationship, and record limits or missing evidence. Where a link is only possible or partial, label it that way instead of force-fitting it.

## Cross-sample observations

1. **Several distinct artifact intents appear even in this small sample.** There is an organization-level standard, a reusable impact-assessment template, a dataset-documentation learning toolkit, and a model-specific transparency card. These serve different users and lifecycle purposes; they should not be collapsed into a single “AI governance document” category.
2. **Assessment and documentation prompts recur across the Microsoft artifacts**, while the Google artifacts emphasize dataset/model transparency, intended use, limits, and published evaluation descriptions. This is a pattern in this selected corpus only; it is not a prevalence conclusion about large companies.
3. **Documents can support different evidence claims.** The Microsoft standard states internal requirements; the template specifies what to record; the Google model card is an actual public artifact with source-reported evaluation content; the Data Cards Playbook is a method that someone could use. Their existence supports different conclusions.
4. **Public material has uneven granularity.** A standard or model card can summarize controls and evaluation while leaving underlying completed assessments, test data, decision records, or monitoring logs private. Do not infer the missing records.
5. **Crosswalks must allow partial and no mapping.** For instance, the Google toolkit is relevant to data documentation and collaboration, but the publication alone does not show that external feedback was gathered for a specific system under GOVERN 5.1.

## Evidence and interpretation limits

- This sample cannot validate either company’s full governance system, implementation consistency, or control effectiveness.
- A public standard evidences documented internal requirements, not necessarily their operation.
- A blank form evidences a designed record structure, not completion.
- A model card evidences a published description and the organization’s statements about model development/evaluation; the review does not independently reproduce those evaluations.
- The Data Cards Playbook is a reusable toolkit, not a company-specific completed data card.
- Source publication and access can change; records preserve the document date/status and access date used here.
- The sample covers two large U.S.-based technology organizations and does not represent deployers, regulated sectors, smaller organizations, or other regions.

## Next review

Use this initial scan to decide whether the matrix and record fields are understandable and useful for mapping actual artifacts. Before making claims about recurring document practice beyond this corpus, expand the sample to include at least one large deployer outside the AI platform/model-provider sector, select it using the same inclusion rules, and record any scope changes. Keep company-specific control assessments and implementation evidence in the relevant solution repositories.
