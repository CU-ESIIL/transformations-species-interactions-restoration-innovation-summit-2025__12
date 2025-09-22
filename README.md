# Transformations in Species Interactions — Innovation Summit 2025 (Group 12)

This repository is the public home for Group 12 at the 2025 Restoration Innovation Summit. Our sprint focuses on how restoration projects reshape species interactions across Colorado wetland corridors. Use this space to document decisions, share runnable code, and publish the live website that teammates, mentors, and community partners can follow in real time.

## Quick links
- **Live site:** https://cu-esiil.github.io/transformations-species-interactions-restoration-innovation-summit-2025__12/
- **Source code & docs:** https://github.com/CU-ESIIL/transformations-species-interactions-restoration-innovation-summit-2025__12
- **Persistent storage (CyVerse):** `i:/iplant/home/shared/esiil/Innovation_summit/Group_12`
- **Customization checklist:** [TEMPLATE_GUIDE.md](TEMPLATE_GUIDE.md)

## Repository map
| Path | Purpose |
|------|---------|
| `docs/` | MkDocs site content. Edit these Markdown files to update the live site. |
| `code/` | Analysis scripts, notebooks, and workflow notes. Keep runnable assets here. |
| `documentation/` | Internal notes (meeting summaries, planning docs, etc.). |
| `docs/assets/` | Images, GIFs, and downloadable artifacts used on the site. |
| `workflows/` | GitHub Actions for building and deploying the website. |

> Need help finding something? Use the search bar on GitHub or `rg "keyword" -n` locally.

## Update the website (no local setup required)
1. Open the file you want to change under `docs/` (for example, `docs/index.md`).
2. Click the pencil icon (✏️) → make edits in Markdown.
3. Write a short commit message such as `Update Day 1 questions` → **Commit changes**.
4. GitHub Actions will rebuild the site (~1 minute). Refresh the live link to confirm.

See the detailed prompts in `docs/instructions/` for day-by-day guidance on what to capture.

## Working with code
- Save scripts and notebooks to the `code/` directory with clear filenames and header comments.
- Reference important workflows on the [`Code`](docs/code.md) page so others know how to run them.
- Large data should stay off GitHub; link to CyVerse paths or other external storage instead.

## Data & storage
- Shared storage for this group lives at `i:/iplant/home/shared/esiil/Innovation_summit/Group_12`.
- Use [GoCommands instructions](docs/instructions/save-to-persistent-storage.md) for uploading results or pulling shared data.
- Document data sources, access requirements, and licensing notes on [docs/data.md](docs/data.md).

## How to contribute
1. Create a branch or edit on `main` (small changes are fine directly on `main`).
2. Commit descriptive, incremental updates.
3. Open a pull request if you’d like review before merging.
4. Tag teammates in issues or PRs when you need feedback.

## Citation & licensing
- Cite this work using the metadata in [CITATION.cff](CITATION.cff).
- Unless otherwise noted, content is released under the [MIT License](LICENSE).
- Include dataset-specific licenses on the **Data** page and in your analysis notebooks.

Let’s keep the repo tidy, transparent, and up to date so collaborators can jump in quickly.
