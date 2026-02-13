# Phase 2: Plan

After the user reviews research.md, write a detailed implementation plan to `.claude/plan.md` using the template at `assets/templates/plan-template.md`.

## What the Plan Must Include

- Detailed explanation of the approach
- Code snippets showing the actual changes (not pseudocode)
- File paths that will be modified or created
- Considerations and trade-offs
- How the changes integrate with existing patterns found in research

## Rules

- Base the plan on the actual codebase. Read source files before proposing changes. Never design in a vacuum.
- When the user provides reference code from open source or other projects, use it as a concrete model — not vague inspiration.
- Every code snippet must reference a real file path in the project.
- If a change touches an existing function, show the before and after.

## Example Prompts

```
I want to build a new feature <name and description> that extends the system to
perform <business outcome>. write a detailed .claude/plan.md document outlining
how to implement this. include code snippets
```

```
the list endpoint should support cursor-based pagination instead of offset.
write a detailed .claude/plan.md for how to achieve this. read source files
before suggesting changes, base the plan on the actual codebase
```

## Phase Exit

End the plan with: *"Ready for your review. Add any inline notes and I'll update the plan accordingly."*

**Do NOT implement yet.**
