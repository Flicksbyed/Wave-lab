# Wave Lab

A personal 360-wave training planner with an adaptive calendar, brush timer, wash-and-style guide, four-week onboarding, editable inventory and product response logs.

## Open on iPhone

Once GitHub Pages is enabled, open the deployed link in Safari. Use Share → Add to Home Screen for quick access.

## Publishing

In repository Settings → Pages → Build and deployment, choose GitHub Actions. The Publish Wave Lab workflow deploys changes on main. If needed, run it from Actions → Publish Wave Lab → Run workflow.

## Your data

Profile settings and logs are stored only in your browser, not GitHub. Export regularly for backups. Clearing Safari website data removes saved records. Personal photos and haircut history are not included in this public repository.

## Development

Buildless HTML/CSS/JavaScript. Open index.html or serve this folder with any static web server. The App framework view documents the future relational model and API design.

## Version 2

Black and red mobile interface, custom generated hero artwork (fictional model), interactive eight-lane crown trainer, adjustable session targets, animated timer, configurable wash calendar, seven-step conditioning-aware wash guide, activity charts and preserved v1 records. Tight coils and strand thickness are recorded separately. Hair-health sources and barber-technique references are linked in Wave knowledge.

## Research review — October 11, 2026

- Brush studio has Skip stage: actual elapsed time is retained, untouched time is never credited, and history distinguishes completed, completed with skips, and ended early. Each stage records planned/active seconds, status and skip reason.
- Active grooming uses performance.now(), pauses on navigation or hidden tabs, and snapshots the routine when started. Compression uses wall time while the app is open. Unsaved sessions do not survive closing/reloading.
- Wash order: optional gentle pre-detangle → shampoo → optional lather alignment → optional durag → fully rinse shampoo → condition/detangle/rinse → dry and finish. Lather alignment is optional barber technique. A leave-in cream does not replace rinse-out conditioner.
- Wash rhythm includes every other week, weekly and twice weekly, adjusted for scalp needs and buildup. Browser storage failure displays a persistent export reminder.
- Touch controls are at least 44px high. Existing locally saved history/product edits are retained.

Research references: [AAD curly hair care](https://www.aad.org/public/everyday-care/hair-scalp-care/hair/curly-hair-care), [AAD healthy hair tips](https://www.aad.org/public/everyday-care/hair-scalp-care/hair/healthy-hair-tips), [MDN monotonic timer](https://developer.mozilla.org/en-US/docs/Web/API/Performance/now), [WCAG target size](https://www.w3.org/WAI/WCAG22/Understanding/target-size-minimum). Hair-care targets remain editable practical starting points; they are not proven doses for wave growth.
