# PRD Templates

A PRD is a contract between product and engineering. Its job is to eliminate 
ambiguity before a single line of code is written, not to document decisions 
after they have already been made.

## My PRD Format

Every PRD I write follows this structure. Nothing is added that does not serve 
the engineer building it or the stakeholder evaluating it.

---

**Issue ID and Title**
Every PRD is traceable to a project management issue. No issue ID means the 
work has not been properly scoped and should not be built.

**Status**
Draft, In Review, or Approved. Nothing enters development until status is 
Approved.

**Problem Statement**
Two sentences maximum. What is broken, for whom, and what is the measurable 
cost of leaving it broken.

**User Story**
One sentence. As a [persona] I need to [action] so that [measurable outcome]. 
No padding, no multiple stories in one PRD.

**Acceptance Criteria**
Numbered, testable, eight items maximum. Each criterion can be verified by 
a QA engineer or the PM without interpretation. If it requires judgment to 
evaluate, rewrite it.

**Scope Boundary**
Two columns. In scope and out of scope. This section prevents scope creep 
more than any other artifact in the document.

**Compliance Flags**
Only included when triggered. Relevant frameworks flagged by name with the 
specific requirement that applies.

**Open Decisions**
Any unresolved question that could change the build. Each item has an owner 
and a due date. A PRD with unresolved open decisions does not get approved.

---

## What Makes a Bad PRD

Vague acceptance criteria that require interpretation. User stories with 
multiple outcomes. Scope boundaries that are not enforced. Open decisions 
with no owner. Requirements written after engineering has already started.

## Template File

A blank PRD template is available in this folder as `prd-template.md`. 
Copy it for each new feature and fill in every section before submitting 
for review.
