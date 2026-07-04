# How to Install the Skill

## Summary

By following these steps, you will install the `write-the-docs` skill in your GitHub wiki repository so that the AI assistant can apply the instructor's documentation guidelines automatically.

## Prerequisites

- You have a GitHub wiki repository for this course (for example, `YourName.wiki`).
- You have cloned your wiki repository to your local computer.
- You have Claude Code installed and connected to your repository.

## Steps

1. Open your wiki repository folder on your computer.
2. Create a new folder named `.claude` at the root of the repository (if it does not already exist).
3. Inside `.claude`, create a subfolder named `skills`.
4. Download the skill file `write-the-docs.md` from the [skill-for-technical-writers](https://github.com/JordanStanchev/Getting-Started-as-User-Assistance-Developer/tree/master/skill-for-technical-writers) folder in the course repository.
5. Copy `write-the-docs.md` into the `.claude/skills/` folder you created.
6. Save all changes and commit them to your repository.

```
your-wiki-repo/
└── .claude/
    └── skills/
        └── write-the-docs.md     ← the skill file goes here
```

## Result

The `write-the-docs` skill is installed in your repository. Claude Code can now detect it and make it available as the `/write-the-docs` slash command whenever you open a chat session in that repository.

## Example

You have cloned your wiki repo to `~/Documents/MyName.wiki`. You open a terminal and run:

```
mkdir -p ~/Documents/MyName.wiki/.claude/skills
cp write-the-docs.md ~/Documents/MyName.wiki/.claude/skills/
cd ~/Documents/MyName.wiki
git add .claude/skills/write-the-docs.md
git commit -m "Add write-the-docs skill for AI-assisted documentation"
```

The next time you open Claude Code in that repository, the `/write-the-docs` command is available.
