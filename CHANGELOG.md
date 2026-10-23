# Changelog

All notable changes to this standalone edition of the-art-of-command-line are documented in this file.

## v1.1.0 — Standalone enhancements (2026-10-20)

- Converted the repository from a fork into a standalone edition with its own history, keeping full upstream credit.
- Added an "About This Standalone Edition" section to `README.md` with the upstream link, base-version provenance, and credit.
- Added `ENHANCEMENTS.md` documenting everything changed in this edition.
- Added `.github/dependabot.yml` for weekly GitHub Actions dependency updates.
- Added markdown linting automation (`.markdownlint.json` and the Markdown check workflow); the check was later scoped via `.markdownlint-cli2.yaml` so it covers this edition's own documentation instead of failing on upstream content.
- Added `.editorconfig` with standard editor settings (UTF-8, LF, 2-space indent).

## v1.0.0 — Upstream baseline (2026-10-20)

- Clean standalone baseline of [jlevy/the-art-of-command-line](https://github.com/jlevy/the-art-of-command-line) at upstream commit `6b50745d2e788add2e8f1ed29010e72659a9a074` (upstream HEAD dated 2023-07-12).
- Fork history severed; all files preserved as-is. No standalone licence file exists upstream; the work is declared CC BY-SA 4.0 in the README License section.
