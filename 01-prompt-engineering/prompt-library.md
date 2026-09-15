# Prompt Library — Business Analyst

This prompt library contains practical generative AI prompts designed to support common tasks performed by a Business Analyst. The prompts follow the C.A.R.E. or O.T.C.R. framework and are designed to produce clear, structured, and workplace-relevant outputs.

## 1. Meeting Notes to Action Items

**Workplace Task:** Convert meeting notes into clear action items.

**Framework:** C.A.R.E.

**Prompt:**

> Act as a Business Analyst. Review the meeting notes provided below and extract the key action items. For each action item, identify the owner, deadline, priority, and status only when the information is explicitly available. If information is missing, write "Not Specified." Present the results in a clear table.

**Expected Output:** A structured action-item table with accurate and clearly identified information.

**When to Use:** Use this prompt after meetings to organize decisions and follow-up actions.

---

## 2. Business Requirements Summary

**Workplace Task:** Summarize business requirements from a longer document.

**Framework:** O.T.C.R.

**Prompt:**

> Organize the following business requirements into a concise summary. Identify the main business objective, key requirements, stakeholders, constraints, and open questions. Do not invent information that is not included in the source. Mark missing information as "Not Specified." Present the result using clear headings and bullet points.

**Expected Output:** A concise and structured requirements summary.

**When to Use:** Use this prompt when reviewing requirements documents before analysis or discussion.

---

## 3. Stakeholder Communication Draft

**Workplace Task:** Draft a professional message for a stakeholder.

**Framework:** C.A.R.E.

**Prompt:**

> Act as a Business Analyst and draft a concise professional email to a stakeholder based only on the information provided. Clearly communicate the purpose, current status, required action, and next step. Use a professional and respectful tone. Do not add information that is not provided.

**Expected Output:** A professional stakeholder communication draft that is clear and concise.

**When to Use:** Use this prompt when preparing stakeholder updates or requests for clarification.

---

## 4. Requirements Comparison

**Workplace Task:** Compare two sets of business requirements.

**Framework:** O.T.C.R.

**Prompt:**

> Compare the two sets of business requirements provided below. Identify common requirements, differences, missing requirements, and potential areas that require clarification. Do not assume that similar wording means identical requirements. Present the comparison in a structured table.

**Expected Output:** A comparison table highlighting similarities, differences, gaps, and clarification points.

**When to Use:** Use this prompt when reviewing updated requirements or comparing stakeholder inputs.

---

## 5. Information Prioritization

**Workplace Task:** Prioritize business information or requirements.

**Framework:** C.A.R.E.

**Prompt:**

> Review the information provided and prioritize the items based on business importance, urgency, and potential impact. Explain the reason for each priority level using only the available information. If there is insufficient information to determine priority, mark it as "Needs Review." Present the results in a table.

**Expected Output:** A prioritized list with a brief rationale for each item.

**When to Use:** Use this prompt when deciding which requirements or issues should receive attention first.

---

## 6. Executive Summary

**Workplace Task:** Create a concise summary for decision-makers.

**Framework:** O.T.C.R.

**Prompt:**

> Summarize the following business information for a decision-maker. Focus on the main issue, key findings, important risks or considerations, and recommended next steps when they are supported by the source. Keep the summary concise and do not introduce unsupported information.

**Expected Output:** A short, decision-ready executive summary.

**When to Use:** Use this prompt when converting detailed information into a format suitable for managers or decision-makers.

---

## 7. Requirements Clarification Questions

**Workplace Task:** Identify questions that need clarification before proceeding.

**Framework:** C.A.R.E.

**Prompt:**

> Act as a Business Analyst reviewing the information below. Identify unclear, incomplete, or ambiguous requirements that require clarification. For each issue, write one specific question that could be asked to the stakeholder. Do not make assumptions or provide answers that are not supported by the source.

**Expected Output:** A structured list of clarification questions linked to the identified gaps.

**When to Use:** Use this prompt before finalizing requirements or starting analysis.

---

## Example Outputs

### Example 1 — Meeting Notes to Action Items

**Input:**
The team agreed that the requirements document needs to be updated. Sara will review the document. The deadline was not specified.

**Short Example Output:**

| Action Item                      | Owner | Deadline      | Priority      | Status        |
| -------------------------------- | ----- | ------------- | ------------- | ------------- |
| Update the requirements document | Sara  | Not Specified | Not Specified | Not Specified |

### Example 2 — Requirements Clarification Questions

**Input:**
"The system should generate reports faster."

**Short Example Output:**

* What is the expected report generation time?
* Which reports are included in this requirement?
* Is there a specific performance target or deadline?

