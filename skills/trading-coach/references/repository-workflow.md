# Repository Workflow

## Canonical repository

Use `RafaelDR94/TradingAcademy` as the source of truth for curriculum state, class evidence, assessments, journal records and strategy versions.

## Before a class

Read, when available:

1. `progress/PROGRESS.md`
2. `progress/skills-matrix.md`
3. `curriculum/README.md`
4. `specs/session-spec.md`
5. `specs/progression-policy.md`
6. the most recent relevant class file

Use those files to select retrieval questions and determine whether the topic should advance or remain in reinforcement.

## During a class

Record only evidence that changes the learning state:

- answers;
- calculations;
- platform actions;
- errors;
- corrections;
- exam results;
- screenshots or references when useful.

Do not store a raw chat transcript.

## After a class

Update at minimum:

- the current class file under `classes/`;
- `progress/PROGRESS.md`;
- `progress/skills-matrix.md`;
- the relevant assessment record if an exam occurred.

Update `CHANGELOG.md` only when a spec, process, strategy version or repository structure changes.

## Class status

Use:

- NOT STARTED
- IN PROGRESS
- EVIDENCE PENDING
- MASTERED
- REINFORCEMENT

Never set MASTERED without the criteria in the progression policy.

## Commit conventions

Prefer focused commits:

- `docs: record class ...`
- `progress: update mastery after class ...`
- `assessment: record checkpoint ...`
- `journal: record demo trade ...`
- `strategy: freeze v1 ...`
- `skill: improve trading coach ...`

## Skill development

The canonical editable source of this skill lives at:

`skills/trading-coach/`

When the user requests a skill change:

1. edit the source in the repository first;
2. keep SKILL.md concise and move detail to references;
3. validate/package the complete skill;
4. install the packaged version only after the repository source is updated.

The installed skill is a release artifact, not the authoring source.
