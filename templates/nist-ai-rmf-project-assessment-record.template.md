# NIST AI RMF project assessment record — template

**Template status:** Draft; repository-created learning aid, not NIST-issued  
**Framework baseline:** NIST AI RMF 1.0, NIST AI 100-1 (2023)  
**Source status checked:** 24 November 2026; NIST reports revision in progress  
**Related matrix:** [NIST AI RMF application matrix — draft](../working-documents/nist-ai-rmf-application-matrix-draft.md)  
**Related source index:** [NIST AI RMF Core outcome inventory](../working-documents/nist-ai-rmf-core-outcome-inventory.md)

> Complete one record for a defined system or use case. This document supports a context-specific application of a voluntary risk-management framework. It does not establish legal compliance, certification, implementation effectiveness, or a NIST determination.

## 1. Record control

| Field | Entry |
|---|---|
| Assessment record ID | |
| Project / system name | |
| Record owner | |
| Contributors / reviewers | |
| Assessment date and status | |
| Related solution repository or project record | |
| Matrix version / commit / date | |
| Framework source version | NIST AI RMF 1.0, NIST AI 100-1 (2023), unless revised and specified |
| Source baseline rechecked on | |
| Assessment type | ☐ Planned ☐ In progress ☐ Retrospective ☐ Update / reassessment |
| Prior assessment / change reference | |

## 2. System and use context

| Prompt | Record |
|---|---|
| What system or proposed system is being assessed? | |
| What business or public-interest need is it intended to address? | |
| What are the intended purpose, users, and expected decisions/actions? | |
| What uses are outside the intended scope or prohibited? | |
| What AI methods/components are involved (e.g., classifier, recommender, generative model, external service)? | |
| What are the system boundaries and relevant dependencies, including data, software, models, vendors, and integrations? | |
| What lifecycle stage(s) are covered (idea, acquisition, design, development, testing, deployment, operation, change, retirement)? | |
| What geography, sector, organizational setting, and deployment environment matter? | |
| Who may be affected directly or indirectly? Include relevant groups and potential benefits and harms. | |
| What human roles, oversight, review, override, or appeal are expected? | |
| What important assumptions, limitations, uncertainties, or foreseeable changes apply? | |
| What non-AI alternatives or existing processes are relevant? | |

## 3. Profile search, selection, and tailoring

Before creating a project-specific use-case profile, search current official NIST sources for published profiles or profile materials relevant to the system’s technology, sector, use case, or cross-sector activity. An existing profile is a starting point to assess for fit; it does not automatically define this project’s applicable outcomes or target state.

Distinguish a published NIST profile from a NIST concept note or draft in development and from a profile published by another organization. External profiles may be considered separately as supplementary sources, but must not be presented as NIST profiles. Record the source and status as of the date checked.

| Candidate profile / source | Publisher and status (published / draft / concept / external) | Scope and relevant risks | Fit to this project | Decision (reuse / adapt / combine / supplement / not use) | Rationale, limitations, and remaining gaps |
|---|---|---|---|---|---|
| | | | | | |

**Profile search conclusion:** ☐ Suitable NIST profile reused ☐ One or more profiles adapted/combined ☐ Profile used as partial input and project-specific tailoring added ☐ No suitable published NIST profile identified; tailored profile developed from the Core

**Search record:** official NIST sources checked, search date, version/date of profile(s), and relevant pages or documents: ______________________________________

If no published NIST profile fits, or a profile only partly fits, define a project-specific profile by tailoring Core outcomes to this context. Explain what was retained, adapted, supplemented, or omitted. Do not treat a draft or concept note as a finalized profile.

### 3.1 Assessment scope and tailoring rationale

Describe the purpose and boundaries of this assessment. State which lifecycle stages and system components are included or excluded and why.

| Tailoring factor | Assessment notes |
|---|---|
| User and organizational requirements | |
| Context-specific laws, norms, and expectations identified (not a legal opinion) | |
| Organizational risk tolerance or applicable decision basis | |
| Available capabilities, expertise, time, and resources | |
| System capability, knowledge limits, and intended scope | |
| Relevant affected parties and perspectives sought | |
| Framework outcomes selected for detailed assessment | |
| Current Profile — how risk is currently managed for selected outcomes; summarize findings and link to outcome rows/evidence | |
| Target Profile — desired outcomes for selected outcomes, developed with relevant company representatives using the Current Profile as context | |
| Representatives consulted (names or roles), their relationship to the system, and key input | |
| Target Profile decision owner(s), approval status, and date; note any disagreement or unresolved item | |
| Outcomes considered but not selected and why | |
| Outcomes deferred or unable to assess, and what would resolve the gap | |

