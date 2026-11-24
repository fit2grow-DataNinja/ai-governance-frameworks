# Optional company AI-governance document analysis

**Status:** Optional complementary method; repository-created and not prescribed by NIST  
**Use with:** NIST AI RMF company-document scans and, when relevant, project assessment records

## Purpose

This method provides an optional way to analyze a company’s publicly available AI-governance materials when they describe a sufficiently clear internal structure. It organizes the company’s own stated:

**AI principles → AI goals or objectives → internal requirements or practices → supporting documentation, where identified**

The structure is an analytical lens for tracing how a company says its AI-governance intent is put into practice. It is not a universal company model, a NIST method, or a required part of applying the NIST AI RMF. A company may use different terms, omit a layer, or connect elements in a many-to-many way. Preserve the company’s wording and record only relationships supported by the material; do not force a missing layer or one-to-one chain.

Use the method only when it adds useful traceability beyond a basic source record. If the public material does not make the structure clear, record the source and its limits without completing this analysis.

## Scope and boundaries

- Focus on AI-specific governance material, such as a public AI policy, responsible AI standard, handbook, assessment template, or governance document.
- Do not require a company’s general vision, mission, or strategy as an input. Record broader corporate context only when the company explicitly connects it to its AI-governance material or it is independently relevant to a defined NIST project assessment.
- Distinguish company-stated principles, objectives, requirements, and documents from our interpretation of how they relate.
- Distinguish internal company requirements from NIST outcomes, law, official guidance, and other external standards. The method does not determine legal applicability or compliance.
- Treat public policies and standards as evidence of what is documented. Their existence alone does not show that a process was followed or that controls operated effectively.
- Treat a company’s worked use-case narrative as an illustrative example unless the source provides evidence that the activity was completed for an actual system.
- Keep company-wide public-document analysis separate from project-specific control assessment and implementation evidence. Project-specific assessment evidence belongs in the relevant solution repository.

## Relationship to the NIST AI RMF

The NIST AI RMF remains the source for the NIST Core and the project-level outcome review. This optional analysis can complement a NIST assessment in two limited ways:

1. **Source discovery and context:** identify company-published policies, processes, templates, and stated expectations that may be relevant to a project.
2. **Documented current-state input:** where a source is relevant to the assessed project, cite the original artifact in the NIST project assessment record and explain what it supports and what it does not establish.

Where a mapping to a NIST Core outcome is useful, explain the relationship and label it as a repository analysis. Do not treat the company’s hierarchy as a NIST Profile, use it to determine NIST outcome applicability, or let it set the Target Profile automatically. The Target Profile remains context-specific and should be developed with relevant company representatives using the Current Profile as context, as described in the [NIST project assessment record](../templates/nist-ai-rmf-project-assessment-record.template.md).

A separate company-document analysis is an interpretive index, not primary evidence. In the project record, cite the original company source in the evidence register; use the analysis to help navigate or interpret it.

## Analysis workflow

1. **Set the review scope.** Record the organization, review purpose, date, relevant business or AI context if known, and the documents included. State whether the analysis concerns an organization-wide governance approach or a particular system/use case.
2. **Inventory the sources.** For each artifact, record publisher, exact title, document type, publication/version date, URL, access date, and whether the full content was available for review. Use the repository’s [source-record template](../templates/source-record.template.md) for detailed source notes.
3. **Capture the company’s own structure.** Identify the terms and relationships the source explicitly uses. Classify an element as a principle, goal/objective, internal requirement/practice, or supporting document only when the source supports that interpretation. Preserve original labels.
4. **Record links and visibility separately.** Mark whether each relationship is explicit, analyst-inferred, or not established. Record whether a supporting document is available and reviewed, named but unavailable, or not identified in the material reviewed.
5. **Assess the evidence type and limits.** Distinguish stated commitment or policy, described process, reusable template/tool, worked example, completed assessment/activity record, operational evidence, and independent assurance. State what the material does not establish.
6. **Optionally map to NIST.** Map only where a specific NIST Core outcome is plausibly supported. Explain the rationale and use direct, partial, possible, or no mapping as repository analysis labels—not NIST scores or compliance categories. A company document may support multiple outcomes, and an outcome may be reflected in several documents.
7. **Decide whether the analysis helps.** If the source structure is too opaque or the mapping adds no practical understanding, retain the source record and stop. Do not expand the NIST matrix or project record just to accommodate a weak mapping.
8. **Carry relevant sources into a project assessment only when appropriate.** Confirm that an organization-wide artifact applies to the assessed project. Record the original source and its limitations in the NIST record’s evidence register; do not substitute the analysis note for project evidence.

## Suggested analysis table

| Company’s term / element | Analytical level (if supported) | Stated aim or content | Source and location | Relationship to other elements (explicit / inferred / not established) | Supporting document and availability | Evidence type and limits | Optional NIST reference and mapping rationale |
|---|---|---|---|---|---|---|---|
| | Principle / goal or objective / internal requirement or practice / supporting document / other | | | | | | |

Use multiple rows where one element connects to several others. Do not label a missing item “not applicable” merely because it was not found in the documents reviewed.

## Status conventions

These status dimensions answer different questions and should not be collapsed into one maturity or compliance rating:

| Dimension | Suggested labels | Meaning |
|---|---|---|
| Element visibility | Explicitly stated / partially described / not found in reviewed material / source unavailable | Whether the element can be seen in the material reviewed; “not found” does not mean it does not exist internally |
| Relationship | Explicitly linked by the company / inferred by the reviewer / not established | Whether the source itself connects the elements |
| Supporting artifact | Available and reviewed / named but unavailable / not identified in reviewed material | Whether the referenced document can be examined |
| Evidence type | Policy or commitment / described process / template or tool / worked example / completed record / operational evidence / independent assurance | What kind of evidence the source provides; this does not by itself establish effectiveness |

## Reporting

State:

- which sources and versions were reviewed;
- which hierarchy elements and relationships were explicit versus inferred;
- what supporting documents were available or unavailable;
- any optional NIST mapping and its rationale;
- what the analysis cannot establish; and
- whether it supplied useful context or evidence leads for a project assessment.

Do not report the result as a company maturity level, NIST score, EU AI Act compliance status, or assurance conclusion.

## Use limitation

This is an optional repository-created analysis method for organizing public company AI-governance documentation. It is not part of the NIST AI RMF, does not add NIST requirements, and does not establish that a company or system implements its stated governance approach effectively.
