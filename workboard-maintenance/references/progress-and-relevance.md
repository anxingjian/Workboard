# Progress and relevance

For task selection and preparation, also use [Work rounds and handoffs](work-handoffs.md).
It supersedes message-to-checkbox extraction: current actions need an evidenced
owner and bounded finish, and project Next steps shares the same task record.
Preparations and source-read steps are not product Progress.

Read before curating Product memory, Ongoing, To-dos or Daily updates, including
source-driven refreshes. These are editorial rules, not authorization to read
new sources.

## Resolve the project before writing the view

For each candidate, establish its stable project identity, scenario/surface,
original author, occurrence date, source and current disposition. Shared people,
file or meeting membership alone do not make a discussion part of the project.
Keep related projects separate unless an explicit scope decision joins them.

Reconcile dated evidence in this order:

1. Latest scoped user confirmation and verified decisions, including supersession.
2. Current conclusion and concrete remaining dependency.
3. Affected old actions: still open, waiting, answered, superseded or complete.
4. New consequential highlights, genuinely new actions and selected FYI.

A newer message is not automatically stronger evidence. Distinguish a proposal
from an adopted decision, and a scoped decision from a whole-project approval.
Retain conflicts/uncertainty when they materially qualify the conclusion.

## Progress composition

Each visible entry contains:

- A short **English outcome/issue title**, not a generic meeting title.
- A concise account of the important change, conclusion or open exploration.
- The actual occurrence/confirmation date, not the curation/build date.
- At most two compact, deduplicated direct citations when available and useful.

Formal reviews, scoped sign-off, substantive thread decisions, consequential
callouts and actual advancement qualify. A review request, recording link,
recap, positive comment or senior attendee alone does not establish approval.
Do not invent a stage or completed milestone because the project just started.

Combine repeated discussion of the same issue around its current outcome.
Retain meaningful earlier evolution as dated highlights; do not make one row
per message or repeat the current conclusion in several sections.

Product memory shows the complete curated sequence. Ongoing details show the
same sequence's latest three entries, with **Earlier progress** revealing earlier
highlights only. Both structured milestones and legacy review-backed projects
follow this contract. Do not restore raw-chat fallback renderers.

### What never belongs inside expanded Progress

- Verbatim messages/transcripts or repeated meeting feedback.
- Old open-question/follow-up lists attached to historical conversations.
- Local maintenance instructions, a user correction transcript, or an audit log.
- A duplicate of the concise summary followed by the same story in source prose.
- Speculative tasks created from missing evidence or a neutral behavior fact.
- Assistant chapter outlines, generated decisions or preparation logs masquerading
  as user work. Direct user commitments in a chat are valid evidence, not permission
  to replay the chat or convert all unfinished discussion into To-dos.

Retain those original records internally where appropriate. This is projection
curation, not deletion of source data. Important uncertainty can qualify the
highlight itself; actual current dependencies belong in Overview/details.

## Current dependencies and actions

Admit a pending item only when it has:

1. A concrete choice, requested action or active dependency.
2. Direct relevance to this project's scope.
3. Evidence that it remains current after later replies/confirmations.
4. Supported ownership if it is presented as the user's To-do.

Do not carry forward routine notifications, handoffs, agenda/scheduling messages,
old sequencing debates, adjacent-feature issues or “no later evidence found.”
A person's name in the thread is not a follow-up assignment. Collaboration
does not mean “waiting for a reply.” A planned date is not a deadline.

Confirmed completion/supersession retires the particular old question, not
unrelated implementation work or independent UX/legal approvals. Cleaning copy
does not silently check personal tasks, change lifecycle, or establish shipment.
Where evidence is inaccessible, preserve a precise provenance gap rather than
creating a generic “verify/follow up” checkbox.

## Citations and resources

Progress citations identify the consequential source, not local cleanup notes.
Deduplicate references to the same channel thread/chat while retaining the
selected real deep link. Use compact app-marked links; do not invent URLs.
Reject unsafe or credential-bearing URLs. Direct user confirmations may remain
internally attributed without a fabricated public citation.

The two-citation limit applies to a highlight, not the project's Related resources.
Distinct design configurations and separate Bug bash/Loop documents belong there.

## FYI is not action

Select relevant updates from the configured channels, email, chats/meetings,
documents and Figma; do not assume only channel posts exist. Follow the board's
chosen section/relevance rules rather than relabelling a chat as channel news.
Clear asks go to the right task/project; FYI does not automatically get a checkbox.
Deduplicate the same event across sources and retain its original date and link.
Previously displayed old news is not fresh simply because it was reread.

## Regression cases — use synthetic data or private tests locally

| Input situation | Required result |
| --- | --- |
| A cleanup instruction quotes several rejected pending items | None becomes Progress or a new dependency; the instruction may remain internally attributed |
| An older follow-up is explicitly completed later | Do not show it as current; retain history and unrelated open work |
| A shared meeting discusses a different feature | Exclude it from this project's projection without claiming it was resolved |
| A user says an observed behavior is a fact, not a defect | Use neutral wording; do not derive a bug/fix action |
| Raw event bodies and historical open lists change, curated highlights do not | Visible Progress stays unchanged in both structured and legacy renderers |
| A project has more than three highlights | Ongoing's first three match Product memory; Earlier progress contains only older highlights |
| Two links identify one thread; another is a local maintenance note | Show one real thread citation, omit the maintenance link, keep total at two or fewer |
| A design is complete but release/sign-off evidence is absent | Preserve the confirmed design fact; do not fabricate approval or shipment |

Use the existing board's focused content/rendering tests where available. In a
documentation-only change, review these cases but do not claim a browser or
application regression run. Do not package private test fixtures with the skill.
