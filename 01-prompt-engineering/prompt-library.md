# Prompt Library

**Workplace scenario:** Business Analyst supporting a business team with requirements analysis, stakeholder communication, information processing, and project planning.

The prompts below are reusable examples for routine Business Analyst workplace tasks. Each prompt follows either the **C.A.R.E.** framework (Context, Action, Role, Expected Output) or **R.C.T.O.** (Role, Context, Task, Output).

| **Prompt Name**                         | **Workplace Task**                                  | **Framework** | **Prompt**                                                                                                                                                                                                                                                                                                                                                                                                                                                   | **Expected Output**                                                                        |
| --------------------------------------- | --------------------------------------------------- | ------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------ |
| **Meeting Summary**                     | Summarize business-team meeting notes               | **C.A.R.E.**  | **Context:** I support a business team and need to turn meeting notes into a concise record. **Action:** Summarize only the information provided, identify decisions, action items, owners, deadlines, and unresolved questions. If a detail is missing, write `[Not Specified]`. **Role:** Act as a Business Analyst. **Expected Output:** A concise summary followed by an action-item table with columns: Action Item, Owner, Deadline, Priority, Status. | Concise summary plus a structured action-item table without invented information.          |
| **Stakeholder Update Email**            | Draft a professional project update email           | **C.A.R.E.**  | **Context:** A business stakeholder needs an update about a project timeline. **Action:** Draft a clear and professional email communicating the current status, revised deadline, and next steps using only the information provided. **Role:** Act as a Business Analyst communicating with a stakeholder. **Expected Output:** Subject line plus a concise professional email.                                                                            | A clear stakeholder email containing the relevant project information and next steps.      |
| **Requirements Extractor**              | Extract key information from business requirements  | **R.C.T.O.**  | **Role:** Act as a Business Analyst. **Context:** I will provide business requirements or notes related to a project. **Task:** Extract the business objective, key requirements, stakeholders, constraints, and open questions. Do not add facts that are not in the source. **Output:** A structured five-part summary using clear headings and `[Not Specified]` for missing information.                                                                 | Structured requirements summary that preserves the meaning of the source.                  |
| **Requirements Comparison**             | Compare two sets of business requirements           | **R.C.T.O.**  | **Role:** Act as a Business Analyst. **Context:** I have two versions of business requirements that need to be reviewed. **Task:** Identify common requirements, differences, missing requirements, and points that require clarification. Do not assume that similar wording means identical requirements. **Output:** A comparison table with Requirement, Version 1, Version 2, Difference, and Clarification Needed.                                     | A structured comparison showing similarities, differences, gaps, and clarification points. |
| **Project Planning Assistant**          | Build a short plan for a business-analysis activity | **C.A.R.E.**  | **Context:** I need to organize a business-analysis activity and complete it within a defined timeframe. **Action:** Break the work into Goal → Mechanisms → Phases → Tasks. **Role:** Act as a Business Analyst and planning assistant. **Expected Output:** A concise table showing phases, tasks, responsible role, suggested timing, and completion check.                                                                                               | A practical phased plan with clear and specific tasks.                                     |
| **Priority Sorter**                     | Prioritize business requirements or tasks           | **C.A.R.E.**  | **Context:** I have a list of business tasks with different deadlines, dependencies, and levels of impact. **Action:** Prioritize the tasks based on urgency, business impact, dependency, and effort. **Role:** Act as a Business Analyst. **Expected Output:** A ranked table with Task, Priority, Reason, Dependency, and Recommended Next Action. Explain any assumptions.                                                                               | A ranked and justified task list.                                                          |
| **Stakeholder Clarification Questions** | Identify unclear or incomplete requirements         | **R.C.T.O.**  | **Role:** Act as a Business Analyst. **Context:** I am reviewing business requirements provided by a stakeholder. **Task:** Identify unclear, incomplete, or ambiguous requirements and create specific clarification questions. Do not make assumptions or provide answers that are not supported by the source. **Output:** A structured list of clarification questions linked to each identified gap.                                                    | Clear clarification questions that help identify missing or ambiguous requirements.        |

## Example Output 1 — Stakeholder Update Email

**Subject:** Project Timeline Update

Dear [Client Name],

I would like to provide you with an update regarding the project timeline. Please note that the revised deadline for completing the project is **September 22**.

We are currently working according to the updated timeline and will ensure that the required deliverables are completed by the revised deadline.

If you have any questions or require further clarification, please feel free to contact me.

Thank you for your understanding and cooperation.

Best regards,
Business Analyst

## Example Output 2 — Meeting Summary

### Key Summary

* The team discussed the current business requirements.
* The requirements document needs to be reviewed and updated.
* Sara will review the current document.
* The deadline for the review was **[Not Specified]**.
* Additional clarification may be required before finalizing the requirements.

### Action Items

| Action Item                              | Owner | Deadline        | Priority        | Status          |
| ---------------------------------------- | ----- | --------------- | --------------- | --------------- |
| Review the current requirements document | Sara  | [Not Specified] | [Not Specified] | [Not Specified] |

## When I Would Use These Prompts

* **Meeting Summary:** after a business-team meeting to organize decisions and action items.
* **Stakeholder Update Email:** when communicating a project status or timeline update.
* **Requirements Extractor:** when reviewing a requirements document or unstructured business notes.
* **Requirements Comparison:** when comparing different versions of business requirements.
* **Project Planning Assistant:** when organizing a business-analysis activity into clear phases and tasks.
* **Priority Sorter:** when several business tasks or requirements compete for attention.
* **Stakeholder Clarification Questions:** when requirements are unclear, incomplete, or ambiguous.

