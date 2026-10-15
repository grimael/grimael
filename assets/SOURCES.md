# Visual Sources

- `banner.svg` and `assets/banner-*.svg`: original bilingual animated designs.
  The introduction cycles through four roles, with data-flow and circuit motion.
  CSS lives inside the SVG image, not in the README. No JavaScript is used.
- `assets/projects/*.svg`: original illustrative project covers. Diagrams are
  conceptual, not screenshots, real measurements or model performance claims.
- `assets/icons/*.svg`: tool brand marks from the owner's existing portfolio
  (`grimus/public/assets/logos`), placed on neutral tiles for both GitHub themes.
  Brand geometry is retained; internal IDs are namespaced to avoid collisions.
  Logos and trademarks belong to their respective owners; no endorsement implied.
- Interface symbols in banners/covers: Lucide, ISC license; see
  `assets/LUCIDE-LICENSE.txt` and https://lucide.dev/license.
- Existing `profile.png` and `profile.jpeg` are preserved unchanged.

Every new visual is local and self-contained: no external font, script, nested
image, foreignObject, remote resource or tracking pixel. Reduced-motion settings
disable animation and leave a static presentation visible. The README retains a
text equivalent of the introduction and skills.

The README uses native Markdown and GitHub-supported HTML. Files under `.preview/`
are ignored local review artifacts. Previous project screenshots are archived
there, not referenced by the profile and not included in the next commit.
