# AI Acceptable-Use Policy

A plain-language template for small governments and nonprofits. The public mirror of the research piece at [jakelawrence.xyz/research/ai-acceptable-use](https://jakelawrence.xyz/research/ai-acceptable-use): a plain-language AI acceptable-use policy for small governments and nonprofits. Version 1.0.5 is the newest, published 2026-11-21.

> **Not legal advice.** This is a starting template, not legal advice. Public-records and privacy laws differ by state, and procurement rules differ by funder too. Have counsel review it before you adopt it.

Every file here is a frozen release, exactly as the site publishes it, with its checksums. Nothing in this repository is written by hand: it is generated from the site on each release, so the two cannot drift. A correction is made on the site and arrives here as a new version.

| | |
|---|---|
| The live page | https://jakelawrence.xyz/research/ai-acceptable-use |
| The newest release's files | https://jakelawrence.xyz/downloads/ai-acceptable-use/v1.0.5/ |
| One permanent link per version | `https://jakelawrence.xyz/research/ai-acceptable-use/v/<version>` |
| License | CC BY 4.0 ([LICENSE.md](LICENSE.md)) |
| Cite | [CITATION.cff](CITATION.cff) (GitHub's "Cite this repository" reads it) |

## What it is

- **15 rules.** Each is written two ways: how a small office follows it with a spreadsheet, a sign-off or a calendar reminder, and how the publisher's own site enforces it in code.
- **6 yes/no questions** describe an organization; each rule applies to everyone or only when certain answers are yes, so the template can be trimmed to fit.
- **`policy.md`** is the full template, ready to edit. `rules.csv` and `rules.json` hold the same rules as data. `crosswalk.csv` maps them to two outside frameworks.

The crosswalk (from 1.0.4) quotes the NIST AI Risk Management Framework 1.0 outcomes verbatim (a U.S. Government work, not subject to copyright, 17 U.S.C. 105) and names ISO/IEC 42001:2023 clauses and controls by title only, read from public guides, at low or medium confidence. ISO/IEC 42001 is paywalled and keeps its own terms.

The data files name the publisher's own code as evidence for each rule, by path. Those paths are named, not linked: the code they point into is not public.

## Versions

Each folder under `downloads/ai-acceptable-use/` is one frozen version, and `latest.json` names the newest. A released version is never altered.

| Version | Published | Contents | Frozen page |
|---|---|---|---|
| [1.0.5](downloads/ai-acceptable-use/v1.0.5) | 2026-11-21 | 15 rules, 6 questions | [https://jakelawrence.xyz/research/ai-acceptable-use/v/1.0.5](https://jakelawrence.xyz/research/ai-acceptable-use/v/1.0.5) |
| [1.0.4](downloads/ai-acceptable-use/v1.0.4) | 2026-11-21 | 15 rules, 6 questions | [https://jakelawrence.xyz/research/ai-acceptable-use/v/1.0.4](https://jakelawrence.xyz/research/ai-acceptable-use/v/1.0.4) |
| [1.0.3](downloads/ai-acceptable-use/v1.0.3) | 2026-11-20 | 15 rules, 6 questions | [https://jakelawrence.xyz/research/ai-acceptable-use/v/1.0.3](https://jakelawrence.xyz/research/ai-acceptable-use/v/1.0.3) |

Files in each version: `rules.json`, `rules.csv`, `questions.csv`, `policy.md`, `crosswalk.csv`, `CITATION.cff`, `README.md`, `manifest.json`, `SHA256SUMS`. The site's HTML browse page for each version is left out; the files are the release.

## Check it

```
python3 scripts/verify.py
```

checks every file of every version against its `SHA256SUMS` and `manifest.json`, with nothing but the Python standard library. Or, inside one version's folder, `sha256sum -c SHA256SUMS`. The check runs on every push ([.github/workflows/verify.yml](.github/workflows/verify.yml)).

## Cite

Archived on Zenodo with a DOI:

- **All versions** (always the newest): [https://doi.org/10.5281/zenodo.24426960](https://doi.org/10.5281/zenodo.24426960)
- **1.0.5:** [https://doi.org/10.5281/zenodo.24430619](https://doi.org/10.5281/zenodo.24430619)
- **1.0.4:** [https://doi.org/10.5281/zenodo.24426961](https://doi.org/10.5281/zenodo.24426961)

Cite the version you used by its own DOI.

Version 1.0.5, as the release gives it:

```
Lawrence, J. (2026). AI Acceptable-Use Policy (version 1.0.5) [Data set]. https://jakelawrence.xyz/research/ai-acceptable-use. CC BY 4.0.
```

[CITATION.cff](CITATION.cff) is the same in machine-readable form, for version 1.0.5. Each version's own `CITATION.cff` is in its folder. The release files carry `doi: null` by design, since a version is frozen before its DOI can exist; the DOI is recorded in the site's Zenodo registry and in this README and `CITATION.cff`.

## What changed, version by version

From the 1.0.5 release's own README:

- 1.0.5 (2026-11-21): Three evidence citations were unable to fail and so proved nothing: one named a word found in every test file, and two pointed at this policy's own file. Each now names something specific in another file, and a test refuses both kinds from here on. The rules themselves are unchanged.
- 1.0.4 (2026-11-21): Adds a crosswalk: each rule names where it falls in the NIST AI Risk Management Framework 1.0, quoting NIST's outcome text, and in ISO/IEC 42001:2023 by clause and control title, with full or partial fit, a confidence and the reason. Rules with no honest fit say why. The rules themselves are unchanged.
- 1.0.3 (2026-11-20): The page no longer says a test enforces the review date; that test was retired on October 16. The date is shown, and the page now says so at the top once it passes. Answers can be shared as a link, and the export shows a preview before you save it.
- 1.0.2 (2026-11-06): The off-switch rule's note says what is true now: Telegram and email notifications are on by the owner's decision, browser push is still off, and one switch still silences every channel.
- 1.0.1 (2026-09-23): Evidence is named by file path instead of linked, because the repository is private.
- 1.0.0 (2026-09-23): First release: fifteen rules, each with a no-code way to follow it and a link to where this site enforces it in code.

## License

Creative Commons Attribution 4.0 International (CC BY 4.0). See [LICENSE.md](LICENSE.md). Copy, adapt and reuse it, including commercially, with attribution.

## Corrections

Open an issue; see [CONTRIBUTING.md](CONTRIBUTING.md). Corrections are made on the site and mirrored here as a new version, never edited in place in this repository.

Written and edited by Jake Lawrence. Published at [jakelawrence.xyz](https://jakelawrence.xyz).
