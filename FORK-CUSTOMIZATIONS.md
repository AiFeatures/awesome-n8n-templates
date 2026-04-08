# Fork Customizations

> Upstream: [enescingoz/awesome-n8n-templates](https://github.com/enescingoz/awesome-n8n-templates)
> Fork maintained by: @ashsolei
> Last reviewed: 2026-04-08
> Fork type: **light-customization**
> Sync cadence: **quarterly**

## Purpose of Fork

Curated n8n template list; iAiFy carries governance metadata only.

## Upstream Source

| Property | Value |
|---|---|
| Upstream | [enescingoz/awesome-n8n-templates](https://github.com/enescingoz/awesome-n8n-templates) |
| Fork org | AiFeatures |
| Fork type | light-customization |
| Sync cadence | quarterly |
| Owner | @ashsolei |

## Carried Patches

Local commits ahead of `upstream/main` at last review:

- `ef8c112 chore: sync CLAUDE.md and copilot-instructions docs`
- `b11741b docs: update FORK-CUSTOMIZATIONS.md with upstream source`
- `95b971b docs: add FORK-CUSTOMIZATIONS.md per enterprise fork governance`
- `a59a7e9 ci: add copilot-setup-steps.yml for Copilot Workspace`
- `ce3da9a chore: add AGENTS.md`
- `881c149 chore: add CLAUDE.md`
- `554cc0c chore: add copilot-instructions.md`
- `e08c7c4 chore: add Copilot Coding Agent setup steps`
- `4896d3a chore: remove misplaced agent files from .github/copilot/agents/`
- `1d6199e chore: deploy core custom agents from AgentHub`
- `e0dba4c chore: deploy core Copilot agents from AgentHub`
- `1beb494 docs: add FORK-CUSTOMIZATIONS.md`
- `e267ec8 chore: add dependabot.yml [governance-orchestrator]`
- `825dbe1 chore: add CODEOWNERS [governance-orchestrator]`
- `353a8d6 chore: remove unused workflow file`

## Supported Components

- Root governance files (`.github/`, `CLAUDE.md`, `AGENTS.md`, `FORK-CUSTOMIZATIONS.md`)
- Enterprise CI/CD workflows imported from `Ai-road-4-You/enterprise-ci-cd`

## Out of Support

- All upstream source directories are tracked as upstream-of-record; local edits to core source are discouraged.

## Breaking-Change Policy

1. On upstream sync, classify per `governance/docs/fork-governance.md`.
2. Breaking API/license/security changes auto-classify as `manual-review-required`.
3. Owner triages within 5 business days; conflicts are logged to the `fork-sync-failure` issue label.
4. Revert local customizations only after stakeholder sign-off.

## Sync Strategy

This fork follows the [Fork Governance Policy](https://github.com/Ai-road-4-You/governance/blob/main/docs/fork-governance.md)
and the [Fork Upstream Merge Runbook](https://github.com/Ai-road-4-You/governance/blob/main/docs/runbooks/fork-upstream-merge.md).

- **Sync frequency**: quarterly
- **Conflict resolution**: Prefer upstream; reapply iAiFy customizations on a sync branch
- **Automation**: [`Ai-road-4-You/fork-sync`](https://github.com/Ai-road-4-You/fork-sync) workflows
- **Failure handling**: Sync failures create issues tagged `fork-sync-failure`

## Decision: Continue, Rebase, Refresh, or Replace

| Option | Current Assessment |
|---|---|
| Continue maintaining fork | yes - governance overlay only |
| Full rebase onto upstream | feasible on request |
| Fresh fork (discard local changes) | acceptable |
| Replace with upstream directly | possible |

## Maintenance

- **Owner**: @ashsolei
- **Last reviewed**: 2026-04-08
- **Reference runbook**: `ai-road-4-you/governance/docs/runbooks/fork-upstream-merge.md`
