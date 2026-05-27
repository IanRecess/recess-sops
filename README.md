# Recess Supply Ops — SOPs

Internal click-through SOPs for the supply side of Recess. Linked from Notion.

**Live URL:** https://ianrecess.github.io/recess-sops/

## Structure

```
/                       → landing page (index of all SOPs)
/billing/               → How to Submit Billing Info
```

Each SOP is a single self-contained HTML file (no build step, no framework). Drop it in a new subdirectory, link it from `index.html`, and it auto-deploys on push.

## Editing

**Quick edits (typo, link swap):**
- Open the file on github.com → click the pencil icon → commit → live in ~30 seconds

**Bigger edits (full VS Code in browser):**
- Press `.` on the keyboard while viewing the repo on github.com

**Local:**
```
git clone https://github.com/IanRecess/recess-sops.git
# edit, commit, push
```

## Deploy

GitHub Pages is configured to serve from the `main` branch root. Every push to `main` triggers a redeploy (~30 sec).

## Roadmap

- [x] How to Submit Billing Info (in progress — backend webhook still to be wired)
- [ ] Building a Listing
- [ ] Activating Pricing
- [ ] Onboarding a New Supplier
- [ ] Win-Back Workflow
