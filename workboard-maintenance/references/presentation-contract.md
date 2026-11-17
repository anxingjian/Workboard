# Confirmed Workboard presentation

Read when modifying the existing Workboard interface, status presentation or
resource labels. These are its latest confirmed conventions, not universal UI
rules. Preserve later explicit user changes. Do not reinterpret old one-off
“+1px” requests as instructions to grow fonts on every run.

## Display language

- EN applies to reading content and all detail panes, not just headings:
  progress, dependencies, task descriptions, source labels/quotes, saved-note
  displays and tooltips. Provenance markers are not language exemptions.
- Translate only the display layer. Preserve original evidence, stored personal
  text, complete history and source dates. Never rewrite editor values or discard
  unsaved input on language switches; keep focus and open panes.
- Add faithful offline translations with newly visible content and check complete
  rendered views, including expanded details and archives. Do not mask missing
  translations, substitute generic summaries, or reuse stale translations after
  source wording changes. Report legacy/unknown-content gaps honestly; a pass
  on current views does not establish complete historical translation.

## My work

- Single-task and multi-task projects both use **project name → action list**.
  Keep project separation stronger than spacing within a group. Do not fabricate
  a project for an unrelated personal action.
- Under the project heading, omit a repeated project-name prefix in the display
  only. Preserve distinct sub-feature names, stored titles and personal edits.
- The optional second line shows an evidenced follow-up counterpart, current
  waiting dependency or real due date/time. No meaningful information means
  no second line. Generic “action needed/design follow-up,” source and old
  planning dates stay out of list metadata.
- Group and standalone separators use **content → 20px → divider → 20px →
  content**, counting existing padding within that space. Separators sit outside
  hover/selected hit areas; cards retain all four rounded corners.
- Ongoing and Archive lists: status badge above the project name, then one concise
  current-progress sentence. Keep DOM and visual reading order aligned;
  this supersedes the earlier title-first/status-below layout.
  No Cycle, Product memory shortcut, duplicated introduction or next-step block.
  Background and next steps stay in details; a description is not progress.
- Archive uses a quiet, unfilled unarchive icon on the right, with **Move to
  ongoing** tooltip and an accessible name identifying the project. Retain a
  native keyboard-operable button and adequate hit area, without a visible
  Restore text button. Preserve archive/restore behavior and ordering.
- The detail-pane **Archive action** is separate from that restore icon:
  keep its existing archive-box artwork, show only the icon at rest, and reveal
  **icon + Archive** on hover or keyboard focus. Reserve expansion space without
  shifting nearby Cycle badges; touch shows the label directly and reduced
  motion skips expansion animation. Preserve the named native button and handlers.
- Project details use separate neutral-gray cycle badges, such as **C4** and
  **C5**, not a combined badge or “Start — · Cycle…” line. Omit unknown cycles.
- Project record editing has no **Reply status** control: communication replies
  are not project progress. Preserve legacy reply state/evidence, not its redundant
  editor copy. Its entry is a named status-adjustment slider icon immediately
  left of Archive in the detail action row, with **Update project status**
  tooltip and accessible name. This supersedes the pencil, which suggested copy
  editing; do not add another entry or a text disclosure below Current focus. Toggle the
  existing form in place, preserving inputs and expanded state across status/
  Cycle updates. Keep translated tooltip/accessible names and read-only history.
  Cycle opens as visible multi-select choices (C6, C5, C4, C3, C2, C1 plus existing
  labels), not free text or another dropdown. Use numeric descending order
  (C10 before C6) consistently in choices, filters and detail badges; keep custom
  labels intact after numbered cycles in their relative order. Opening does not rewrite
  saved labels; clearing all creates an explicit empty override. Actual start
  date is optional under collapsed **Additional details**; preserve existing
  dates without inferring missing ones or changing project ordering. New projects
  use the same controls. Keep keyboard access and independent state fields.
- Native single-select controls keep their chevron inset from the border:
  a 16px icon box with 12px trailing inset and separate text clearance. Preserve
  control dimensions and native selection/keyboard behavior, theme the arrow
  for light/dark, and restore the platform arrow in forced colors. Do not apply
  dropdown artwork to multi-select listboxes.

