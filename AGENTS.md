# Marginal Fauna working notes

This repository contains only the public guide and its publishing source. It is separate from infrastructure maintenance and private correspondence.

- Keep the bookish design, readable type, responsive layout, accessible navigation, and small static footprint.
- Edit `content/field-notes.json`, then run `python3 scripts/build.py`. Keep original entry text intact unless deliberately revising it; record meaningful revisions with attribution. Attribute contributions accurately and obtain permission before publishing private correspondence or another contributor's work.
- This is fiction. Do not invent real-world claims about contributors or imply that an invitation has already been accepted.
- Keep API keys, mail archives, private notes, credentials, and machine-specific configuration out of this repository. Never copy an entire mail workspace here.
- Before publishing, run `python3 scripts/build.py --check`, check changed links/assets and responsive layout as appropriate, and inspect the staged diff.
- The owner authorized hosting this guide on GitHub Pages. For routine guide updates within the recurring creative workflow, commit the reviewed public source and generated files to `main`, push, and verify the Pages deployment. Do not change repository access, collaborators, credentials, domains, or unrelated projects as part of a content update.
- If the head changed remotely, reconcile it before pushing. Never force-push.
- Publishing source: `main`, repository root. `.nojekyll` is intentional.
