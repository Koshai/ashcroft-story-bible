# Pre-Production Update Manifest — 2026-08-01

## Purpose

This package transitions the repository from worldbuilding-first development into formal game pre-production.

## Add

- `Design/00_Game_Vision.md`
- `Design/01_Player_Experience.md`
- `Design/02_Game_Spine.md`
- `Design/03_Core_Loop.md`
- `Design/04_Investigation_Framework.md`
- `Design/05_Case_Framework.md`
- `Design/06_Level_Design.md`
- `Design/07_Progression.md`
- `Design/08_Design_Principles.md`
- `Production/00_Preproduction_Roadmap.md`
- `Cases/CASE_TEMPLATE.md`
- `Ecosystems/Commerce.md`
- `Organizations/Commerce/Ashcroft_Chamber_of_Commerce.md`
- `Neighborhoods/Eastside_Flats.md`

## Modify

- `README.md`
- `00_CONSTITUTION.md`
- `01_MASTER_INDEX.md`
- `02_CHANGELOG.md`
- `03_SESSION_SUMMARY.md`
- `Cases/Case_Architecture.md`
- `Gameplay/Detective_System.md`
- `Gameplay/Whiteboard_System.md`
- `Decisions/DECISION_LOG.md`
- `World/Districts.md`

## Delete

None. The restructuring is additive to preserve existing canon and Git history.

## Important Open Items

The following are intentionally not canonized yet:

- Exact act count
- Exact case count
- Target total game length
- Full case curriculum
- Exact Case 001 premise
- Exact Chamber leadership
- Detailed Eastside Flats citizens and landmarks

## Suggested Commit

```text
feat(preproduction): establish investigation-first project framework

- add game vision, player experience, and game spine documents
- canonize non-RPG investigation and reasonable confidence
- add case, level, and progression frameworks
- establish demand-driven worldbuilding
- add Commerce, Chamber, and Eastside Flats foundations
- update constitution, indexes, decisions, and gameplay systems
```

## Apply

Extract the changed-files ZIP into the repository root and replace existing files. Then run:

```bash
git status
git add .
git commit -m "feat(preproduction): establish investigation-first project framework"
git push origin master
```
