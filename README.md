# The Capital Gap

A research project examining where capital fails to flow in women's health markets,
framed as a capital-allocation problem rather than an advocacy issue. Built to
position Sophia Blackwelder for investment banking recruiting by demonstrating
research rigor, sourcing discipline, and a genuine investment-thesis mindset.

## Structure

```
index.html                              Landing page / issue index
about.html                              Bio
methodology.html                        Sourcing standards and research process
styles.css                              Shared stylesheet for all pages
issues/
  issue-01-the-missing-middle.html      Issue 01: endometriosis, menopause,
                                         women's cardiovascular health
  issue-02-florida-resilience-capital-gap.html
                                         Issue 02: Florida catastrophe insurance
                                         vs. resilience financing
```

Static site, no build step. Every page links `styles.css` with a relative path,
so it works unmodified from any static host.

## Adding a new issue

1. Copy `issues/issue-01-the-missing-middle.html` as a starting template — it has
   the stat row, chart, callout, and sources-list patterns already wired to the
   shared stylesheet.
2. Add an `<li class="issue-card">` entry to the issue list in `index.html`.
3. Follow the sourcing standard in `methodology.html`: every statistic needs a
   named, linkable, publicly checkable source.

## Publishing

Any static host works — Netlify, Vercel, or GitHub Pages. To use GitHub Pages:
Settings → Pages → Deploy from branch → `main` → `/ (root)`.

## Contact

sophia.blackwelder@duke.edu
