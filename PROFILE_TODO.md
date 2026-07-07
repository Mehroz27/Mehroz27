# Profile TODO

GitHub username (`Mehroz27`), email, and LinkedIn are already wired into `README.md`.
What's left:

## Featured Systems section

- [ ] Add a repo/demo link to `[View Project →](#)` on the **AI Voice Agent — Marketing** card
- [ ] Add your live demo URL to `[Try the Live Demo →](#)` on the **AI Voice Agent — HVAC** card
- [ ] Add a repo/demo link to `[View Project →](#)` on the **AI Newsletter App** card
- [ ] Tighten the AI Newsletter App description to exactly what it does (content generation vs. curation vs. sending) — currently a reasonable placeholder description
- [ ] Confirm/replace the backend & DB in the Newsletter App's tech stack line (marked with a `<!-- REPLACE -->` comment in the file)
- [ ] Optionally add a screenshot/demo GIF to any card (drop into `/assets` and reference with `<img src="./assets/your-file.png" width="100%" />` inside the card)
- [ ] If you build/showcase more public projects later, add more cards following the same `<table>` pattern

## GitHub Actions (contribution snake)

- [ ] This workflow only works when this README lives in the special profile repo: `github.com/Mehroz27/Mehroz27`
- [ ] Push this repo there, then go to the **Actions** tab and make sure Actions are enabled
- [ ] Run the `generate contribution snake` workflow once manually (`workflow_dispatch`) so the `output` branch gets created — after that it refreshes automatically every 12 hours
- [ ] Confirm **Settings → Actions → General → Workflow permissions** is set to "Read and write permissions" (required for the workflow to push to the `output` branch)

## Optional polish

- [ ] No portfolio link is included (removed per your request) — add one back to the hero/Contact sections if you launch one later
- [ ] Swap any shields.io badge colors/icons in the Tech Stack section if you want a different accent than the cyan/violet used throughout