NIST defines use-case profiles as context-specific implementations of selected Core functions, categories, and subcategories, and Current/Target Profiles as descriptions of existing and desired states. Comparing them can reveal gaps. This record’s profile search workflow, fields, and status labels are repository-created; NIST does not prescribe this template. The collaborative target-setting steps below are also this repository’s proposed practice, not a NIST-mandated consultation or approval procedure.

## 4. Summary and decisions

| Item | Record |
|---|---|
| Main findings about documented current state | |
| Material risks, potential benefits, and uncertainties | |
| Important evidence reviewed | |
| Significant evidence gaps or limitations | |
| Current decision / recommendation (e.g., proceed, proceed with actions, pause, redesign, stop, or further assessment) | |
| Decision-maker and date | |
| Conditions, dependencies, or review triggers | |
| What this assessment does not establish | |

## 5. Core outcome review and focus hierarchy

Review the complete set of 72 Core subcategories in the [application matrix](../working-documents/nist-ai-rmf-application-matrix-draft.md). Assign every subcategory a disposition. For subcategories selected for assessment, also assign a focus tier so the record distinguishes the outcomes most central to this project from outcomes that support them. These tiers and labels are repository-created; NIST does not rank or weight its outcomes this way.

- **Main focus points:** selected outcomes most central to the project’s context, material risks, key decisions, or constraints.
- **Sub-focus points:** selected outcomes that support, enable, or qualify one or more main focus points. They remain part of the assessment; “sub-focus” does not mean unreviewed or unimportant.
- **Other outcomes:** outcomes considered but not selected, deferred, unable to assess, or not applicable. Record a reason for each so the assessment remains traceable across the full Core. “Not selected” does not mean the associated risk is absent.

The focus tier describes relative emphasis in this project assessment; it is not a NIST category, risk rating, maturity level, or measure of whether an outcome has been achieved. A Core outcome may be a main focus or sub-focus depending on project context.

### 5.1 Main focus points

Copy one row for each selected outcome that is central to the assessment. Use the matrix prompt and record findings, evidence, limitations, gaps, and actions.

| NIST reference | Why this is a main focus | Current Profile: documented state (facts vs assumptions) | Evidence ID(s), source/date/location | Evidence type and limits | Target Profile: desired state, developed with relevant representatives | Target status (proposed / under discussion / agreed / approved / unresolved) | Gap / uncertainty | Action, owner, target date | Decision/status |
|---|---|---|---|---|---|---|---|
| e.g., MAP 1.1 | | | | | | | | |

### 5.2 Sub-focus points

Copy one row for each selected outcome that supports or qualifies a main focus point. Where useful, identify the linked main-focus reference(s).

| NIST reference | Linked main focus point(s) | Why this is a sub-focus | Current Profile: documented state (facts vs assumptions) | Evidence ID(s), source/date/location | Evidence type and limits | Target Profile: desired state, discussed with relevant representatives | Target status (proposed / under discussion / agreed / approved / unresolved) | Gap / uncertainty | Action, owner, target date | Decision/status |
|---|---|---|---|---|---|---|---|---|
| e.g., GOVERN 2.1 | | | | | | | | | | |

### 5.3 Other Core outcomes and disposition

Record each remaining Core subcategory and why it was not selected, deferred, unable to assess, or considered not applicable. Use the precise status and record information gaps or follow-up where needed.

| NIST reference | Disposition | Rationale / information gap | Revisit trigger or follow-up, if any |
|---|---|---|---|
| e.g., MEASURE 2.12 | | | |

**Suggested dispositions:** Selected (Main focus); Selected (Sub-focus); Not selected — rationale recorded; Deferred / not yet assessed; Unable to assess — information gap; Not applicable — rationale recorded. These are repository-proposed labels, not NIST terminology.

