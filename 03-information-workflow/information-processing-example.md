# Information Processing Workflow

## Workplace Scenario

A Business Analyst receives unstructured meeting notes and needs to convert them into decision-ready action items.

## Input — Raw Notes

> The team discussed updating the customer requirements document. Sara will review the current version. The team also discussed a possible meeting with the client next week, but no date was confirmed. The priority of the document update was not specified.

## Prompt Used

> Act as a Business Analyst. Extract the action items and relevant information from the notes. Identify the action item, owner, deadline, priority, and status. Do not invent missing information. Use "Not Specified" when information is unavailable. Present the output in a table.

## AI Output

| Action Item                               | Owner         | Deadline                       | Priority      | Status        |
| ----------------------------------------- | ------------- | ------------------------------ | ------------- | ------------- |
| Review the customer requirements document | Sara          | Not Specified                  | Not Specified | Not Specified |
| Arrange a possible client meeting         | Not Specified | Next week — date not confirmed | Not Specified | Not Specified |

## Human Review

The Business Analyst checks the AI output against the original notes.

* The owner "Sara" is supported by the source.
* No confirmed deadline was provided for the document review.
* The client meeting was described as a possibility, not a confirmed meeting.
* No priority or status was provided.

## Final Structured Output

| Action Item                                   | Owner         | Deadline      | Priority      | Status        |
| --------------------------------------------- | ------------- | ------------- | ------------- | ------------- |
| Review the customer requirements document     | Sara          | Not Specified | Not Specified | Not Specified |
| Follow up regarding a possible client meeting | Not Specified | Not Specified | Not Specified | Not Specified |

## Key Learning

AI can help transform unstructured information into a structured format, but the Business Analyst must review the output against the original source and avoid treating assumptions as facts.

