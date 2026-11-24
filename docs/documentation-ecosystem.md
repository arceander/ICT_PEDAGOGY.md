# Documentation ecosystem — ICT

- Edition: 2026–2027
- Version: 0.3
- Status: selected architecture; implementation is progressive.

[PEDAGOGY.md](../PEDAGOGY.md) is the central pedagogical reference. Institutional requirements and the official course guide retain their authority. eGela is the operational student-facing environment. Maintain repository materials in English, keep identifiable student work and grades out of GitHub, and verify private teaching-team access before adding internal operational materials.

## Modules and responsibilities

| Path | Responsibility |
|---|---|
| `PEDAGOGY.md` | Pedagogical principles, curricular structure, methodology, assessment model, AI policy, feedback and maintenance. |
| `README.md`, `CHANGELOG.md`, `docs/documentation-ecosystem.md` | Navigation, change history and documentation responsibilities. |
| `content.md`, optional `content/` | Stable conceptual structure and detailed content, independent of the annual route. |
| `ontology.md` | Preliminary concept definitions and relationships; review at the end of the edition. |
| `activities.md`, `activities/` | Register and specifications of reusable activities, with stable IDs and revisions. |
| `docs/activity-design-guidelines.md` | Teacher-approved working guidance v0.1 for teachers and AI; pilot review pending. |
| `activities/templates/activity-template.md` | Planned internal specification template including the student-facing brief. |
| `activities/templates/activity-template.docx` | Planned editable student-facing Word representation. |
| `projects/` | Project briefs, guides, resource links and, when needed, assistant specifications and tests; link authoritative rubrics. |
| `assessment.md`, `rubrics/` | Detailed assessment procedures and authoritative rubrics, when developed and validated. |
| `resources.md`, optional `resources/` | Verified resources, pedagogical purposes and access conditions or limitations. |
| `editions/2026-2027/teaching-route.md` | Flexible weekly route, edition codes, selected activities/revisions, dates and annual adjustments. |

Resource categories: frameworks, scientific literature, institutional resources, digital tools, learning resources and AI tools. No persistent case system is adopted; contextual scenarios belong within the relevant activity or assessment. AI policy and feedback remain in the core unless a concrete need warrants a separate extension. Do not create empty modules merely to satisfy the architecture.

## Reusable activities and edition instances

Assign a permanent internal identifier (`ACT-001`, etc.) when registering a reusable activity. Record its revision separately. The student-facing identifier uses `P_S5`, `TP_S5`, etc., according to the actual teaching week; use a suffix only if needed. The edition route maps the weekly code to the permanent ID and revision. Moving an activity does not change its stable identity. Keep deadlines and edition-dependent arrangements in the edition implementation, and include the effective values in the student brief. Historical PS identifiers and old TPC mappings must be reviewed before reuse.

A P/TP activity has two layers:

| Layer | Purpose |
|---|---|
| Internal specification | Stable ID, revision, type, block, pedagogical rationale, relevant content, AC/TPC/DigCompEdu links, provisional LO mappings, evidence and criteria, optional related activities/projects, scaffolding and teacher notes. |
| Student-facing brief | Weekly code, block and title; overview (objectives, time, working mode, expected outcome, resources, AI-use summary, DigCompEdu and academic competences); context when useful; instructions; success and assessment/completion criteria; submission requirements when applicable; AI conditions and declaration where relevant; reflection when pedagogically useful. |

The student-facing content in the Markdown specification is the common semantic source for the Word and eGela representations. The representations need not reproduce teacher-only notes. Do not use internal information to introduce undisclosed grading criteria. Use a single modular template for P and TP, with proportional detail. Proposed visual implementation: yellow activity headings and textual block identification (A green, B blue, C orange), with accessible contrast and structure that remains understandable without colour. Use normal headings, lists and simple tables; verify Word-to-eGela transfer rather than assume fidelity.

Refer to PEDAGOGY.md §9.4 for the authoritative planning scales: P has four percentage levels (0/33/66/100) and TP is binary (0/100), without direct grade weighting. Activity success criteria describe observable learning; do not duplicate or invent course-wide penalties or aggregation rules. Refer to §13 for contextualized AI-use conditions (permitted, restricted, required or prohibited), and §10 for possible supervised feedback/assessment-support pilots. These pilots are not operational; no automatic official grades or mandatory assistant interaction are adopted.

## Implementation sequence

1. Draft and review `docs/activity-design-guidelines.md` (v0.1) — teacher-approved and incorporated.
2. Develop `activities/templates/activity-template.docx` (v2.0) — student-facing Word template first.
3. Draft and review `activities/templates/activity-template.md` (v0.1) — internal specification and equivalent student-facing layer.
4. Pilot the templates with a short TP, a technical P and a complex P involving AI; assess usability, pedagogical alignment, AI interpretation and actual Word-to-eGela transfer.
5. Incorporate revised templates and guidelines into the repository after teacher review, then register reusable activities progressively.

Develop content and ontology from reviewed materials; populate the resource catalog, project workspaces, assessment documentation and annual route as needed. Keep mappings provisional where the learning outcomes or underlying decisions have not yet been validated. Update the core only for substantive pedagogical decisions, and record those in the changelog.
