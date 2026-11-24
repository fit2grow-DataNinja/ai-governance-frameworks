# Developing traceable NIST AI RMF working documents

**Status:** NIST source baseline, Core inventory, two working-document drafts, draft review, bounded company-document scan, and first retrospective portfolio application completed; owner review of the applied assessment remains open.  
**Reviewed:** 24 November 2026  
**Framework baseline:** NIST AI RMF 1.0 (NIST AI 100-1), with the NIST AI Resource Center reporting that a revision is in progress.

## Purpose

Develop two reusable NIST working documents:

1. A **NIST AI RMF application matrix** that helps a reviewer select and reason about relevant outcomes for a defined use case.
2. A **NIST AI RMF project assessment record** that captures the use-case context, selected outcomes, evidence, gaps, actions, and decisions.

The documents may use a layout familiar from the EU AI Act matrix and screening template, but their purpose is different. The EU documents help identify potentially applicable legal duties. NIST documents will support a reasoned application of a voluntary risk-management framework; they do not classify legal obligations or determine compliance.

## Source basis and limits

- **NIST AI RMF Core:** the framework anchor for outcomes organized through GOVERN, MAP, MEASURE, and MANAGE. GOVERN is cross-cutting. The Core provides outcomes and actions, not a mandatory checklist or ordered sequence.
- **NIST AI RMF Profiles:** the basis for tailoring selected functions, categories, and subcategories to a specific setting, including the framework user's requirements, risk tolerance, and resources. Current and target profiles can help identify gaps. NIST does not prescribe profile templates.
- **NIST AI RMF Playbook:** a companion source for optional action suggestions tied to Core subcategories. These suggestions are voluntary, non-exhaustive, and not a required sequence.
- **Company-published documents:** a source of observed document practices and stated intent. Use them after the NIST-based drafts exist to assess documentary alignment and refine practical evidence fields. They do not establish what NIST requires or prove that a company's processes operate effectively.

See [SRC-013 — NIST AI RMF Core and Profiles](../sources/records/SRC-013-nist-ai-rmf-core-and-profiles.md), [SRC-014 — NIST AI RMF Playbook](../sources/records/SRC-014-nist-ai-rmf-playbook.md), the [NIST AI RMF Core outcome inventory](nist-ai-rmf-core-outcome-inventory.md), the [application matrix draft](nist-ai-rmf-application-matrix-draft.md), and the [project assessment record template](../templates/nist-ai-rmf-project-assessment-record.template.md).

## Working principles

- Start with the official NIST outcome and context; do not start by treating a company document as a requirement.
- Before creating a project-specific use-case profile, search official NIST sources for relevant published profiles and assess fit. Reuse, adapt, or combine suitable profiles where appropriate; if none fit or coverage is partial, tailor from the Core and record why. Distinguish published profiles from drafts/concept notes and from non-NIST profiles.
- The Phase 2 NIST case narratives and Commission literacy practice pages did not provide reusable working materials. Do not use their generic descriptions to derive template fields; assess any separately linked artifact as its own source.
- Anchor every proposed element first to a NIST outcome or an explicit portfolio need. Company documents may later inform the evidence examples or usability of the element, but do not establish NIST requirements.
- For each element, state its purpose, rationale, source, limits, and review trigger.
- Keep distinctions visible between **NIST framework content**, **voluntary Playbook suggestions**, **company-reported material**, **repository interpretation**, and **project evidence**.
- Use many-to-many mapping: one document or assessment field may support several NIST outcomes, and one outcome may be supported by several artifacts.
- Classify document intent from its stated purpose and substantive content, not from its title or keyword matches alone.
- Treat recurrence in the collected sample as an observed pattern, not a universal requirement or prevalence claim.
- Prioritize actual working materials. Generic success stories, use-case narratives, press releases, and high-level commitments are not evidence from which to derive template fields. If they link to a concrete artifact, assess that artifact separately.
- Do not infer that a public policy, framework, or report is implemented in practice unless the source supplies evidence for that claim.

## Step-by-step work plan

