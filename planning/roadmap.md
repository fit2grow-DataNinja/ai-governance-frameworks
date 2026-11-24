# Learning and work roadmap

**Status:** Working sequence  
**Last reviewed:** 24 November 2026

This roadmap sequences learning and repository work. It is separate from [MVP scope and boundaries](mvp-scope.md), which defines what the repository is for.

## Phase 0 — Establish the repository foundation

**Status: Complete**

- Create the repository structure and define how it relates to the AI Services Portfolio and solution repositories.
- Record primary sources, source types, scope limits, and source-review conventions.
- Draft initial NIST and EU AI Act orientation pages, the EU evaluation matrix, and the screening record template.
- Add working status, roadmap, documentation standards, and a source-record template.

**Checkpoint:** Initial documents and clear boundaries are available for review.

## Phase 1 — Validate the screening record and EU matrix

**Status: Complete — source-mapped learning draft**

- Reviewed the consolidated EU AI Act text (27 July 2026 snapshot) and selected official Commission material on 23 November 2026.
- Updated the matrix and screening template to capture Article 6 conditions, provider/deployer and value-chain roles, distinct Article 50 duties, staged dates, and the difference between legal duties and suggested evidence.
- Cross-checked the cited transition dates against Articles 111 and 113; recorded the Article 50(2) transition under Article 111(4).
- Added seven source records and linked them from the [source register](../sources/source-register.md).
- Added open questions and a clear route for legal/factual issues that require qualified review.

**Checkpoint met:** Source-mapped working documents, source records, visible unresolved questions, and no claim of legal validation. Recheck the consolidated law and guidance before applying the material to a real deployment.

**Before v1.0:** Establish the matrix’s baseline version, release date, and legal-source snapshot. Confirm the matrix contains a reader-facing change record. After release, material changes must record the reason, affected content, and supporting source or use-case; see [versioning and change rationale](../governance/documentation-standards.md#versioning-and-change-rationale).

## Phase 2 — Review selected examples

**Status: Complete — bounded source review**

- Reviewed two NIST AI RMF use cases as reported applications: City of San José and Workday.
- Reviewed two European Commission AI literacy practices for Article 4 learning: VERBUND and OpenSky Data Systems; these are not treated as general AI Act project-evaluation cases.
- Added a source record for each selected example and for the Article 4 legal anchor.
- Recorded context, source claims, described actions/evidence, limits, and repository interpretation.
- Corrected the Article 4 checklist in the matrix to reflect the amended text in the 27 July 2026 consolidated Regulation, with the reason and source recorded in its change table.
- Decided whether the examples change framework notes, reusable methods, or the screening template.

**Checkpoint met:** Four example records and an Article 4 record are linked in the source register; the [Phase 2 review note](../working-documents/phase-2-example-review.md) captures the cross-case findings and decisions. The matrix received a targeted Article 4 wording correction; no new legal screen or broader restructuring was warranted. The examples remain reported learning inputs, not validated evidence or compliance determinations.

## Phase 3 — Develop traceable NIST AI RMF working documents

**Status: Initial two-company document scan complete — bounded findings recorded**

The detailed workflow is in the [NIST documentation-development approach](../working-documents/nist-ai-rmf-documentation-development-approach.md).

1. **Complete (24 Nov 2026):** Confirmed NIST AI RMF 1.0 remains the published baseline, revision is in progress, and the Playbook update will follow.
2. **Complete (24 Nov 2026):** Indexed all 72 Core subcategories and recorded the Profiles concepts for contextual tailoring and current/target comparison. The first draft uses a complete reference catalog with reasoned project-level selection.
3. **Drafts created (24 Nov 2026):** [NIST application matrix](../working-documents/nist-ai-rmf-application-matrix-draft.md) and [project assessment record](../templates/nist-ai-rmf-project-assessment-record.template.md), derived from NIST sources; Playbook content is labeled voluntary.
4. **Complete (24 Nov 2026):** Reviewed source fidelity and usability; see the [draft review log](../working-documents/nist-ai-rmf-draft-review-log.md).
5. **Complete for the initial bounded sample (24 Nov 2026):** Defined a purposive scan of Microsoft and Google DeepMind / Google, with scope and limits in the [scan note](../working-documents/nist-company-document-scan.md).
6. **Complete for the initial sample (24 Nov 2026):** Collected four inspectable artifacts: Microsoft Responsible AI Standard v2 and Impact Assessment Template; Google Data Cards Playbook and Gemini Omni Flash Model Card.
7. **Complete (24 Nov 2026):** Classified artifact intent and the evidence each can/cannot support; recorded source records SRC-015–SRC-018.
8. **Initial crosswalk complete (24 Nov 2026):** Mapped supported passages to Core points; retained partial/conditional mappings and evidence limits.
9. **Initial usability comparison complete (24 Nov 2026):** Existing template fields captured the evidence distinctions found; no change justified by this small sample. Broader sampling is needed before making wider recurrence claims.
10. **Complete for this sample (24 Nov 2026):** Recorded bounded findings and limitations without claims of implementation or effectiveness.

**Checkpoint:** Two reviewed NIST working-document drafts derived from NIST sources, followed by a crosswalk to selected company working materials, traceable rationales, and explicit evidence limits. The drafts are repository-created learning aids, not NIST-issued tools or compliance checklists.

**Optional companion resource:** The repository includes a separate company AI-governance document analysis method for cases where public material clearly connects company-stated principles, objectives, internal requirements, and supporting documents. It may inform source discovery or project-record evidence review, but it does not change the NIST-derived matrix or add a required NIST assessment step.

## Phase 4 — Apply the NIST materials to a bounded scenario

**Status: Complete — first retrospective assessment draft; owner review pending**

- Selected S02 Variant 1, a completed synthetic-data portfolio MVP with documented deterministic audit rules and a generative explanation component.
- Applied the reviewed NIST AI RMF 1.0 matrix and assessment record; searched official NIST Profiles and used the Generative AI Profile only as partial input for the explanation component.
- Recorded the project-specific assessment, evidence, limitations, and proposed actions in the [S02 solution repository](https://github.com/fit2grow-DataNinja/s02-crm-data-quality-auditor/blob/main/docs/nist-ai-rmf-retrospective-assessment.md).
- Marked target states as proposed, not company-agreed, because this is a self-directed portfolio project with no company representatives.
- Preserved existing MVP closure; the assessment does not authorize real-data or production use.

**Checkpoint met for the bounded portfolio exercise:** A dated, reviewable governance assessment demonstrates the method and its limits. Owner review and any improvements remain open.

## Phase 5 — Expand based on demonstrated need

**Status: Later**

Possible work includes a NIST/EU comparison on one scenario, a deeper data governance and privacy module, and North American materials. Add these only when they serve the learning plan or a concrete portfolio need.

## Updating the roadmap

Mark work complete only when its stated checkpoint is met. Record substantive changes in the repository status page and preserve project-specific evidence in the relevant project repository.
