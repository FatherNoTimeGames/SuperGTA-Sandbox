# Documentation

- [Project status](STATUS.md) tracks the current milestone, agreed direction, open decisions, and next task.
- [Power progression](POWER-PROGRESSION.md) records the human-scale baseline, power point goals, and candidate progression mechanics.

Use this directory as the source of truth. Read the status and relevant docs before resuming. Discuss major decisions before recording them. Give each decision one home and link to it from related pages. Mark decisions **confirmed**, **provisional**, **open**, or **deferred** and record the rationale, alternatives, and affected systems.

Review affected docs, links, and dependencies with each commit. Update related code and docs together. Commit and push approved changes, then verify the remote result. Audit consistency every 20 commits since the last audited commit and at major milestones. Record the audited commit in the project status and count from it with `git rev-list --count <audited-commit>..HEAD`.
