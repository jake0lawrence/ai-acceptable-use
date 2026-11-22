# AI Acceptable-Use Policy

A plain-language AI acceptable-use policy template for small governments and nonprofits, published by Jake Lawrence under CC BY 4.0. Each rule is written for an organization with no engineers: the rule, why it matters, and a way to follow it with a spreadsheet, a sign-off or a calendar reminder. This record holds one frozen version of the template, so a citation to that version keeps pointing at the words it cited.

## What it is

- `rules.json`: the same version as data. The six questions, and every rule with its number, id, title, the rule text, the reason, the no-code way to follow it, how the publisher's own site follows it, which of the questions make it apply, and the file paths of its evidence that the live page shows.
- `rules.csv`: the rules as one row each, for a spreadsheet.
- `questions.csv`: the six questions that trim the template.
- `policy.md`: the full template with every rule, ready to adapt. The live page asks six questions and trims the template to the rules an organization needs; this file keeps all of them.
- `crosswalk.csv`: where each rule falls in the NIST AI Risk Management Framework 1.0 (NIST's outcome quoted verbatim) and in ISO/IEC 42001:2023 (clause and control titles only, read from public guides because the standard is paywalled): per row the reference, full or partial, a confidence and the reason, plus a row for each rule with no honest fit and why. From version 1.0.4 on; the same is in each rule's `crosswalk` in `rules.json`.
- `CITATION.cff`: how to cite this version, in the Citation File Format.
- `README.md`: the version, the license, the files and how to cite them.
- `manifest.json`: this record's manifest, with the SHA-256 of every file in it. (The website download also carries its own manifest and `SHA256SUMS`; the record's manifest replaces both here.)

## Versions

Each version of the template is frozen when it is published: its files on the website (`/downloads/ai-acceptable-use/v<version>/`) never change, and a frozen page shows it at `/research/ai-acceptable-use/v/<version>`. A change to any rule is a new version, with a changelog entry, and a new version DOI under this record's concept DOI.

## Read with

*Policy as Code, Graded Twice*, a methods preprint by the same author, describes how this template and the self-assessment published beside it are kept true to a running system, and what replaying their checks against the site's own history caught and missed. DOI [10.5281/zenodo.24430329](https://doi.org/10.5281/zenodo.24430329), which always resolves to the newest version of the paper.

## What it is not

Not legal advice. Public-records and privacy laws differ by state, and procurement rules differ by funder. Have counsel review it before adopting it.

The live page names the files in the publisher's code that enforce each rule, and a test re-checks them on every change. The paths the page shows are in the data files as they stood at this version; they point into a private repository and can move without the policy changing.
