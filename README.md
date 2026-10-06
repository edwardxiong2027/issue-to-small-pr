# Issue to Small PR

Move from a bug report to a small, reviewable code change with a reproduction and focused verification.

**Author:** Edward Xiong  
**Format:** Portable Agent Skill (`SKILL.md`)  
**Updated:** October 6, 2026

## Use it

Copy `SKILL.md` into an agent skill directory supported by your tool, or paste the starter prompt into a chat model and replace the bracketed inputs. The instructions are model-agnostic.

## What it does

You are coding with an agent and want control over the patch.

## Workflow

1. Inspect the repo and reproduce the reported behavior.
2. State the smallest cause-backed change.
3. Edit only the necessary files and explain the diff.
4. Run a targeted check and report what it does not cover.

## References

- [Agent Skills specification](https://agentskills.io/specification)
- [Related reference](https://agentskills.io/specification)

## License

MIT. See `LICENSE`.