## One current status model

Use the same status resolver and English vocabulary across Ongoing and Product
memory. Personal overrides normally win over source defaults; do not overwrite
them during refresh. Explicit user corrections require narrowly scoped handling
that preserves newer edits and all unrelated fields.

| Status | Quiet color role |
| --- | --- |
| Planned | Gray |
| In design | Pale yellow with dark text |
| Design done | Pale teal |
| In development | Pale blue |
| In flight | The same pale blue |
| Shipped | Pale green |
| On hold | Pale amber |

Use the existing semantic tokens, readable contrast and rounded-rectangle badges.
Pale yellow supersedes the earlier pink In design label, which felt like an alert.
Do not revert it to pink/purple or use red/orange for normal active work.
Unknown status is an empty/neutral display, not a new lifecycle option. Preserve
historical snapshots and legacy compatibility rather than rewriting history.
Lifecycle, archive, actual approval and measured shipment evidence are distinct.

## Product memory and Progress

- Above the project cards, use **All / Cycle** single-select pills, defaulting
  to All. Derive available labels from eligible projects in the selected source
  snapshot plus personal overrides, in numeric descending order. Multi-cycle projects match
  each corresponding filter; missing cycles remain in All. Do not infer cycles,
  change project order, or persist this reading filter in personal state/history.
  Keep matching details open, close filtered-out project details, and fall back
  to All when the selected label no longer exists. Wrap pills on narrow rails;
  preserve keyboard focus, light/dark contrast and read-only history navigation.
- Keep the filter row compact: 12px header bottom spacing above it and 12px
  between the row and project cards, including narrow and open-detail layouts.
  Preserve the 44px minimum pill hit area, wrapping, heading position and other
  pages' spacing. This supersedes the earlier 24px outer filter-row gaps.
- Project cards open the existing non-modal right-side pane, leaving the index
  and its header visible. While open, use one compact card per row: **copy left,
  image right** when the rail has room; only narrow rail widths move the image
  above the copy. Copy order stays **title → avatars → description → status**.
  Bound card/media size and give spare width to details, rather than enlarging
  the left card. Preserve image proportions and inspected crops; never stretch
  screenshots. This supersedes the earlier always-image-first open-rail rule.
  Closing restores the normal index layout and selected-card focus. Keep images
  optional and nested-topic Back within the pane. Narrow screens retain the
  accessible normal-flow fallback, not an overlay or full-page navigation.
- Inside the pane, **Overview / Progress / Related materials**, notes, coverage
  and nested-topic choices are unboxed: no separate surface fill, all-around
  border, radius or inset card padding. Use whitespace and single section
  dividers where needed, with no leading divider. This explicitly supersedes
  the restored section-card requirement. Keep the single pane title/close/back;
  it does not authorize restoring the previously rejected Current block,
  side-date column, 2:1 detail layout or status/cycle detail-header arrangement.
  Ongoing/Archive status placement and curated content remain unchanged.
- Preserve existing metrics, notes, useful text, links and collapsed source
  coverage. A layout rollback must not rewind project facts, personal overrides,
  source checkpoints or history, nor revive Stage/transcript conventions.
- The Overview's **Current status** uses semantic bullet points instead of a
  paragraph. Separate saved sentences or clear clauses without rewriting facts,
  dropping qualifications or inventing status; preserve source wording. Leave
  Context & scope, Next steps and Progress in their own formats.
- In the Product memory pane, inset the body beneath **Context & scope**,
  **Current status** and **Next steps** by 12px with logical inline spacing.
  Keep their headings aligned and preserve the list's own bullet inset.
  Do not shift crew, Progress or Ongoing content.
- Use **Progress** and English item/section titles, without forced Stage/Phase.
  The content reference controls what belongs here, including expanded content.
