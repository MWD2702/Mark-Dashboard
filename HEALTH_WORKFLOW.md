# Health dashboard update workflow

This file records the default maintenance workflow for Mark's live Health & Performance dashboard.

## Source of truth
- Live health dashboard: `health/index.html` in the `MWD2702/Mark-Dashboard` repository.
- The GitHub Pages dashboard / Home Screen shortcut is the user-facing version.
- The `Training Progress & Tracking` chat is the primary longitudinal input stream for day-to-day health and training data.
- The `Health Dashboard` chat is primarily for dashboard design, functionality, layout, targets, charts and higher-level review.

## Default instruction
Whenever Mark provides a new health or training metric in the `Training Progress & Tracking` chat that is relevant to the live dashboard, treat it as an instruction to update the live Health Dashboard automatically unless Mark says otherwise.

Examples include:
- Weight and waist measurements
- Body fat %, muscle mass and InBody results
- Strength PBs and tracked exercise performance
- Farmer's carry / grip benchmarks
- VO2max and cardio benchmarks
- Relevant WHOOP trend metrics
- Other health or fitness metrics already represented on the dashboard

## Update workflow
1. Read the current `health/index.html` before editing.
2. Update the live dashboard with the new metric while preserving historical data and longitudinal trends.
3. Preserve existing dashboard layout, navigation and functionality unless Mark explicitly requests a design change.
4. Do not overwrite or drop prior metrics unintentionally.
5. Verify the requested data is present in the repository after the write.
6. Tell Mark that the live dashboard has been updated. He should not need to repeat the same data in the Health Dashboard chat.

## Chat workflow
- Calendar data -> Calendar Dashboard chat -> live `calendar/index.html`
- Health/training data -> Training Progress & Tracking chat -> live `health/index.html`
- Health dashboard redesign/functionality -> Health Dashboard chat
- Emma school/report data -> Emma-related workflow / live `emma/` dashboard

## Exceptions
- If Mark explicitly says a data point is provisional, estimated, incorrect, or should not be added yet, do not update the live dashboard.
- If essential details are ambiguous, ask for clarification before writing.
- Medical interpretation and dashboard recording are separate: a metric can be recorded without treating it as a diagnosis.
