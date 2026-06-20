# T3 Code mini PR plan

## 01 changed files card
Change: restore the changed-files card/file tree design from PR 2451 without bundling unrelated picker changes.
Images needed:
- OLD: upstream card showing `CHANGED FILES (2)` and old file tree styling.
- NEW: patched card showing `2 changed files`, restored file tree layout, file icons, and diff totals. Use `01 changed files card/new-changed-files-card.png`.

## 02 split service tier controls
Change: split provider traits into separate compact controls, including Service Tier as its own dropdown. Keep this separate from checkmark styling.
Images needed:
- OLD: combined traits/service-tier picker. Use `02 split service tier controls/old-combined-service-tier-control.png`.
- NEW: split controls in the composer footer, with Service Tier as its own dropdown. Use `02 split service tier controls/new-split-service-tier-control.png`.

## 03 move menu selection checkmarks to the right
Change: remove the default left-side radio/check indicator from picker menus and place the selected checkmark on the right side.
Images needed:
- OLD: menu with the left-side selected check. Use `03 move menu selection checkmarks to the right/old-access-mode-left-check.png`.
- NEW: same menu with selection indicator on the right. Use `03 move menu selection checkmarks to the right/new-right-side-checkmark.png`.

## 04 make selected menu checks blue
Change: style the right-side selected checkmark blue.
Images needed:
- OLD: right-side/default-position check before blue styling. Use `04 make selected menu checks blue/old-default-colored-check.png`.
- NEW: right-side selected check in blue. Use `04 make selected menu checks blue/new-blue-right-side-checkmark.png`.

## 05 model picker favorite button
Change: replace custom favorite button styling with shared `Button` using `variant="ghost"` and icon sizing.
Images needed:
- OLD: old favorite star button/tooltip area. Use `05 model picker favorite button/old-favorite-button.png`.
- NEW: favorite star using the shared button styling. Use `05 model picker favorite button/new-favorite-button.png`.

## 06 chatbar provider badge clipping
Change: fix clipped provider/model badge icon in the chatbar.
Images needed:
- OLD: chatbar model badge where circular icon is clipped flat at the bottom. Use `06 chatbar provider badge clipping/old-clipped-provider-badge.png`.
- NEW: chatbar model badge with full circular icon visible. Use `06 chatbar provider badge clipping/new-provider-badge-unclipped.png`.

## 07 previous tool call row
Change: keep previous tool-call row same size, muted, and restore `tool call` wording.
Images needed:
- OLD: row showing unmuted/incorrect previous tool call text. Use `07 previous tool call row/old-previous-tool-calls-row.png`.
- NEW: row showing muted `+ 1 previous tool call` or plural equivalent. Use `07 previous tool call row/new-muted-previous-tool-calls-row.png`.

## 08 default badge
Change: replace inline `(default)` option text with a compact `Default` badge in picker menus.
Images needed:
- OLD: menu showing `Medium (default)` / `Standard (default)`. Use `08 default badge/old-default-text.png`.
- NEW: same menu showing `Medium` / `Standard` plus compact `Default` badge. Use `08 default badge/new-default-badge.png`.

## 09 Work Log capitalization
Change: rename the mixed activity group label from `work log` to `Work Log`.
Images needed:
- OLD: activity group heading showing lowercase `work log`.
- NEW: same heading showing `Work Log`. Use `09 Work Log capitalization/new-work-log-capitalized.png`.

## 10 Preserve brand icon colors
Change: stop muting/filtering editor brand icons in the open-in-editor picker while keeping generic file-manager icons muted.
Images needed:
- OLD: Zed/GitHub-style brand icons dimmed in the editor picker. Use `10 preserve brand icon colors/old-muted-brand-icons.png`.
- NEW: same menu with brand icons at full intended contrast/color. Use `10 preserve brand icon colors/new-brand-icons-preserved.png`.

## 11 Unify menu shortcuts with Kbd
Change: render menu shortcuts through the shared Kbd component so shortcuts like Ctrl+K and Ctrl+O have the same pill treatment.
Images needed:
- OLD: mixed shortcut rendering where Ctrl+K uses Kbd styling but menu Ctrl+O is plain muted text. Use `11 unify menu shortcuts with Kbd/old-mixed-menu-shortcuts.png`.
- NEW: same UI with menu shortcuts rendered through Kbd as well. Use `11 unify menu shortcuts with Kbd/new-unified-kbd-shortcuts.png`.
