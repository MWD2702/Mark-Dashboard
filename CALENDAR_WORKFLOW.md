# Calendar update workflow

This file records the default maintenance workflow for the Daly Family calendar.

## Source of truth
- Live calendar: `calendar/index.html` in the `MWD2702/Mark-Dashboard` repository.
- The dashboard Home Screen shortcut / GitHub Pages site is the user-facing version.
- Standalone HTML files created in chat are not the source of truth unless explicitly requested.

## Default instruction
Whenever Mark adds, changes, moves, renames, or removes a calendar item in the Mark Personal chat:
1. Treat the request as an instruction to update the live calendar.
2. Update `calendar/index.html` in this repository.
3. Preserve the existing calendar design and functionality unless Mark specifically requests a design change.
4. Preserve category colours, month zoom, filters, clickable events, current-day highlight, and Monday/Friday TRT shading.
5. Verify the requested event(s) are present in the repository after the write.
6. Tell Mark the live calendar has been updated. Do not require him to separately say “update GitHub” each time.

## Exceptions
- If Mark explicitly says the item is provisional, a draft, or should not yet be added, do not update the live calendar.
- If essential event details are ambiguous (especially the date), ask for clarification before writing.
