A repo of various LLM augmentations that I find useful.

### Available Skills

- [dendron](skills/dendron/SKILL.md): Work with dendron markdown notes using fs and sqlite
- [add-license](skills/dev-add-license/SKILL.md): This skill should be used when the user wants to add a LICENSE file to their repository. Currently supports Apache License 2.0 with automatic copyright information detection from git configuration. Also updates package.json license field if the file exists.
- [code](skills/dev-code/SKILL.md): This skill should be used when performing any coding task including implementing features, fixing bugs, refactoring code, or making any modifications to source code. Provides best practices, security considerations, testing guidelines, and a structured workflow for development tasks.
- [dev-document](skills/dev-document/SKILL.md): document changes made
- [Execution Plan](skills/dev-exec-plan/SKILL.md): This skill should be used for complex development tasks that require detailed technical planning with persistent documentation. Use when the task involves architectural decisions, multi-phase implementation, external dependencies, or when the user explicitly requests a documented execution plan. For simple tasks with 3-5 steps, use TodoWrite instead.
- [gh](skills/dev-gh/SKILL.md): GitHub CLI operations
- [lint](skills/dev-lint/SKILL.md): lint project
- [find-links](skills/find-links/SKILL.md): This skill should be used when the user wants to fill in TODO links, placeholder links, or missing links in markdown files. Invoke when the user mentions "fill links", "TODO links", "find links", or asks to add appropriate links to concepts in a document.
- [gen-notifier](skills/gen-notifier/SKILL.md): Send desktop notifications when tasks are complete. This skill should be used when user tells you to notify them when a job is done. By default, assume that all jobs assigned to you will require a notification.
- [hn-title](skills/hn-title/SKILL.md): This skill should be used when the user wants to create, analyze, or improve blog titles for Hacker News submissions. Invoke when the user mentions "HN title", "Hacker News title", wants to optimize their post title, or wants to increase their chances of reaching the HN front page.
- [learn](skills/learn/SKILL.md): learn from the current session
- [learning-capture](skills/learning-capture/SKILL.md): Extract and consolidate key learnings, insights, and actionable takeaways from the current conversation session. Use when the user wants to capture, summarize, or document what was learned during the chat, create study materials from discussions, or save important discoveries and decisions for future reference. Triggers include requests like "capture learnings," "summarize what we discussed," "create notes from this conversation," "what did I learn today," or "document our key findings."
- [skill-creator](skills/skill-creator/SKILL.md): Guide for creating effective skills. This skill should be used when users want to create a new skill (or update an existing skill) that extends Claude's capabilities with specialized knowledge, workflows, or tool integrations.
- [imagekit-upload](skills/tool-imagekit-upload/SKILL.md): Upload images to ImageKit from file paths or clipboard, returning the CDN URL for easy sharing and embedding
- [tech-doc-writer](skills/write-tech-docs/SKILL.md): This skill should be used when writing or reviewing technical documentation such as READMEs, API documentation, quickstart guides, or any user-facing documentation. Apply editorial principles focused on leading with value, cutting redundancy, and creating scannable, actionable content. Use when the user requests help writing docs, improving existing documentation, or creating user guides.

## Additional Instructions

### Available Skills

- [dendron](skills/dendron/SKILL.md): Work with dendron markdown notes using fs and sqlite
- [add-license](skills/dev-add-license/SKILL.md): This skill should be used when the user wants to add a LICENSE file to their repository. Currently supports Apache License 2.0 with automatic copyright information detection from git configuration. Also updates package.json license field if the file exists.
- [code](skills/dev-code/SKILL.md): This skill should be used when performing any coding task including implementing features, fixing bugs, refactoring code, or making any modifications to source code. Provides best practices, security considerations, testing guidelines, and a structured workflow for development tasks.
- [dev-document](skills/dev-document/SKILL.md): document changes made
- [Execution Plan](skills/dev-exec-plan/SKILL.md): This skill should be used for complex development tasks that require detailed technical planning with persistent documentation. Use when the task involves architectural decisions, multi-phase implementation, external dependencies, or when the user explicitly requests a documented execution plan. For simple tasks with 3-5 steps, use TodoWrite instead.
- [gh](skills/dev-gh/SKILL.md): GitHub CLI operations
- [lint](skills/dev-lint/SKILL.md): lint project
- [find-links](skills/find-links/SKILL.md): This skill should be used when the user wants to fill in TODO links, placeholder links, or missing links in markdown files. Invoke when the user mentions "fill links", "TODO links", "find links", or asks to add appropriate links to concepts in a document.
- [gen-notifier](skills/gen-notifier/SKILL.md): Send desktop notifications when tasks are complete. This skill should be used when user tells you to notify them when a job is done. By default, assume that all jobs assigned to you will require a notification.
- [hn-title](skills/hn-title/SKILL.md): This skill should be used when the user wants to create, analyze, or improve blog titles for Hacker News submissions. Invoke when the user mentions "HN title", "Hacker News title", wants to optimize their post title, or wants to increase their chances of reaching the HN front page.
- [learn](skills/learn/SKILL.md): learn from the current session
- [learning-capture](skills/learning-capture/SKILL.md): Extract and consolidate key learnings, insights, and actionable takeaways from the current conversation session. Use when the user wants to capture, summarize, or document what was learned during the chat, create study materials from discussions, or save important discoveries and decisions for future reference. Triggers include requests like "capture learnings," "summarize what we discussed," "create notes from this conversation," "what did I learn today," or "document our key findings."
- [skill-creator](skills/skill-creator/SKILL.md): Guide for creating effective skills. This skill should be used when users want to create a new skill (or update an existing skill) that extends Claude's capabilities with specialized knowledge, workflows, or tool integrations.
- [imagekit-upload](skills/tool-imagekit-upload/SKILL.md): Upload images to ImageKit from file paths or clipboard, returning the CDN URL for easy sharing and embedding
- [tech-doc-writer](skills/write-tech-docs/SKILL.md): This skill should be used when writing or reviewing technical documentation such as READMEs, API documentation, quickstart guides, or any user-facing documentation. Apply editorial principles focused on leading with value, cutting redundancy, and creating scannable, actionable content. Use when the user requests help writing docs, improving existing documentation, or creating user guides.

