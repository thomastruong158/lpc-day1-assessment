# LPC — Day 1 Knowledge Check

A self-contained pre/post knowledge-check web app for the **London Premier Centre**
executive programme *Overview of Artificial Intelligence* (Course ID MLDL1149, Paris 2026).

The same six questions are asked twice — once before Day 1 (baseline) and once after —
and the gap between the two scores is reported as the participant's **learning gain**,
alongside a confidence-calibration breakdown and a full answer key.

## Live site

Published with GitHub Pages — see the repository's **Pages** settings for the URL.

## Running locally

It's a single static file with no build step or dependencies. Either:

- Open `index.html` directly in a browser, or
- Serve the folder: `python3 -m http.server` then visit <http://localhost:8000>.

Results are saved in the browser via `localStorage`, so a participant's pre- and
post-test scores persist on the same device/browser. Use **Reset results** on the
home screen to clear them.
