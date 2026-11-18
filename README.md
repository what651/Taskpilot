# TaskPilot AI — React Edition

A responsive student productivity workspace built with React 19 and Vite.

## Run locally

1. Open this folder in VS Code.
2. Open the terminal in this folder (the folder containing `package.json`).
3. Run:

   ```bash
   npm install
   npm run dev
   ```

4. Open the local URL printed by Vite (usually `http://localhost:5173`).

## Included features

- Dashboard with assignment stats, completion progress and upcoming work
- Assignment manager: create, edit, delete, search, filter, mark complete and add checklist steps
- Study planner that prioritizes active assignments by due date and priority
- Focus timer with configurable focus and break durations, pause and reset
- Breakdown Engine that creates an editable starter checklist for a large project
- Monthly calendar with clickable assignment entries
- Dark appearance, editable profile name, JSON export/import and reset
- Local browser persistence via `localStorage`

## Notes

- Data is stored locally in the browser on the device where the app is used. It is not synced between devices.
- The planner and Breakdown Engine use local rules and templates; they do not call an external AI API. No API key is required.
