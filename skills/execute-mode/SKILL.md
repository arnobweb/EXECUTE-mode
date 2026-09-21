---
name: execute-mode
description: Execution continuity mode for complex multi-step work and non-linear thinking. Use only when explicitly invoked by the user.
---

# Execute Mode

## Purpose

Help the user move complex work forward without suppressing non-linear thinking.

## Core principle

Reduce presentation complexity, never reasoning complexity.

Do not force branching thought into a linear process.
Instead, make branches visible, maintain the map, and preserve the path back to the main execution thread.

## EXECUTE

EXECUTE is the main thread.

While in EXECUTE:

- Keep the current objective clear.
- Give only the action or small block of actions needed now.
- Keep the broader plan, dependencies, and risks in mind.
- Do not expose future steps unless they are needed for the current action.
- Do not reopen a validated decision without explicitly identifying why.
- When useful, state the expected result or CHECK before moving on.

Do not turn execution into brainstorming.

## THINK

Do not suppress useful branching.

When a question, discovery, or concern requires deeper exploration, explicitly mark:

**THINK ↗**

Briefly state what caused the branch.

Then explore the issue normally. Do not artificially shorten the reasoning merely because Execute Mode is active.

When the issue is resolved, mark:

**THINK ✓**

Record the conclusion, decision, or implication that matters.

Then explicitly mark:

**↙ RETURN TO EXECUTE**

Restate:
- where execution stopped;
- anything that changed because of THINK;
- the next action.

The user should not have to remember to return to the main thread.

## NOTICE

Use **NOTICE** for a relevant lateral idea that does not justify interrupting EXECUTE.

A NOTICE should make the idea visible without turning it into a new task.

Do not accumulate NOTICE items.

## PARKED

Use **PARKED** only when something genuinely needs to return later.

Every PARKED item must include a specific reopening trigger:

**PARKED:** [item]  
**Reopen when:** [specific phase, event, decision, or condition]

Never create vague "later", "read later", "look into", or someday lists.

When the reopening trigger occurs, proactively surface the PARKED item.

If an idea has no identifiable reason or trigger to return, do not park it.

## Problems and errors

For technical or operational problems, prefer:

diagnostic → test → result → correction

Do not immediately present many alternative solutions unless comparing alternatives is itself necessary.

When validation matters, wait for the result of the current test before moving to the next action.

## State recovery

When the user asks **"Where are we?"**, return a concise state snapshot:

**DONE:** what is completed or validated  
**CURRENT:** the active execution point  
**OPEN THINK:** unresolved branch, if any  
**PARKED:** only items with valid reopening triggers  
**NEXT:** the next concrete action

Do not reconstruct the entire history unless needed.

## User thinking style

Branching is not failure.

The purpose of Execute Mode is not to prevent the user from exploring adjacent questions or ideas.

The assistant maintains the map:
- identify when the conversation leaves the main execution thread;
- allow useful exploration;
- capture decisions that affect the main thread;
- return to the exact execution point afterward.

## Exit

When the user says **"Exit Execute"**, stop applying Execute Mode and return to normal interaction.
