# Project status — AI Governance Frameworks

**Last updated:** 2026-11-24  
**Stage:** Repository foundation established; Phases 1–3 complete; first bounded NIST use-case assessment draft completed for S02 Variant 1; owner review next.  
**Status:** Active learning and documentation project. Working documents are issue-spotting drafts, not validated compliance tools.

## Purpose

Build a source-grounded AI governance knowledge base and portfolio showing how frameworks inform AI solution design and delivery. The repository complements the AI Services Portfolio and the separate solution repositories.

## Completed foundation

- Initial repository hierarchy, scope boundaries, and repository relationship documented.
- Source register and source-review workflow established.
- Initial NIST AI RMF and EU AI Act orientation pages added.
- EU AI Act project-evaluation matrix and project-screening record template drafted.
- Governance-specific status, roadmap, documentation standards, and source-record template added.

## Current review status

- Reviewed the consolidated EU AI Act text snapshot dated 27 July 2026 and selected official Commission guidance on 23 November 2026.
- Revised the EU matrix and screening record for Article 6 classification details, actor/value-chain roles, Article 50 distinctions, staged dates, and evidence labeling.
- Cross-checked cited transition dates against Articles 111 and 113; corrected the Article 50(2) transition reference to Article 111(4).
- Added and linked seven Phase 1 source records in the [source register](sources/source-register.md).
- Phase 1 is complete as a **source-mapped learning draft**. Open legal/factual questions are listed in the matrix; this work does not validate compliance or settle how the Act applies to a specific system.
- The classification guidelines reviewed are draft guidance, and the Article 27 FRIA template is draft consultation material; neither is represented as adopted binding law.
- Added five Phase 2 source records: Article 4 and the City of San José, Workday, VERBUND, and OpenSky examples.
- Completed the [Phase 2 example review](working-documents/phase-2-example-review.md). It records cross-case observations and one targeted correction to the Article 4 checklist in the matrix.
- The Article 4 checklist now follows the 27 July 2026 consolidated wording: measures support development of literacy, context and affected groups matter, and no individual literacy level must be guaranteed. The change is recorded in the matrix change table and [SRC-008](sources/records/SRC-008-ai-act-article-4-ai-literacy.md).
- Phase 2 review found that the selected NIST case narratives and Commission literacy practice pages do not provide working materials we can reuse. Keep them as documented examples and source-limit records; do not derive template fields from their generic summaries. NIST also states that it does not validate or endorse individual use cases, and the Commission says copying a literacy practice does not automatically create a presumption of Article 4 compliance.
- The matrix and template remain repository-authored learning aids, not legal advice or proof of compliance.
- Project-specific application, controls, decisions, and evidence belong in the relevant solution repository.
- No governance use-case has been completed yet; the `use-cases/` directory remains reserved.
- Rechecked the NIST source baseline on 24 November 2026: AI RMF 1.0 remains the published baseline while revision is in progress; the Playbook update will follow the revised Framework.
- Created a complete 72-subcategory [NIST AI RMF Core outcome inventory](working-documents/nist-ai-rmf-core-outcome-inventory.md), plus the [application matrix](working-documents/nist-ai-rmf-application-matrix-draft.md) and [project assessment record](templates/nist-ai-rmf-project-assessment-record.template.md). The assessment record groups selected outcomes into Main focus and Sub-focus points while retaining a disposition for all 72; this portfolio hierarchy is not a NIST ranking or requirement.
- Completed the NIST [draft source-fidelity and usability review](working-documents/nist-ai-rmf-draft-review-log.md), including a small table-format correction.
- Completed an initial bounded [company-document scan](working-documents/nist-company-document-scan.md) of Microsoft and Google DeepMind / Google. It inventories four artifacts, classifies their intent, and maps supported passages to NIST Core points. Findings are limited to this purposive sample and do not validate company implementation or effectiveness.
- Added source records SRC-015–SRC-018 for the Microsoft standard and assessment template, Google Data Cards Playbook, and Google DeepMind model card; linked them from the [source register](sources/source-register.md).
- Applied the NIST working drafts retrospectively to S02 Variant 1. The [assessment record](https://github.com/fit2grow-DataNinja/s02-crm-data-quality-auditor/blob/main/docs/nist-ai-rmf-retrospective-assessment.md) identifies NIST AI 600-1 as partial profile input and records all 72 Core dispositions. Targets remain portfolio-proposed because no company representatives participated.
- Added [SRC-019 — NIST Generative AI Profile](sources/records/SRC-019-nist-generative-ai-profile.md) and linked it from the source register.
- Added an [optional company AI-governance document analysis method](working-documents/nist-company-ai-governance-document-analysis.md) as a complementary resource. It is not a NIST method or required assessment step; it may help organize company-stated governance intent and identify original sources relevant to a project record.

## Next focus

Review the S02 retrospective assessment draft and decide whether the method needs refinement before applying it to another use case. Expand the company-document sample only if it will improve the analysis. Keep the distinction between documented alignment and available evidence versus validated operation or effectiveness. The process is in the [development approach](working-documents/nist-ai-rmf-documentation-development-approach.md), and sample limits are in the [company-document scan](working-documents/nist-company-document-scan.md).

## Evidence and status conventions

Distinguish binding legal text, official guidance, voluntary framework suggestions, published examples, repository interpretation, and project evidence. Mark project controls as **implemented**, **planned**, **not addressed**, or **not applicable**, with evidence for implemented claims.

This status page summarizes repository-level progress. It does not assert that any system complies with the EU AI Act, NIST AI RMF, or other law or framework.
