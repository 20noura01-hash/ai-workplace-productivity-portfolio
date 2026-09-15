# Before and After Prompt Example

## Workplace Scenario

This example is based on a Business Analyst who needs to convert meeting notes into clear and structured action items.

## Before — Weak Prompt

> Summarize these meeting notes and tell me what needs to be done.

### Initial Result

The output may provide a general summary, but it may not clearly separate action items, owners, deadlines, priorities, or missing information.

## After — Improved Prompt

> Act as a Business Analyst. Review the meeting notes below and extract the key action items. For each action item, identify the owner, deadline, priority, and status only when the information is explicitly available. If any information is missing, write "Not Specified." Present the results in a clear table. Do not invent or assume information that is not included in the notes.

### Improved Result

| Action Item                      | Owner | Deadline      | Priority      | Status        |
| -------------------------------- | ----- | ------------- | ------------- | ------------- |
| Update the requirements document | Sara  | Not Specified | Not Specified | Not Specified |

## What Improved

1. **Clear role:** The prompt defines the AI as a Business Analyst.
2. **Specific task:** It clearly explains what information should be extracted.
3. **Structured output:** It specifies a table with defined fields.
4. **Accuracy control:** It instructs the AI not to invent missing information.

## Key Learning

A well-structured prompt provides clearer instructions, defines the expected output, and reduces the risk of unsupported information.

