# Next Steps

## On Another Computer
1. Install Git for Windows.
2. Install Node.js LTS.
3. Clone the repository:
   `git clone https://github.com/ljg20002010-design/1.git`
4. Open the project folder in Codex.
5. Configure Codex MCP for Anki.
6. Ensure Anki Desktop is installed.
7. Ensure the AnkiConnect add-on is installed and Anki is running.
8. Test Anki connectivity from Codex.

## Files Worth Syncing Manually
- `C:\Users\49576\.codex\config.toml`
- Any custom files under `.codex\memories\` if they are important
- Project files inside this repository

## Important Notes
- Git syncs files in the repository, not the full local Codex chat/session database.
- If you want cross-device continuity, keep important progress notes in repository files.
- Use `WORKLOG.md` to record what was done.
- Use this file to record the next actionable tasks before switching computers.

## Suggested Workflow
1. Do work in `D:\codex`.
2. Update `WORKLOG.md` and `NEXT_STEPS.md` when you make meaningful progress.
3. Run:
   `git add .`
4. Run:
   `git commit -m "Update work log"`
5. Run:
   `git push`
6. On the other computer, run:
   `git pull`
