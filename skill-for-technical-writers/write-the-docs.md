Write documentation pages following the instructor's guidelines for the UA Developer course.

## Rules

When writing or reviewing any documentation page in this repository, apply the following guidelines:

### Information Types

Every page must belong to exactly one of these information types. Do not mix types on the same page.

| Type | Purpose | Key question answered |
|---|---|---|
| Concept | Background understanding | What is this? |
| Task | Step-by-step instructions | How do I do this? |
| Reference | Lookup data, tables, lists | What are the values/options? |

### Concept Page Structure

Use this structure for every Concept page:

```
# <Title>
## Summary
<Brief summary of what conceptual information this page covers.>
## Detailed Overview
<In-depth explanation. Include images or video links where helpful.>
## Example
<A concrete example that illustrates the concept.>
```

### Task Page Structure

Use this structure for every Task page:

```
# How to <Verb> <Object>
## Summary
<What the user will achieve by following this task.>
## Prerequisites
<What the user must have or know before starting.>
## Steps
1. <First step.>
2. <Second step.>
3. ...
## Result
<What the user will see or have when the task is complete.>
## Example
<A worked example walking through the steps with real values.>
```

### Reference Page Structure

Use this structure for every Reference page:

```
# <Title>
## Summary
<Brief summary of what reference information this page contains.>
## <Appropriate Heading>
<Reference content — tables, lists, or structured data.>
```

### General Writing Rules

1. **Audience first** — before writing, identify who will read this page and what they need to know.
2. **One type per page** — never mix concept, task, and reference content on the same page.
3. **Task titles start with "How to"** — e.g. "How to Sum Up Numbers", "How to Export a Report".
4. **Steps are imperative and atomic** — each step describes one user action, written as a command ("Choose", "Enter", "Select").
5. **Results are observable** — the Result section describes what the user sees or has, not what the software does internally.
6. **Examples use real values** — replace placeholders with specific, realistic data so users can follow along.
7. **Images and video** — include visuals where they clarify a concept or show a UI state. Use a descriptive alt text.
8. **Separate overview from instructions** — a Concept page never contains procedure steps; a Task page never contains deep background theory.

## How to Invoke

When a student asks you to write a documentation page, ask:
1. What is the information type? (Concept / Task / Reference)
2. Who is the target audience?
3. What is the topic or feature to document?

Then produce a complete page following the matching structure above, with no placeholder text left unfilled.

When reviewing an existing page, check it against every rule above and list specific violations with suggested corrections.
