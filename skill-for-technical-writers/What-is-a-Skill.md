# What is a Skill?

## Summary

A skill is a small instruction file that teaches an AI assistant (such as Claude) how to behave in a specific way. When you install a skill in your repository, the AI automatically follows its rules every time you ask it to help you write or review documentation.

## Detailed Overview

When you work with an AI assistant, it does not automatically know the documentation standards of your course or your team. Without guidance, it might produce pages that mix information types, skip required sections, or use an inconsistent structure.

A skill solves this problem. It is a Markdown file placed in a special folder called `.claude/skills/` inside your repository. The file contains:

- A description of the writing rules the AI must follow.
- The exact structure (headings and sections) for each type of documentation page.
- Specific instructions for how the AI should behave when asked to write or review content.

Once the skill is installed, you activate it by typing a short command — called a slash command — in your chat with the AI. The AI then applies all the rules from the skill file to everything it writes for you in that session.

**How it fits into your workflow:**

1. You install the skill once in your repository.
2. Each time you start a new writing session, you activate the skill with a slash command.
3. You ask the AI to write or review a page.
4. The AI produces output that follows the instructor's guidelines automatically.

## Example

Imagine you need to write a Concept page about a new software feature. Without the skill, the AI might produce a page that includes procedure steps mixed in with the explanation — which violates the course rule that concept and task information must stay on separate pages.

With the `write-the-docs` skill activated, the AI knows the correct Concept page structure (Summary, Detailed Overview, Example) and will not include steps. It will also remind you if it needs to know your target audience before it starts writing.
