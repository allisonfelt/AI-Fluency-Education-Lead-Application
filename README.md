# AI Fluency Education Lead — Application

An application for the [AI Fluency Education Lead](https://job-boards.greenhouse.io/anthropic/jobs/5383242008)
role at Anthropic, built as a website instead of a cover letter.

**Live:** https://allisonfelt.github.io/AI-Fluency-Education-Lead-Application/

## The goal

The job description asks for two things a CV can't demonstrate:

> A working practice of using Claude and other LLMs as infrastructure in your own production

> Enough technical comfort to build light tooling and automations yourself

Those are claims you can only make convincingly by doing the thing. So this
application *is* the evidence — a page I designed, wrote, and built, with the
commit history left public so the claim is auditable rather than asserted.

## The project

A single page, no build step and no dependencies, that reorganises itself
around whatever the reader cares about.

- **A filterable letter.** The six requirements from the job description sit at
  the top as controls. Selecting one dims the letter to just the sections that
  answer it, and narrows Figure 01 to the matching row.
- **Figure 01 — a coverage grid.** Six requirements against six pieces of
  evidence, marked as direct, adjacent, or blank. Two rows are close to empty.
  That is deliberate: the gaps are stated rather than hidden.
- **Figure 02 — a timeline.** 2019 to now, with the audience being taught under
  each role, so the through-line is visible instead of claimed.
- **Figure 03 — the smallest true model.** A conceptual curve, labelled as a
  belief rather than data: telling someone more helps until it doesn't.
- **Figure 04 — leverage.** What I make, handed to the people who deliver it,
  across a boundary I'm deliberately not on the far side of.
- **Figure 05 — alignment.** Six functions converging into one story, because
  at this scale the aligning is the work.
- **Colour encodes provenance.** Each evidence source keeps its hue across the
  stat band, the grid and the timeline, so you can see where a claim comes from.
- **Receipts in the margin.** Every number in the letter sits beside the claim
  it supports, sourced.

## How it's built

| | |
|---|---|
| Markup | One hand-written `index.html`. No framework, no build. |
| Type | Newsreader, IBM Plex Sans, IBM Plex Mono via Google Fonts. |
| Figures | Hand-authored inline SVG on a shared grid. No charting library. |
| Interaction | ~40 lines of vanilla JS for the filter state. |
| Themes | Light and dark, driven by CSS custom properties. |
| Hosting | GitHub Pages, served from `main`. |

Written with [Claude Code](https://claude.com/claude-code) as the production
environment, which is the point rather than a disclaimer.

## Running it

Open `index.html` in a browser. That's the whole toolchain.
