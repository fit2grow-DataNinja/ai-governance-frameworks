# Developing traceable NIST AI RMF working documents

**Status:** Source baseline and Core outcome inventory completed; first drafts of the NIST application matrix and project assessment record created for review.  
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
| **2. Extract the NIST structure** | **Core structure completed 24 November 2026.** Indexed all 72 subcategories under the Core’s functions and categories; recorded Profiles principles for context-based tailoring and current/target gap comparison. **First-matrix coverage decision remains open** and will be made during drafting. | [NIST AI RMF Core outcome inventory](nist-ai-rmf-core-outcome-inventory.md) | Each selected point must be anchored to NIST; the inventory does not imply every outcome applies to every use case. |
| **3. Draft the working documents from NIST** | **First drafts created 24 November 2026.** The matrix retains all 72 AI RMF 1.0 subcategories as a reference catalog and requires project-specific selection and rationale; the assessment record captures context, status, evidence, gaps, actions, and decisions. Playbook suggestions are clearly voluntary. | [Application matrix draft](nist-ai-rmf-application-matrix-draft.md); [project assessment record template](../templates/nist-ai-rmf-project-assessment-record.template.md) | The structure is NIST-source-grounded; repository-created prompts, evidence fields, and statuses are identified as such. Source-fidelity and usability review remains pending. |
| **4. Review source fidelity and usability** | Check that NIST outcomes are represented accurately, the tools support context-based tailoring, current/target comparison and gaps, and no field implies a NIST-mandated checklist or score. | Draft review log | Representative fields trace to exact NIST references and their intended use is clear. |
| **5. Define the company-document review** | Set the research question, date range, geography, sectors, organization roles, meaning of “larger company,” inclusion/exclusion criteria, and a purposeful sample. Prioritize organizations publishing actual operational artifacts. Do not claim the sample represents all companies. | Scope note and company sample register | The scope and sampling limits are explicit and reproducible. |
| **6. Collect actual public working materials** | Search official company sites and document libraries for operational policies/standards, procedures, assessment tools, lifecycle requirements, model/system documentation, testing materials, data-governance controls, human-oversight instructions, supplier questionnaires, incident/monitoring processes, transparency specifications, or literacy curricula. Generic narratives and principles statements are not working artifacts; assess a separately linked artifact on its own. | Document inventory with source links and metadata | Each included document has publisher, URL, title, date/version, access date, scope, status, and a reason it qualifies. |
| **7. Classify document intent and evidence** | Record each document’s stated and substantive intent. Separately classify what it evidences: a commitment or policy, a defined process, a record of operation such as completed assessments or test results, or independent assurance. These are repository-created evidence labels, not NIST categories. | Intent taxonomy and evidence notes | Each classification cites the relevant passage. A policy statement is not described as proof that a control operates. |
| **8. Map company materials back to NIST** | Map supported passages or artifacts to NIST function/category/subcategory references. Allow one-to-many and many-to-many mappings, partial support, and no supported mapping. Do not force-fit a document or treat frequency as a requirement. | Company-document-to-NIST crosswalk | A reader can trace each mapping from the artifact passage to the NIST point and understand the rationale and confidence. |
| **9. Refine the drafts using the scan** | Use the crosswalk to identify practical evidence types, unclear fields, or useful gaps in the drafts. Add or change an element only with a recorded rationale; keep NIST content, Playbook suggestions, company-published material, and repository interpretation distinct. | Revised drafts and change notes | The documents remain NIST-anchored; company materials inform documentary usability, not what NIST requires. |
| **10. State conclusions and limitations** | Report what the collected documents show about published documentary alignment and available evidence. Record missing internal material, selection/publication bias, self-reported claims, and unverified operation or effectiveness. | Bounded findings note | Conclusions do not claim an organization’s implementation or effectiveness is validated unless the evidence supports that stronger claim. |
| **11. Apply after review** | Once the working documents are reviewable, apply them to a bounded portfolio scenario. Keep project-specific assessment, evidence, decisions, and implementation status in the relevant solution repository; label retrospective assessments with date and source/framework versions. | Scenario assessment and linked repository evidence | The assessment uses the actual draft version and distinguishes documented facts from assumptions and planned controls. |

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
