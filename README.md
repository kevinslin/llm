A repo of various LLM augmentations that I find useful.

## Additional Instructions

You now have access to Skills. Skills are specialized instruction sets stored as markdown files that extend your capabilities. When a task matches a skill's purpose, load and follow that skill's instructions.

### Skill Structure

Each skill contains:
- **SKILL.md**: Core instructions with YAML frontmatter
- **scripts/**: Optional executable code for deterministic tasks
- **references/**: Optional detailed documentation
- **assets/**: Optional templates, images, or files

### How to Use Skills

1. **Match task to skill**: Check the skill list below for relevant descriptions
2. **Load the skill**: Read the SKILL.md file when needed
3. **Follow instructions**: Apply the skill's guidelines exactly
4. **Use resources**: Reference bundled scripts/docs/assets as directed
5. **Combine skills**: Use multiple skills together when appropriate

### When to Load a Skill

- Task matches a skill's description
- User mentions a skill by name
- Task requires specialized knowledge (file formats, workflows, domain expertise)

### Key Principles

- **Load only when needed** - Don't load skills for simple tasks
- **Apply naturally** - Don't announce "loading skill X" unless relevant
- **Use bundled resources** - Scripts and references are there to help
- **Be precise** - Skills often include exact patterns and code to follow

### Available Skills

Below is the list of skills you can access. Load a skill by reading its SKILL.md file when the task matches:

- [algorithmic-art](../code/skills/algorithmic-art/SKILL.md): Creating algorithmic art using p5.js with seeded randomness and interactive parameter exploration. Use this when users request creating art using code, generative art, algorithmic art, flow fields, or particle systems. Create original algorithmic art rather than copying existing artists&#x27; work to avoid copyright violations.
- [artifacts-builder](../code/skills/artifacts-builder/SKILL.md): Suite of tools for creating elaborate, multi-component claude.ai HTML artifacts using modern frontend web technologies (React, Tailwind CSS, shadcn/ui). Use for complex artifacts requiring state management, routing, or shadcn/ui components - not for simple single-file HTML/JSX artifacts.
- [brand-guidelines](../code/skills/brand-guidelines/SKILL.md): Applies Anthropic&#x27;s official brand colors and typography to any sort of artifact that may benefit from having Anthropic&#x27;s look-and-feel. Use it when brand colors or style guidelines, visual formatting, or company design standards apply.
- [canvas-design](../code/skills/canvas-design/SKILL.md): Create beautiful visual art in .png and .pdf documents using design philosophy. You should use this skill when the user asks to create a poster, piece of art, design, or other static piece. Create original visual designs, never copying existing artists&#x27; work to avoid copyright violations.
- [internal-comms](../code/skills/internal-comms/SKILL.md): A set of resources to help me write all kinds of internal communications, using the formats that my company likes to use. Claude should use this skill whenever asked to write some sort of internal communications (status reports, leadership updates, 3P updates, company newsletters, FAQs, incident reports, project updates, etc.).
- [mcp-builder](../code/skills/mcp-builder/SKILL.md): Guide for creating high-quality MCP (Model Context Protocol) servers that enable LLMs to interact with external services through well-designed tools. Use when building MCP servers to integrate external APIs or services, whether in Python (FastMCP) or Node/TypeScript (MCP SDK).
- [skill-creator](../code/skills/skill-creator/SKILL.md): Guide for creating effective skills. This skill should be used when users want to create a new skill (or update an existing skill) that extends Claude&#x27;s capabilities with specialized knowledge, workflows, or tool integrations.
- [slack-gif-creator](../code/skills/slack-gif-creator/SKILL.md): Toolkit for creating animated GIFs optimized for Slack, with validators for size constraints and composable animation primitives. This skill applies when users request animated GIFs or emoji animations for Slack from descriptions like &quot;make me a GIF for Slack of X doing Y&quot;.
- [template-skill](../code/skills/template-skill/SKILL.md): Replace with description of the skill and when Claude should use it.
- [theme-factory](../code/skills/theme-factory/SKILL.md): Toolkit for styling artifacts with a theme. These artifacts can be slides, docs, reportings, HTML landing pages, etc. There are 10 pre-set themes with colors/fonts that you can apply to any artifact that has been creating, or can generate a new theme on-the-fly.
- [webapp-testing](../code/skills/webapp-testing/SKILL.md): Toolkit for interacting with and testing local web applications using Playwright. Supports verifying frontend functionality, debugging UI behavior, capturing browser screenshots, and viewing browser logs.

