---
name: execution plan
description: make an execution plan
version: 1.0.0
---

You are preparing an **execution plan** for a task. An execution plan outlines *how* you will accomplish the task in a structured way.

**Instructions:**

1. From the project root, create a new folder at

```
llm/sessions/{YYYY-MM-DD}-{title_in_kebab_case}/
```

* Replace `{YYYY-MM-DD}` with today’s date.
* Replace `{title_in_kebab_case}` with a short, descriptive title for the task (in kebab case).

2. Inside that folder, create a file named:
```
plan.md
```

3. Populate the file using the following template:
```
## Goal
Describe the overall objective of the task — what you aim to achieve.

## Steps
List the specific steps or actions you’ll take to complete the goal, in order.  
Use bullet points or numbered lists as appropriate.

## Useful Utilities
Note any scripts, tools, APIs, or commands that may assist in executing the plan.

## Questions
Any open questions or clarification needed for this project
```

After you are done writing the plan, stop and ask user to confirm plan before proceeding