- All project Progress uses a continuous muted **1px left rail + 7px dots**
  for both structured milestones and review-backed highlights. Align dots to
  the title's first line; order each entry **English title → summary → real date
  → source links**, newest first. Keep 15/20 titles and 14/20 body/date, natural
  wrapping, 16px vertical padding and 20px left inset. No per-entry card frames
  or transcript expansion. Apply to Product memory, Ongoing and archived-project
  details, including expanded Earlier progress; this supersedes the earlier
  memory-only scope. Preserve shared highlight content and disclosure behavior.
- Retain the approved readable typography hierarchy and increased Progress
  entry-title size; do not globally enlarge descriptions and body copy.
- No historical-date selector at the Product memory top.
- Frame project thumbnails around the actual UI, avoiding black capture edges,
  excess canvas and dimmed overlay backdrops where removable. Inspect each image;
  retain meaningful UI and its proportions rather than applying a blanket zoom.
  Prefer reversible display crops, preserving original image bytes, provenance
  and capture dates. Unrelated screenshots and source evidence remain unchanged.
- Product memory's **Overview does not repeat Feature crew**: the project card
  already provides the member row. Apply this to structured topics and fallback
  project details, without removing card avatars or saved people/evidence.
  This supersedes the earlier crew-row-in-Overview requirement.
  Where crew is displayed, use one avatar row, not separate PM/Design text rows.
  Include known PM/Design and evidenced Eng membership, not everyone in a meeting.
  Avatars overlap by 2px; show name/role accessibly on hover/focus. Missing images
  use initials on a colored circle. Keep readable accessible names.
- Do not restore **View evidence** or crew/resource divider lines. Preservation
  of original evidence does not require adding a visible evidence control.

## Related resources

- Prefix links with the actual destination's app icon: Figma, Teams, Loop or
  the relevant Office app; use a neutral fallback for unknown destinations.
- No link underlines or row separators in Related resources. Retain visible
  keyboard focus and clear link affordance.
- Use the **actual Figma page name**, removing only known status prefixes,
  decorative status emoji/dots and trailing author attribution. Preserve
  meaningful wording/dashes; do not substitute a generic “Feature.”
- Keep distinct pages/configurations (desktop, mobile, history, etc.) even when
  they share one file. Deduplicate the same destination only. Prefer useful
  page/configuration links over arbitrary deeper frame links; never invent IDs.
- List relevant separate Loop documents, including Bug bash/test trackers, not
  just the priorities document. Deduplicate by actual document identity.
- Reusing a known link does not mean its current contents were reread.

## Other confirmed surfaces

- Preserve navigation order: **My work / Daily updates / Product memory /
  Ready to share / Product radar**. Today's actions and information stay
  adjacent, followed by project context; do not restore the older four-page list.
- Daily updates shares My work's header hierarchy, typography, spacing and
  alignment: a small **YYYY.MM.DD** source date with a dropdown chevron above
  the large **Daily updates** title. This supersedes the earlier title-inline
  date. Keep one date control with existing history/return behavior; never use
  today's calendar or build date in place of the displayed source snapshot.
  Keep coverage audit data, but do not restore the coverage block below the feed.
- Channel entries name the specific channel, linking that name to the thread;
  the next line is author · concrete update. No generic “Teams” label or trailing
  “Original” link. Do not misattribute mentions as authors.
- Ready to share keeps the two text-only draft sections, **Project highlights**
  and **Celebrate Wins**, personal edits and subtle approved paper-card tilt.
  No “saved locally · unpublished” boilerplate; Archive sits at the bottom of
  the right pane. A draft is not approval to post.
- Product radar keeps independent research, issue dates and styling; a work-source
  refresh must not replace its research or hard-code a new person's area.
  Topic rows have no numbering or reserved number column. Each product source
  bullet ends with one **🔗Link** to its actual original, with an accessible
  source name; omit the long publication/date/source-title suffix from that row.
  Preserve original publication/update dates, checked dates, scope restrictions
  and evidence in the saved data and details, including older issues.
- Retain the established MAI/Cowork type, cards and palette, distinct main/side-pane
  backgrounds, light consistent selected states and compact bottom-left controls.
  Retain approved SVG navigation icons, subtle gradients and restrained hover
  motion; respect reduced motion, touch and keyboard use. Do not add imagery
  or alter the desktop companion as part of content maintenance.
