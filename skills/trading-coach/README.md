# Trading Coach - Skill source

This directory is the **canonical editable source** of the Trading Coach skill.

## Rule

Do not treat an installed skill as the authoring source.

Changes follow this path:

```
repo source -> validate -> package -> install
```

## Structure

- `SKILL.md` - control plane and trigger behavior.
- `agents/openai.yaml` - ChatGPT UI metadata.
- `references/` - detailed workflows and domain rules.
- `assets/` - icon and other non-reasoning resources.

## Release procedure

1. Edit files in this directory.
2. Review the diff.
3. Validate the whole skill with the Skill Creator validator.
4. Package the complete directory as `skill.zip`.
5. Install/upload that package in ChatGPT.
6. Test against a real class.
7. If behavior needs adjustment, change the repository source first and release again.

## Design goals

The skill should:

- run full, substantive 30-minute learning cycles rather than ending after a few questions;
- teach conversationally, usually one question at a time;
- show formulas clearly;
- use MT5 demo for Forex mechanics and TradingView for chart/replay work when appropriate;
- use progression by mastery;
- synchronize class evidence, assessments, progress, journal and strategy versions to this repository when GitHub is available;
- keep money real locked until the documented evidence gates are met.

## Repository integration

See `references/repository-workflow.md`.

The skill should read the repository state before a class and update evidence after the class whenever the GitHub connector is available.
