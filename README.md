# Workboard Maintenance Skill

用于维护现有离线 Workboard 的可复用规则，不是完整 Workboard 应用。
Reusable guidance for maintaining an existing offline Workboard — not a complete dashboard application.

## Included

- Progress highlights instead of raw conversations; current project-specific dependencies.
- Consistent Product memory and Ongoing views, status vocabulary and presentation rules.
- Evidence-backed work rounds, useful AI preparation, and shared To-do / Next steps records.
- Focused regression cases, state-preserving saves and safe sharing boundaries.

## Ruleset update — 2026-11-17

- Current actions stay separate from FYI, preparation logs and historical discussion;
  project archive does not silently complete a newly confirmed action.
- Full reading-view language coverage preserves original evidence and editor values.
- Current status controls, descending Cycle filters, compact Product memory spacing,
  and navigation / Product radar presentation are documented.

These are maintenance instructions for an existing board, not newly bundled application
code, data, assets or connectors. Later explicit user choices take precedence.

## Use

Download or clone this repository. Keep the **entire `workboard-maintenance` directory** together, including `references` and `agents`; do not copy only `SKILL.md`.

Install that directory using your coding assistant’s supported skill-installation method, or ask it to read [`workboard-maintenance/SKILL.md`](workboard-maintenance/SKILL.md) and its relevant references when maintaining your existing board.

Example request:

> Use workboard-maintenance to review my Product memory Progress. Keep consequential highlights, reconcile completed or superseded follow-ups, and preserve my personal state and original evidence.

## Not included

- No personal or company project data, source URLs/IDs, messages, avatars or generated board HTML.
- No account credentials, source connectors, background automation or preconfigured research topics.
- No runnable dashboard, blank application template or conversational setup implementation.

Each user connects their own authorized accounts and defines their own source registry, projects and research area. Installing this skill does not itself provide Teams, Outlook, Loop or Figma access.

**不要把自己的 `private` 目录、生成后的看板 HTML、来源注册表或历史备份提交到本仓库。**

This repository intentionally contains only the generic skill and this introduction. No existing workspace or Git history was copied.
