# Contact-page development context

## Purpose and architecture
Self-contained static contact page. index.html is the page source; tilda-embed.html is the recommended T123 embed and tilda-inline-t123.html is the inline alternative. The repository is an independent component of the landing workspace.

## Commands and stopping point
No package installation/build manifest is needed. For a local read-only preview: python -m http.server 4192 --bind 127.0.0.1; inspect with HTTP GET and stop the server. Do not click external contact controls, send messages or change published Tilda blocks. Review both T123 alternatives before edits. No automated test suite is defined in this repository.

main is the existing Pages publication branch. The development branch preserves its current source and history without changing publication settings.

## Continuity and boundaries
2026-10-04: a separate development migration branch adds public-safe instructions only. Existing code, assets, Git history and publication branches are preserved. No feature fixes or production changes were made. A GitHub branch is not proof of a published Cloud environment; verify the exact commit and dependency/test results in a fresh task.

Keep private context, credentials, runtime state and personal materials outside public commits. A development checkout of existing raster/history content requires separate privacy review before transfer to a new service. Do not remove original assets automatically. No source-conversation URLs are recorded through supported tools; do not invent links or read internal session stores.
