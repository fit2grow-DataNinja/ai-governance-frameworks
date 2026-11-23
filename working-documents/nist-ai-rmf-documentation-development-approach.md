# Developing traceable NIST AI RMF working documents

**Status:** Approach established; the NIST application matrix and project assessment record are not yet drafted.  
**Reviewed:** 23 November 2026  
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
- **Company-published documents:** a source of observed document practices and stated intent. They can inform possible evidence fields and examples; they do not establish what NIST requires or prove that a company's processes operate effectively.

See [SRC-013 — NIST AI RMF Core and Profiles](../sources/records/SRC-013-nist-ai-rmf-core-and-profiles.md) and [SRC-014 — NIST AI RMF Playbook](../sources/records/SRC-014-nist-ai-rmf-playbook.md).

## Working principles

- Start with the official NIST outcome and context; do not start by treating a company document as a requirement.
- The Phase 2 NIST case narratives and Commission literacy practice pages did not provide reusable working materials. Do not use their generic descriptions to derive template fields; assess any separately linked artifact as its own source.
- Trace every repository-created element to an external source, an observed document practice, or an explicit portfolio need.
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
| **1. Confirm the research scope** | Define the question, date range, geography, sectors, organization roles (provider/deployer or both), and what “larger company” means for this scan. Bound the scan to public, organization-published documents located through a documented search process; it cannot cover internal documents or prove completeness of a company’s full documentation set. | Short scope and inclusion/exclusion note | Another reader can tell what was searched, when, and what was out of scope. |
| **2. Select a purposeful company sample** | Choose a small, diverse sample of larger organizations with discoverable AI governance materials, prioritizing those that publish operational artifacts rather than only narratives or principles. Seek variation across sectors, geographies, and provider/deployer roles. Record why each organization was selected. Do not claim the sample represents all companies. | Company sample register | Each selection has a stated rationale; sample limitations are explicit. |
| **3. Collect and register public documents** | Search official company sites and document libraries for actual AI governance working materials. Prioritize policies/standards that operationalize controls, governance procedures, risk or impact assessment forms, lifecycle requirements, system/model documentation, testing/evaluation protocols and reports, data-governance procedures, human-oversight instructions, supplier/procurement questionnaires, incident/monitoring procedures, transparency specifications, and literacy curricula or assessment materials. Record generic case narratives and principles statements only as context; do not treat them as reusable artifacts. Save title, publisher, URL, date/version, access date, stated scope, document status, and why the item qualifies as a working material. | Document inventory with source links and metadata | Included items are traceable to their publisher and review date; out-of-scope items have a reason for exclusion. |
| **4. Classify each document by intent** | Record the document’s primary stated intent and any secondary intents. Classify what it aims to do (for example, set policy, allocate responsibilities, assess impact, test performance, disclose system information, or manage incidents). Keep claims, process descriptions, evidence, and future plans distinct. | Document-intent taxonomy and classification rationale | Every classification is supported by the artifact’s stated purpose and substantive content; generic narrative-only sources do not qualify as working materials, and ambiguous cases remain marked uncertain. |
| **5. Map documents to NIST outcomes** | Map relevant passages or described processes to NIST Core function/category/subcategory references. Add Playbook suggestions only as optional supporting material. Link each mapping to a page, section, or passage; allow multiple mappings and record “no supported mapping” when appropriate. | Evidence-to-outcome crosswalk | A reviewer can follow each mapping from source passage to NIST reference and see why it was assigned. |
| **6. Compare patterns and limits** | Identify recurring working-document intents and artifact types within the sample, variation by organization/context, and NIST outcomes that the public materials do or do not make observable. Do not count narrative-only case summaries as artifacts. Record publication and selection bias, missing internal documents, marketing language, and unverified implementation. | Bounded findings note | Findings describe only the sampled publications; frequency is not treated as proof of importance, effectiveness, or universal practice. |
| **7. Derive the application matrix and assessment record** | For every proposed field or prompt, document its NIST reference, external source(s), reason for inclusion, expected use/evidence, status as NIST text/Playbook suggestion/observed practice/repository interpretation, and change trigger. Include a rationale when a relevant outcome is combined, adapted, or omitted. | Draft NIST application matrix and project assessment record | No field is presented as NIST-mandated without a direct source; each element has traceable rationale and limits. |
| **8. Review and refine the drafts** | Check source links and version, consistency of document-intent coding, clarity of current/target status, and whether the templates invite context-based selection rather than blanket completion. Review ambiguous classifications and revise the taxonomy or instructions where needed. | Review log and revised drafts | A reviewer can trace representative fields end to end and understand how to record uncertainty and evidence gaps. |
| **9. Apply only after review** | Once the NIST documents are reviewable, apply them to a bounded portfolio scenario. Keep project-specific assessment, evidence, decisions, and implementation status in the relevant solution repository; label retrospective assessments with date and source/framework versions. | Scenario assessment and linked repository evidence | The assessment uses the actual draft version and distinguishes documented facts from assumptions and planned controls. |

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
- Should the first application matrix cover all NIST 1.0 subcategories, or provide a selection-oriented guide with a complete reference crosswalk?
- What review cadence is practical once the NIST documents reach v1.0?

## Use limitation

These planned documents will be repository-created learning aids aligned to a selected NIST AI RMF version. They will not be NIST-issued tools, a universal checklist, certification, legal advice, or proof that an organization or system manages risk effectively.