**Coverage check:** Confirm that all 72 Core subcategories have exactly one disposition and that every selected outcome appears in either §5.1 or §5.2. Record totals: Main focus ___; Sub-focus ___; Not selected ___; Deferred ___; Unable to assess ___; Not applicable ___; **Total reviewed: 72**.

For each selected outcome, document the Current Profile state based on reviewed information and evidence. Then develop the Target Profile state through discussion with relevant company representatives, using the Current Profile as the baseline and considering the organization’s goals, priorities, risk tolerance, context, and resources. Involve the people who understand the use case and those authorized or accountable for relevant business, risk, and system decisions, as appropriate. Record participant names or roles, their input, the target’s status (proposed, under discussion, agreed, approved, or unresolved), the decision owner, and any disagreement. Record the resulting gap and any action. The target is a project decision; it is not automatically the full wording of a Core outcome or every suggestion in a related profile. Do not present a proposed target as company-approved. Distinguish the outcome being considered from evidence that an activity exists. A lack of evidence should be recorded as an information gap, not silently treated as absence of risk or failure. Record whether evidence is a policy/commitment, defined process, completed activity record, operational observation, or independent assurance; this taxonomy is repository-created, not a NIST classification.

## 6. Voluntary Playbook suggestions (optional)

Consult the NIST Playbook only where it helps operationalize a selected Core outcome. Suggestions are voluntary and non-exhaustive.

| Core reference | Playbook suggestion / source location | Decision (adopt / adapt / defer / omit) | Context rationale | Owner / planned evidence |
|---|---|---|---|---|
| | | | | |

Do not state that a Playbook suggestion is mandatory or that omission alone indicates nonconformance.

## 7. Evidence register

| Evidence ID | Document / artifact / observation | Origin / owner | Version or date | Location / link | What it supports | Limitations / verification status |
|---|---|---|---|---|---|---|
| E-01 | | | | | | |

Record unavailable or inaccessible evidence where material. Distinguish a source’s claim from what the artifact itself demonstrates.

**Optional companion input:** A company AI-governance document analysis may help identify relevant company-stated principles, objectives, internal requirements, and supporting artifacts. It does not replace this NIST assessment or establish project implementation. If used, verify that each original source applies to this project, list the original artifact here, and record what it supports and its limits. The companion analysis is a navigation and interpretation aid, not primary evidence. See the [optional method](../working-documents/nist-company-ai-governance-document-analysis.md).

## 8. Actions, decisions, and monitoring

| ID | Risk / gap / improvement | Selected response and rationale | Owner | Due / review date | Status | Completion evidence / follow-up |
|---|---|---|---|---|---|---|
| A-01 | | | | | | |

Include monitoring, incident response, appeal/override, change-management, and retirement actions where relevant. Record residual risks and who accepts or owns them; do not infer acceptance from silence.

## 9. Reassessment triggers

List events that would make this record stale or require review.

- Material change to intended purpose, users, deployment context, model, data, vendor, integration, or system capability.
- Material change in affected groups, risk understanding, performance, incidents, or feedback.
- Material change to organizational risk tolerance, requirements, or available controls.
- Publication of a revised NIST AI RMF or a material change to the sources used in the assessment.
- A material change to any legal or sector-specific requirement identified for specialist review.
- Other project-specific trigger: ______________________________________

## 10. Review and sign-off

| Role | Name | Review / decision | Date |
|---|---|---|---|
| Assessment owner | | | |
| Relevant business / domain owner | | | |
| Technical / data / security reviewer, as applicable | | | |
| Risk / governance reviewer, as applicable | | | |
| Decision-maker | | | |

Sign-off means the stated record was reviewed for the stated purpose; it is not certification or proof that controls are effective.

## 11. Change history

| Record version/date | Change | Reason/source or project trigger | Affected outcomes/sections | Reviewed by |
|---|---|---|---|---|
| 0.1 / | Initial draft | | | |

## Use limitation

This record captures a context-specific review of selected NIST AI RMF outcomes and available documentation/evidence. It is a repository-created learning artifact. Conclusions should be phrased as documented alignment and available evidence unless the reviewed material supports a stronger claim about implementation or effectiveness. This record is not a NIST-issued template, universal checklist, maturity rating, legal opinion, certification, or proof of organizational compliance.
