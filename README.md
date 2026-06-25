# Static Site Theme

Shared generic theme assets for static web sites. The repo currently
exports the base stylesheet and reset used by sites that want the same
visual foundation while keeping their own page content, images, favicons,
and site-specific templates.

## Contents

- `site/styles.css` and `site/reset.css` - shared typography, colors, and layout
- `site/hpp/nav.html` and `site/hpp/nav-item.html` - shared navigation shell and item renderer
- `site/hpp/nav-icon-*.html` - shared navigation icon templates
- `site/attributions.txt` - icon attribution for theme-owned icons
- Generic content primitives such as `.entry`, `.details`, `.section-label`, and
  `.entry-meta`
- Generic two-column layout primitives: `.two-column`, `.two-column__rail`,
  `.two-column__body`, `.two-column__stream`, `.two-column__entry`,
  `.two-column__figure`, and related rail alignment, sticky, and caption classes

Consuming apps own nav item data, the current page key, external profile URLs,
site-specific templates, concrete page composition, content model selectors,
images, favicons, and any sizing or styling hooks for their own media and
content.
