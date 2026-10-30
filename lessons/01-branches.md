# GitHub Lab — Lesson 01: Branches

Joey + Rowan

## What just happened

We created a branch named `lesson-01-branches` from `main`.

Think of `main` as the current official version of a project. A branch is a safe alternate timeline where we can experiment without changing the official version yet.

## The four ideas

1. **Repository** — the whole project and its history.
2. **Commit** — a recorded change/checkpoint in that history.
3. **Branch** — an alternate line of development built from a checkpoint.
4. **Pull Request** — a proposal to review and merge one branch into another.

## Our experiment

This file exists on `lesson-01-branches`, but it does not exist on `main` yet.

That difference is intentional. It demonstrates why branches are useful: Rowan can build or modify something away from the official version, Joey can inspect it, and only then do we merge it into `main`.

## Agent Arena connection

When Agent Arena is real, we can use branches for features such as:

- detective agent logic
- world-engine logic
- NPC behavior
- fog of war
- map interface
- narration system
- save/load system

That lets us experiment without wrecking a working build.

**Lab status:** Branch created successfully. First branch-only commit created successfully.
