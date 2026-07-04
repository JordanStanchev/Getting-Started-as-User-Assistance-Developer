# How to Use the Skill

## Summary

By following these steps, you will activate the `write-the-docs` skill in a Claude Code chat session and use it to generate or review a documentation page that follows the instructor's guidelines.

## Prerequisites

- You have installed the `write-the-docs` skill in your repository. See [How to Install the Skill](How-to-Install-the-Skill.md).
- You have opened your wiki repository in Claude Code.

## Steps

1. Open a new chat session in Claude Code inside your wiki repository.
2. Type the following slash command and press **Enter**:
   ```
   /write-the-docs
   ```
3. The skill loads. Claude will confirm that the `write-the-docs` guidelines are active.
4. Tell Claude what you want to write. Include the following information in your request:
   - The **information type**: Concept, Task, or Reference.
   - The **target audience**: for example, "a new user who has never used the app".
   - The **topic**: the feature or procedure you want to document.
5. Review the page that Claude produces.
6. If needed, ask Claude to revise specific sections. Claude will keep applying the skill rules during the same session.

## Result

Claude produces a complete documentation page that follows the correct structure for the information type you requested. All required sections are present and no placeholder text remains.

## Example

You want to write a Task page explaining how to divide numbers in the Calculator app.

1. You open Claude Code in your wiki repository.
2. You type `/write-the-docs` and press **Enter**.
3. Claude confirms the skill is active.
4. You type:
   > Write a Task page for new users of the Calculator app explaining how to divide two numbers.
5. Claude produces a page with the headings: Summary, Prerequisites, Steps, Result, and Example — each filled with real content about dividing numbers, with no placeholder text.
6. You copy the output into a new file in your wiki, for example `How-to-Divide-Numbers.md`.
