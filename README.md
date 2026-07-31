# Jail Commissary & Communications Provider — Report Comparison Tool

A single-page, no-install tool that compares two research passes on jail commissary and
communications providers side by side:

- **Report A** — the v6 report (`Jail_Commissary_and_Communications_Providers_v6`)
- **Report B** — a second, independent research pass run after Report A

The goal isn't to re-rank or merge the two reports into one score. It's to make it fast for
someone who has never seen this project to answer: where do the two reports agree, where do
they disagree, and which providers are worth a second look before relying on either one.

## How to open it

No installation, server, or build step required.

1. Download or clone this repo.
2. Double-click `index.html`, or open it from your browser with **File → Open**.

Or use the live version via GitHub Pages (link in the repo's "About" section once enabled —
see **Publishing** below).

## What it does

- Switch between **Communications** and **Commissary** provider lists.
- Filter by tier (**National / Mid-tier / Regional / Adjacent**).
- Filter by facility focus (**mainly jails / mainly prisons / both**).
- Filter by comparison status: **ranked in both reports**, **only in Report A**, **only in
  Report B**, or **ranked in both but at different positions**.
- Search for a company by name.
- Click any company to expand a side-by-side view: what Report A said, what Report B said,
  their cited sources, and a comparison note flagging agreements, disagreements, or
  corrections.
- A pill reading **"unranked (grp N)"** means Report A placed that company inside its
  numbered-but-unranked group of regional specialists at position N in its own ranking
  section — that's why the numbered ranks above N sometimes skip past it. This is
  distinguished from a plain **"unranked"** pill, which means the company isn't part of that
  named group at all (e.g. it only appears in a descriptive table, or only in the other
  report).

## Methodology notes

- All company names, rankings, and report content come directly from Report A and Report B —
  nothing was re-verified against the live web while building this tool.
- Comparison notes labeled **"verified"** mean the two reports independently corroborate the
  same fact (agreement between the two documents), not that a claim was checked against an
  outside source.
- Comparison notes labeled **"corrected"** describe a revision one of the reports made to its
  own earlier draft (stated explicitly in that report's own text), not a correction made by
  this tool.
- Comparison notes labeled **"unverified"** flag something worth confirming directly — a claim
  made by only one report, an internal inconsistency, or a detail that looked questionable on
  a close read — rather than asserting it's right or wrong.

## What's in this repo

- `index.html` — the comparison tool itself
- `GRASP Prompt 1.docx` — the Stage 1 GRASP brief (initial provider research request)
- `GRASP Prompt 2.docx` — the Stage 2 GRASP brief (this comparison-tool request)
- `README.md` — this file
