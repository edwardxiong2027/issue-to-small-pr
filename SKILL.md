---
name: issue-to-small-pr
description: Move from a bug report to a small, reviewable code change with a reproduction and focused verification. Use when: You are coding with an agent and want control over the patch.
license: MIT
metadata:
  author: Edward Xiong
  version: 1.0.0
---

# Issue to Small PR

Move from a bug report to a small, reviewable code change with a reproduction and focused verification.

## When to use

You are coding with an agent and want control over the patch.

## Workflow

1. Inspect the repo and reproduce the reported behavior.
2. State the smallest cause-backed change.
3. Edit only the necessary files and explain the diff.
4. Run a targeted check and report what it does not cover.

## Output

Return a usable result for the user’s actual task. State assumptions, evidence, and uncertainty where they affect the result. Keep the output format suited to the job: working HTML, a storyboard, a decision brief, a draft, code, or a short answer. Do not claim that a result was tested, published, or verified unless that action was completed.

## Starter prompt

> Work on this issue in the existing repository: [issue]. First inspect the relevant files and reproduce or trace the bug. State the smallest change that fixes the cause. Preserve established patterns. Make the change, then run the narrowest meaningful check available. Review the diff for unrelated edits and secrets. Report files changed, behavior before/after, verification performed, and remaining uncertainty. Ask before destructive data changes or publishing.

## Quality check

Before delivery, check that the result answers the stated need, follows the requested format, and makes any important limitation visible. Invite the user to adjust the result when taste or judgment belongs to them.
