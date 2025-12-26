---
name: Execution Plan
description: This skill should be used for development tasks that require detailed technical planning with persistent documentation. Use when the task involves architectural decisions, multi-phase implementation, external dependencies, or when the user explicitly requests an execution plan.
version: 2.0.0
---

# Execution Plan Skill

This skill creates structured, file-based execution plans for complex development tasks that benefit from persistent documentation and detailed technical planning.

## When to Use This Skill

Use this skill when:
- The task involves architectural or design decisions that should be documented
- Multiple implementation phases or milestones need tracking over extended periods
- External dependencies, APIs, or integrations require research and documentation
- The user explicitly requests a documented execution plan or project plan
- The task complexity warrants detailed technical specifications and decision rationale

**Do not use** for simple tasks better suited to TodoWrite (quick 3-5 step tasks without complex dependencies).

## Creating the Execution Plan

### 1. Determine Plan Location

By default, the output of a plan should be in `docs/project/specs`

Check if a planning directory structure exists in the current project:
- Look for existing patterns: `docs/plans/`, `planning/`, `llm/sessions/`, or `.plans/`
- If no standard location exists, store the plan in `llm/plans/{YYYY-MM-DD}-{title}/`

### 2. Create Plan Directory and File

Create a folder with a descriptive name:
```
{chosen-path}/{YYYY-MM-DD}-{title-in-kebab-case}/
```

Inside that folder, create `plan.md` using the template from `assets/plan-template.md`.

### 3. Populate the Plan

Use the template structure to create a comprehensive plan that includes:

For detailed guidance on creating effective plans, consult `references/effective-planning.md`.

**Goal** - Clear objective statement describing what will be accomplished

**Context** - Background information, constraints, and requirements
- Why this task is needed
- Current system state
- Key constraints or limitations

**Technical Approach** - High-level architectural or implementation strategy
- Technology choices and rationale
- Design patterns or methodologies
- Integration points

**Steps** - Detailed implementation phases in logical order
- Break down into milestones or phases
- Include research, implementation, testing, and deployment steps
- Note dependencies between steps

**Dependencies** - External resources, APIs, libraries, or tools needed
- Third-party services or integrations
- Required access or credentials
- Documentation references

**Risks & Mitigations** - Potential blockers and how to address them
- Technical risks
- Resource constraints
- Mitigation strategies

**Questions** - Open questions requiring clarification or research
- Unresolved technical decisions
- Areas needing user input
- Research tasks

### 4. Simplify

After creating the plan, think about whether you could simplify it further. Consult `DESIGN.md` file if it exists as well as last 5 commits to understand recent changes for context. If you identify ways that the plan can be made simpler, do the simplification. Add any simplifications done in the `# Notes` section of the execution plan.

### 5. Review and Confirm

After creating the plan:
1. Present a summary of the plan to the user
2. Highlight any questions or decisions that need input
3. Wait for user confirmation before proceeding with implementation
4. Update the plan as new information emerges during execution

## Best Practices

- Keep plans focused and actionable - avoid unnecessary verbosity
- Update the plan as decisions are made or scope changes
- Use the plan as a living document throughout the development process
- Reference specific sections when discussing progress or blockers
- For very complex plans, consider breaking into multiple related plan documents
