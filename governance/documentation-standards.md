# Documentation standards

**Status:** Working convention  
**Last reviewed:** 19 November 2026

Adapted from the documentation conventions in the AI Services Portfolio. These standards apply to this governance knowledge repository; project-specific records remain authoritative in each solution repository.

## Document conventions

- Use Markdown, descriptive kebab-case filenames, clear headings, and relative links within the repository.
- Include document status and last-reviewed date where currency or maturity matters.
- State purpose, scope, assumptions, limitations, open questions, and next review step where relevant.
- Use precise legal citations (article/annex and regulation version) and framework references (function/category/subcategory and version) when available.
- Keep a single authoritative home for each document. Link to project evidence rather than copying it into this repository.

## Evidence and maturity labels

Separate these kinds of statements:

- **Binding legal text:** requirement in an applicable law or regulation.
- **Official guidance:** regulator or Commission explanation, tool, or recommendation; identify its status and limits.
- **Voluntary framework material:** framework outcome or suggested action, not automatically a legal duty.
- **Published example:** an organization’s reported practice or case; not automatically validated, endorsed, or transferable.
- **Repository interpretation:** our explanation, synthesis, or working question.
- **Project evidence:** implemented controls, test results, records, approvals, or other evidence in the solution repository.

For project control status, use **implemented**, **planned**, **not addressed**, or **not applicable**. “Implemented” requires a link or reference to evidence. A proposal, design note, or checklist entry is not implementation evidence.

## Required source-record practice

**Create and complete a record using the [source-record template](../templates/source-record.template.md) whenever we review an external source in depth or use it to substantively inform a repository document, governance decision, or use-case.** This includes a specific NIST or EU example selected for analysis, not just laws and framework publications.

A bare link may remain in the [source register](../sources/source-register.md) while it is only a research pointer and has not been reviewed or relied on. Once we examine it beyond an initial scan or use it to support or change our work, the source record is required. The record must distinguish the source’s statements from our interpretation and capture relevant scope, limitations, open questions, and follow-up.

This is a repository learning and traceability rule. It does not mean every link needs a full record before anyone can read it, and completing a record does not establish legal applicability or compliance.

## Versioning and change rationale

For a maintained matrix or reusable method, keep one current authoritative document unless a real need requires a separate jurisdictional or historical version. Git history preserves prior file states; it does not replace a reader-facing explanation of why the document changed.

Before declaring the EU AI Act matrix **v1.0**, establish its release date, version, and legal-source snapshot. After that baseline, record each material change in the matrix’s change record: date/version, reason, affected sections, and supporting source or use-case. Reasons may include changes to binding law, new or revised official guidance, lessons from an applied use-case, or correction of an error. Project-specific assessments should identify the matrix version and legal-source snapshot they used.

## Document lifecycle

- Mark new matrices, templates, and framework notes as drafts until their sources and scope have been reviewed.
- Track active and planned work in [the roadmap](../planning/roadmap.md); summarize current state in [PROJECT-STATUS.md](../PROJECT-STATUS.md).
- When a document is revised, update its review date and links, record material unresolved issues, and follow the versioning/change-rationale practice above where applicable.
- Do not call a working aid an official or complete compliance template unless the source establishes that status.
- Keep legal applicability decisions and project evidence with the relevant project repository; this repository contains reusable learning and methods.
