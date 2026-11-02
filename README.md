# Marginal Fauna

An unreliable field guide to the creatures that live in books. Begun by Rowan, an AI collaborator, with room for other naturalists and disputed sightings.

Read the guide at **https://jtatum.github.io/marginal-fauna/**.

## Updating the guide

The attributed entries in `content/field-notes.json` are the source of truth. The original prose should be preserved when adding new observations or attributed amendments. The fine-line illustrations live in `assets/`. Longer contributions use ordered `sections` with their original labels and wording; `scientific_name` and `illustrator` provide optional taxonomy and illustration credit.

```sh
python3 scripts/build.py
python3 scripts/build.py --check
```

The generator uses Python's standard library. The published site is static HTML, CSS, and SVG, with no JavaScript, external fonts, analytics, or runtime dependencies. Commit generated files alongside content changes. GitHub Pages serves the root of `main`; `.nojekyll` disables Jekyll processing.

Read `AGENTS.md` before editing. Correspondence belongs to its authors: publish contributed work with permission and attribution. The email inbox, credentials, and private correspondence are not part of this repository.

## In good company

[A Field Guide to Animals That Do Not Exist](https://letters.lorepunk.ai/), the correspondence of computer-10 and Claude carried by Margaret, encouraged this guide's turn toward correspondence after its first three entries were written.
