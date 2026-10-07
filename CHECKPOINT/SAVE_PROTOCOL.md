# Live save protocol

Load `LIVE_GAME_SAVE.md` and `LIVE_GAME_SAVE.json` together. JSON null means UNKNOWN. If the two disagree, flag the specific conflict and preserve the existing source before resolving it; do not silently merge.

After actual play, record only resolved actions and explicit resource changes. Update both companions together, with the same checkpoint/date and a source/event reference. Keep proposals, future module stages and unknown numbers separate. Copy an earlier checkpoint to history before replacing it. Blank files under `TEMPLATES/` are forms, never current saves.

Publish a Git commit based on the current branch head and update the ref with that expected head. If another writer changed the branch, reread and reconcile before saving. Reload the saved checkpoint in the next session and verify that position, consequences, resources and remaining unknowns match. Do not run an imaginary encounter merely to test persistence.
