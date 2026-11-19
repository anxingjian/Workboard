# Workboard Maintenance Skill

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

## How Progress summaries work

**Summarize how a project has changed, not everything people said about it.**

The workflow is:

**Original evidence → project context → reconciled conclusion → curated highlights → relevant next actions**

1. **Establish the project and scope.** Match original messages and replies,
   emails, actual design comments and relevant transcript segments to the
   specific feature. Shared participants or meetings do not imply shared scope.
   Notifications and recording links are not substitutes for reading the source.
2. **Reconcile before summarizing.** Compare new evidence with existing decisions
   and later replies; merge duplicate accounts of the same event. Keep attribution,
   dates, supersession, disagreement and uncertainty. A newer message is not
   automatically more authoritative.
3. **Select consequential changes.** Capture material design evolution, decisions,
   review outcomes and important unresolved choices—not acknowledgments, scheduling
   or raw chat logs. Each highlight has a short English title, a concise account,
   the actual event date and up to two useful, deduplicated source citations.
4. **Separate conclusions from actions.** Reconcile existing work before adding
   tasks. A current action needs evidence, supported ownership and a bounded finish.
   FYI is not an assignment; missing evidence is a coverage gap, not proof of
   unfinished work. Preserve personal plans, checks, notes and overrides.
5. **Use one interpretation across views.** Product memory shows the complete
   curated timeline. Ongoing shows its latest three highlights, with older
   highlights under **Earlier progress**. Original evidence remains preserved
   without being replayed inside expanded Progress.

A proposal is not a decision, a reply is not completed design, positive feedback
is not formal approval, and design completion is not shipment.

The assistant performs evidence-based editorial judgment. An existing board's
validation scripts can check consistency, citations and saved-state integrity;
passing those checks does not independently prove factual accuracy or complete
source coverage. This skill contains guidance, not those scripts or a collector.

See [Progress and relevance](workboard-maintenance/references/progress-and-relevance.md)
and [Work rounds and handoffs](workboard-maintenance/references/work-handoffs.md)
for the detailed rules. This English overview was added on 2026-11-19; it does not
represent a new source refresh or a change to the maintained ruleset.

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

**Never commit your `private` directory, generated board HTML, source registry or history backups to this repository.**

This repository intentionally contains only the generic skill and this introduction. No existing workspace or Git history was copied.
