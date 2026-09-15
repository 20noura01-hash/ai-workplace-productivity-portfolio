# Information Processing Example

## Information Tasks Used

This example demonstrates **summarizing, extracting, restructuring, and prioritizing**. These tasks were selected because a Business Analyst often needs to turn scattered meeting notes into a clear summary that supports decisions, requirements tracking, and follow-up.

## 1. Raw Input

> Requirements review meeting recap: the team agreed to update the customer requirements document before the next stakeholder review. Sara will review the current requirements and identify any missing information. The stakeholder review meeting is expected next week, but the exact date has not been confirmed. The team also discussed a reporting dashboard, but no final decision was made on the required metrics. The project manager asked for the updated requirements document before the stakeholder review.

## 2. Prompt Used

**Context:** These are raw meeting notes from a fictional requirements review meeting. The brief will be used by the Business Analyst to organize follow-up actions and prepare for the stakeholder review.

**Action:** Summarize the notes, extract confirmed decisions and action items, identify risks and open questions, and prioritize the items that need attention before the stakeholder review.

**Rules:** Preserve all names, dates, decisions, and uncertainty. Do not invent owners or deadlines. Do not turn a discussion into a confirmed decision. Mark missing information as `[Not Specified]`.

**Expected Output:** Start with a three-bullet bottom line, then provide confirmed decisions, open questions, risks, and an action-item table with Action Item, Owner, Deadline, Priority, and Status.

## 3. AI Output - First Draft

### Bottom Line

* The requirements document will be updated before the stakeholder review.
* Sara will complete the requirements review by next week.
* The reporting dashboard will include the required metrics.

### Actions

| **Action Item**                                      | **Owner**        | **Deadline** | **Priority** | **Status**  |
| ---------------------------------------------------- | ---------------- | ------------ | ------------ | ----------- |
| Update requirements document                         | Business Analyst | Next week    | High         | In progress |
| Review requirements and identify missing information | Sara             | Next week    | High         | In progress |
| Define dashboard metrics                             | Project team     | Next week    | Medium       | Planned     |

## 4. Human Review

The first draft contains unsupported assumptions:

* The source does not say that Sara's review must be completed by next week.
* The status **“In progress”** was not provided.
* No final decision was made about the dashboard metrics.
* The owner of the requirements document update was not explicitly specified.
* The exact date of the stakeholder review was not confirmed.

I corrected these issues and preserved the uncertainty in the final output.

## 5. Final Structured Output

### Bottom Line

* The requirements document needs to be updated before the next stakeholder review.
* Sara will review the current requirements and identify missing information.
* The stakeholder review is expected next week, but the exact date is not confirmed. The required dashboard metrics are also not finalized.

### Confirmed Decision

| **Decision**                                                                 | **Evidence**                   | **Status** |
| ---------------------------------------------------------------------------- | ------------------------------ | ---------- |
| Update the customer requirements document before the next stakeholder review | Confirmed in the meeting notes | Confirmed  |

### Action Items

| **Action Item**                                              | **Owner**         | **Deadline**              | **Priority** | **Status**    |
| ------------------------------------------------------------ | ----------------- | ------------------------- | ------------ | ------------- |
| Update the customer requirements document                    | `[Not Specified]` | Before stakeholder review | High         | Open          |
| Review current requirements and identify missing information | Sara              | `[Not Specified]`         | High         | Open          |
| Confirm the stakeholder review date                          | `[Not Specified]` | `[Not Specified]`         | High         | Open          |
| Define and confirm the required dashboard metrics            | `[Not Specified]` | `[Not Specified]`         | Medium       | Open decision |

### Risks and Open Questions

* **Requirements-readiness risk:** Missing information may remain in the requirements document before the stakeholder review.
* **Timeline uncertainty:** The exact date of the stakeholder review has not been confirmed.
* **Open decision:** The required metrics for the reporting dashboard have not been finalized.
* **Ownership gap:** The owner responsible for updating the requirements document was not explicitly specified.
