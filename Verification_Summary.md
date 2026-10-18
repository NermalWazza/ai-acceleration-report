# BP-AI-WAVE-001 — Verification Summary

## Portfolio appearance update 18 October 2026

The original verification and release-preparation record below is historical. The report is now published at https://nermalwazza.github.io/ai-acceleration-report/.

The public report now includes a small inline appearance script that follows the Light, Dark or System choice on the portfolio homepage. The preference is stored locally in the browser; the script makes no network requests. Existing text and SVG artwork are retained. Light and dark rendering, saved preference, cross-tab updates and System behavior were checked for this appearance update. The original 16 October contrast results below describe that earlier edition, rather than a new exhaustive accessibility audit of both palettes.

---

Date: 2026-10-16 (Perth) · Report: `AI_Civilisational_Transformation_Report.html` v1.1
Status: **Complete and verified for review. Nothing published; no accounts created; no private project files included.**

## 1. Figures checked against primary sources

| Claim in report | Primary source read | Result |
|---|---|---|
| Training compute 4.1× (3.7–4.6) notable; 5.3× (4.9–5.7) frontier; 3.3–4.2× recent frontier | Epoch AI blog | Verified. Old "4–5×" wording replaced with exact figures |
| METR doubling: 196.5 d (2019–25), 130.8 d [107–161] since 2023, 88.6 d since 2024; >16 h unreliable | METR TH1.1 blog, METR time-horizons page | Verified. Old "~7 months" qualified; ≈1 h Claude 3.7 Sonnet from METR 2025-03 blog |
| Price fall 9–900×/yr, 40× example; independent 5–10×/yr, ~3×/yr algorithmic | Epoch (partial read), arXiv 2511.23455 | Verified. **"Median ~50×" removed** (not found) |
| Data-centre electricity 415 → 945 TWh; ~30%/yr accelerated servers; US +240 TWh; 2035 range ~700 to >1,700 TWh | IEA Energy and AI | Verified. **"AI facilities quadruple" removed** (secondary only) |
| FBI IC3 2025: 1,008,597 complaints; $20.877 bn; 2024 $16.6 bn; AI-related 22,364 / $893,346,472; investment AI-nexus >$632 M | IC3 PDF (text extracted locally) | Verified. "Likely undercount" reworded to the report's own caveat; release date dropped (not in PDF text) |
| AI Index 2026: $581.7 bn, 53%/28.3%, −~20% developers 22–25, 58→40, 77.3%, 12%, 83%, 5%, 31%, 362/233 incidents, 88%, 50.1% clocks, SWE-bench 60%→~100% | HAI takeaways page + report page | Verified. Note: US private AI investment ($285.9 bn) is a different measure |
| Pew June 2025: 50% / 10% / 38% | Pew short read | Verified |
| WHO: −1.8 y 2019–21 | WHO 2025 news release | Verified, **plus** WHO 2026-10-02: 73.3 y (2023) vs 73.4 (2019); HALE 62.8, −0.4 — added |
| GitHub Pages limits (1 GB, 100 GB/mo soft, 10 builds/h soft, IP logging) | GitHub Docs | Verified. Plan/visibility availability not stated on pages read |
| Cloudflare Pages: 500 builds, 20,000 files, 25 MiB, 100 domains | Cloudflare Docs | Verified. No bandwidth statement; "unmetered" unverified |
| ChatGPT "900 M weekly users" | none found | **Removed** |

## 2. Remaining issues

1. xAI Colossus scale/power: low-authority, conflicting sources; used qualitatively only.
2. Historical dates in §4 are standard reference dates, not re-checked.
3. Epoch price page read in part (first ~100k of ~300k characters).
4. Strauss–Howe cycle length and critiques rest on secondary summaries.
5. Surveillance, power concentration, cyber, misinformation, unequal access: not quantified.
6. GitHub Pages availability for your plan/repo visibility: confirm before use.
7. Author name for the licence notice: placeholder `[author name to be confirmed]`.
8. No approved HTML template found; design adapted from an earlier private dark-themed report.

## 3. Layout, accessibility, offline checks (browser pane, 2026-10-16)

- 375 px width: no page-level horizontal overflow; sticky horizontal nav scrolls; tables scroll in their own wrapper; charts scroll sideways inside their figure at ≥560 px so labels stay legible.
- 0 elements below WCAG 4.5:1 contrast in the automated check; one `h1`; no heading-level skips; `lang="en-AU"`; all 6 SVGs have `role="img"` plus title/description; visible focus styles; skip link; reduced-motion respected; print stylesheet switches to light.
- 0 external resources loaded (no scripts, fonts, images, trackers); 0 broken internal anchors; 23 outbound links, all user-initiated. Not tested: screen-reader run, real print preview, outbound link liveness beyond the fetches above.

## 4. Provisional release preparation (NOT executed)

Licence: CC BY 4.0 for original text and SVGs (deed read: share/adapt incl. commercially; credit, link licence, indicate changes; no extra restrictions; does not cover cited data; no warranty). Suggested notice: "© 2026 [author name]. Licensed under CC BY 4.0. Text and illustrations drafted with Claude (AI); figures belong to the cited sources."

GitHub Pages steps once you approve (each needs your approval):
1. Confirm current GitHub Pages terms for your account and repo visibility.
2. Create a public repo; add `index.html` (copy of the report), `LICENSE` (CC BY 4.0 text), short `README.md`.
3. Enable Pages from the main branch; check the URL, offline save and print.
4. Add an Issue template ("what is unclear / wrong / source").
5. Record corrections in the git history.
