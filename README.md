# Project board

Live kanban for Hannes & Ludwig, rendered by GitHub Pages from `board.json`.

- **View:** the Pages URL for this repo
- **Update:** chats read `board.json`, merge their changes, and commit it back (see the chat rules file for the protocol)
- **Schema:** `{ project, updatedAt, tasks: [{ id, title, status: backlog|in_progress|review|done, owner, progress, note, updatedBy, updatedAt }], activity: [{ at, by, text }] }`

Do not store secrets or sensitive data here — this repo is public.
