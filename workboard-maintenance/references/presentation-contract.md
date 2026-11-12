# Confirmed Workboard presentation

Read when modifying the existing Workboard interface, status presentation or
resource labels. These are its latest confirmed conventions, not universal UI
rules. Preserve later explicit user changes. Do not reinterpret old one-off
“+1px” requests as instructions to grow fonts on every run.

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
- Ongoing list: project name, status, one concise current-progress sentence.
  No Cycle, Product memory shortcut, duplicated introduction or next-step block.
  Background and next steps stay in details; a description is not progress.
- Project details use separate neutral-gray cycle badges, such as **C4** and
  **C5**, not a combined badge or “Start — · Cycle…” line. Omit unknown cycles.

## One current status model

Use the same status resolver and English vocabulary across Ongoing and Product
memory. Personal overrides normally win over source defaults; do not overwrite
them during refresh. Explicit user corrections require narrowly scoped handling
that preserves newer edits and all unrelated fields.

| Status | Quiet color role |
| --- | --- |
| Planned | Gray |
| In design | Pale pink |
| Design done | Pale teal |
| In development | Pale blue |
| In flight | The same pale blue |
| Shipped | Pale green |
| On hold | Pale amber |

Use the existing semantic tokens, readable contrast and rounded-rectangle badges.
Do not revert In design to purple or use red/orange for normal active work.
Unknown status is an empty/neutral display, not a new lifecycle option. Preserve
historical snapshots and legacy compatibility rather than rewriting history.
Lifecycle, archive, actual approval and measured shipment evidence are distinct.

## Product memory and Progress

- Use **Progress** and English item/section titles, without forced Stage/Phase.
  The content reference controls what belongs here, including expanded content.
- Retain the approved readable typography hierarchy and increased Progress
  entry-title size; do not globally enlarge descriptions and body copy.
- No historical-date selector at the Product memory top.
- Feature crew is one avatar row in detail, not separate PM/Design text rows.
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

- Daily updates uses the true source date in the heading, with a small dropdown
  arrow there instead of a separate top date selector. Keep coverage audit data,
  but do not restore the coverage block below the feed.
- Channel entries name the specific channel, linking that name to the thread;
  the next line is author · concrete update. No generic “Teams” label or trailing
  “Original” link. Do not misattribute mentions as authors.
- Ready to share keeps the two text-only draft sections, **Project highlights**
  and **Celebrate Wins**, personal edits and subtle approved paper-card tilt.
  No “saved locally · unpublished” boilerplate; Archive sits at the bottom of
  the right pane. A draft is not approval to post.
- Product radar keeps independent research, issue dates and styling; a work-source
  refresh must not replace its research or hard-code a new person's area.
- Retain the established MAI/Cowork type, cards and palette, distinct main/side-pane
  backgrounds, light consistent selected states and compact bottom-left controls.
  Retain approved SVG navigation icons, subtle gradients and restrained hover
  motion; respect reduced motion, touch and keyboard use. Do not add imagery
  or alter the desktop companion as part of content maintenance.