| Step | Task | Record or output | Completion check |
|---|---|---|---|
| **1. Fix the NIST source baseline** | **Completed 24 November 2026.** Confirmed AI RMF 1.0 (NIST AI 100-1) remains the published baseline; NIST says revision is in progress, and the Playbook will be updated afterward. | [NIST AI RMF Core outcome inventory](nist-ai-rmf-core-outcome-inventory.md) — source baseline section | Later mappings must identify the version and source checked; recheck before drafting is finalized. |
| **2. Extract the NIST structure** | **Core structure completed 24 November 2026.** Indexed all 72 subcategories under the Core’s functions and categories; recorded Profiles principles for context-based tailoring and current/target gap comparison. **Coverage decision:** retain all 72 as a reference catalog, with project-specific selection and rationale; the complete inventory does not imply universal applicability. | [NIST AI RMF Core outcome inventory](nist-ai-rmf-core-outcome-inventory.md) | Each selected point must be anchored to NIST; the inventory does not imply every outcome applies to every use case. |
| **3. Draft the working documents from NIST** | **First drafts created 24 November 2026.** The matrix retains all 72 AI RMF 1.0 subcategories as a reference catalog and requires project-specific selection and rationale; the assessment record captures context, per-outcome disposition, main-focus/sub-focus grouping, evidence, gaps, actions, and decisions. Playbook suggestions are clearly voluntary. Profile availability review is now a required project-level step before defining a new use-case profile: assess published NIST profiles first, then reuse/adapt/combine if suitable or record why additional tailoring is needed. | [Application matrix draft](nist-ai-rmf-application-matrix-draft.md); [project assessment record template](../templates/nist-ai-rmf-project-assessment-record.template.md) | The structure is NIST-source-grounded; repository-created prompts, evidence fields, and statuses are identified as such. Source-fidelity and usability review remains pending. |
| **4. Review source fidelity and usability** | **Completed 24 November 2026.** Reviewed the 72-outcome coverage, repository/NIST distinctions, Profile workflow, and outcome-disposition/focus design. Corrected one example table row. | [NIST draft review log](nist-ai-rmf-draft-review-log.md) | The drafts support context-based selection and current/target comparison without implying a NIST checklist or score. |
| **5. Define the company-document review** | **Completed for an initial sample 24 November 2026.** Defined a purposive, English-language scan of two large U.S.-based AI technology providers, selected for accessible standards, an assessment template, model documentation, and a data-documentation toolkit. | [NIST company-document scan](nist-company-document-scan.md) | Scope, sources checked, inclusion rules, and limits are explicit. This sample does not represent other sectors or regions. |
| **6. Collect actual public working materials** | **Initial collection completed 24 November 2026.** Reviewed the Microsoft standard and assessment template, Google Data Cards toolkit, and Google DeepMind model card. | [NIST company-document scan — inventory](nist-company-document-scan.md#document-inventory-and-intent-classification) | Each item has an official source, date/status, intent, and evidence limit. The scan is bounded, not an exhaustive company-site crawl. |
| **7. Classify document intent and evidence** | **Completed 24 November 2026.** Classified each artifact as an internal standard, assessment template, learning toolkit, or model-specific public documentation; separated what the artifact documents from what it proves. | [NIST company-document scan](nist-company-document-scan.md) and [source records SRC-015–SRC-018](../sources/source-register.md#nist-company-document-scan-source-records) | A standard is not treated as proof of consistent operation; blank templates and toolkits are not treated as completed control evidence. |
| **8. Map company materials back to NIST** | **Initial crosswalk completed 24 November 2026.** Mapped selected passages to Core references and labeled direct, partial, or conditional relationships; stated what each passage does not establish. | [Initial NIST crosswalk](nist-company-document-scan.md#initial-nist-crosswalk) | Mappings are rationale-based documentary alignment, not a score, compliance result, or validation of control operation. No link is forced where support is weak. |
| **9. Refine the drafts using the scan** | **Initial usability comparison completed 24 November 2026.** The scan’s artifact-intent and evidence distinctions are already captured by the assessment record’s evidence-type/limits fields and the source-review workflow; no matrix field change was justified by this small sample. | [NIST draft review log](nist-ai-rmf-draft-review-log.md); [company-document scan](nist-company-document-scan.md) | Any future field change must cite an observed usability need and remain distinct from NIST content. Expand the sample before treating document patterns as recurring beyond these organizations. |
| **10. State conclusions and limitations** | **Initial bounded findings recorded 24 November 2026.** The scan reports distinct artifact intents and limited repeated patterns within the two-company sample, with publication bias and no implementation/effectiveness validation. | [NIST company-document scan](nist-company-document-scan.md#cross-sample-observations) | Conclusions are explicitly limited to this selected corpus; broader recurrence claims require a broader sample. |
| **11. Apply after review** | **Completed 24 November 2026 (first retrospective draft).** Applied the reviewed documents to S02 Variant 1, a synthetic-data CRM audit with deterministic Python findings and hosted generative explanations. The record keeps project-specific findings in the S02 solution repository, identifies NIST AI 600-1 as partial profile input, and distinguishes documented evidence from assumptions and proposed targets. No company representatives participated, so the Target Profile is explicitly not organization-agreed. | [S02 Variant 1 retrospective assessment](https://github.com/fit2grow-DataNinja/s02-crm-data-quality-auditor/blob/main/docs/nist-ai-rmf-retrospective-assessment.md) | The record is a bounded portfolio draft; it does not validate controls or assess an actual organization. Owner review is pending. |

## Project-level NIST Profile workflow

The following sequence makes explicit how an assessment uses NIST Profiles. It is a repository-designed workflow based on NIST’s Profile concepts; NIST does not prescribe this sequence or a Profile template.

1. **Define the project setting and goals.** Describe the system, intended use, actors and affected people, lifecycle stage, organizational goals, risk tolerance, and available resources.
2. **Search for existing NIST profiles first.** Check current official NIST sources for published profiles relevant to the technology, sector, use case, or cross-sector activity. Record the search date and each candidate’s source, version, status, scope, and relevance. Distinguish published profiles from drafts or concept notes in development; label profiles from other organizations as external, not NIST profiles.
3. **Decide whether and how to reuse them.** For each relevant candidate, document whether it will be reused, adapted, combined with another profile, used as partial input, or not used. Explain fit, limitations, and uncovered needs. Do not assume a profile is suitable simply because the technology or sector label matches.
4. **Define the tailored outcome set.** Use the suitable profile or profiles as a starting point, then select and tailor Core functions, categories, and subcategories for the project. If no published NIST profile is suitable, or coverage is incomplete, create a project-specific use-case profile from the Core and explain the rationale. Apply the project’s Main focus / Sub-focus grouping as a portfolio overview aid.
5. **Describe Current and Target Profiles.** For each selected outcome, establish the Current Profile from available information and evidence. Then develop the Target Profile through discussion with relevant company representatives, using the Current Profile as context and considering organizational goals, priorities, risk tolerance, context, and resources. Record contributors and their roles, the decision owner, whether each target is proposed/agreed/approved/unresolved, and any disagreement. Distinguish a proposed target from a company-approved target. Do not mistake a profile source’s suggested actions for automatically required target outcomes.
6. **Compare profiles and plan.** Identify gaps between current and target states, note evidence limits and residual risks, and prioritize actions according to the project’s needs, risk-management process, and resources.

The [project assessment record](../templates/nist-ai-rmf-project-assessment-record.template.md) captures the profile search, reuse decision, selected Core outcomes, current/target states, and resulting gaps. The [application matrix](nist-ai-rmf-application-matrix-draft.md) supplies the complete Core reference catalog and prompts.

## Traceability fields for each proposed template element

| Traceability item | What to record |
|---|---|
| Template field / prompt | The question, field, status, or evidence item being proposed |
| NIST anchor | Function, category, and subcategory; use the exact reference where possible |
| External basis | Core, Profile, Playbook suggestion, or a specific organization-published document |
| Source location | URL and page/section/passage, with publication/version and access date |
| Intent and rationale | What the field is meant to help assess or record, and why it belongs |
| Element type | NIST outcome; optional Playbook suggestion; observed practice; repository-created prompt; or project evidence |
| Evidence and limits | Evidence the field can capture, and what that evidence does not prove |
| Mapping rationale | Why this field maps to the selected NIST outcome(s); allow multiple links |
| Maintenance trigger | Source revision, material new evidence, or applied-use finding that prompts review |

## Maintenance and change control

- Check NIST’s current status before starting or revising a template. A revised AI RMF or material Profile/Core change triggers review of all mapped elements.
- A Playbook revision triggers review of fields that rely on its suggestions; do not automatically change Core-aligned fields.
- New or revised company documents trigger review only where they materially affect the observed taxonomy or a template rationale.
- Applied scenario findings may prompt a change proposal; project evidence remains in the solution repository, and changes to reusable material require a recorded reason and source.
- Maintain one current version of each working document. After a v1.0 baseline, record material changes with date/version, reason, affected elements, and source or project evidence. Preserve prior states in Git history.
- Review cadence is not yet fixed. Decide it when the first NIST working documents are drafted, balancing NIST update triggers with periodic source maintenance.

## Open design decisions

- Which industries, geographies, and provider/deployer contexts should the initial company sample cover?
- What minimum inclusion standard distinguishes a governance-relevant document from general AI marketing or product documentation?
- **Resolved for the first draft:** retain all 72 subcategories as a reference catalog and use project-specific selection with recorded rationale; this is not a requirement that every outcome apply. Revisit after usability review.
- What review cadence is practical once the NIST documents reach v1.0?

## Use limitation

These planned documents will be repository-created learning aids aligned to a selected NIST AI RMF version. They will not be NIST-issued tools, a universal checklist, certification, legal advice, or proof that an organization or system manages risk effectively.
