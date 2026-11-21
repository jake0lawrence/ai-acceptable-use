# AI Acceptable-Use Policy, version 1.0.4

A plain-language AI acceptable-use policy for small governments and nonprofits: fifteen rules, each with a no-code way to follow it.

Published 2026-11-21. License: CC BY 4.0 (https://creativecommons.org/licenses/by/4.0/). Canonical page: https://jakelawrence.xyz/research/ai-acceptable-use

> This is a starting template, not legal advice. Public-records and privacy laws differ by state, and procurement rules differ by funder too. Have counsel review it before you adopt it.

## Files

- `rules.json`
- `rules.csv`
- `questions.csv`
- `policy.md`
- `crosswalk.csv`
- `CITATION.cff`
- `README.md`
- `manifest.json`
- `SHA256SUMS`

`policy.md` is the full template (every rule, no questions answered out). `rules.csv` and `rules.json` hold the same rules as data, with the question answers that make each one apply. `crosswalk.csv` (and each rule's `crosswalk` in `rules.json`) maps the rules to the NIST AI Risk Management Framework 1.0 and to ISO/IEC 42001:2023: per mapping the reference, full or partial, a confidence and the reason, and per gap the reason there is no honest fit. NIST outcomes are quoted from NIST's own text; ISO/IEC 42001 is paywalled, so its rows carry clause and control titles only, read from public guides, at low or medium confidence.

Verify the files with `sha256sum -c SHA256SUMS`.

## Cite as

Lawrence, J. (2026). AI Acceptable-Use Policy (version 1.0.4) [Data set]. https://jakelawrence.xyz/research/ai-acceptable-use. CC BY 4.0.

## Changes

- 1.0.4 (2026-11-21): Adds a crosswalk: each rule names where it falls in the NIST AI Risk Management Framework 1.0, quoting NIST's outcome text, and in ISO/IEC 42001:2023 by clause and control title, with full or partial fit, a confidence and the reason. Rules with no honest fit say why. The rules themselves are unchanged.
- 1.0.3 (2026-11-20): The page no longer says a test enforces the review date; that test was retired on October 16. The date is shown, and the page now says so at the top once it passes. Answers can be shared as a link, and the export shows a preview before you save it.
- 1.0.2 (2026-11-06): The off-switch rule's note says what is true now: Telegram and email notifications are on by the owner's decision, browser push is still off, and one switch still silences every channel.
- 1.0.1 (2026-09-23): Evidence is named by file path instead of linked, because the repository is private.
- 1.0.0 (2026-09-23): First release: fifteen rules, each with a no-code way to follow it and a link to where this site enforces it in code.
