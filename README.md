# CSS Test for Carney

## Overview

Build this project grid component (from the Landify UI Kit) and try to match the design as closely as possible.

## Specs

- [x] Deliver a plain HTML file if you want, or feel free to use CodePen or a similar site.

- [x] Use vanilla CSS, SCSS, LESS, or whatever you want.

- [x] Use Inter font, available on Google Fonts.

- [x] Each project block should be a link.

- [x] When you hover/focus a project, the other ones should fade out (50% opacity) and the image should become grayscale.

- [x] Projects should become square and stack when the screen is less than `992px` wide.

- [x] No javascript.

## Developer Comments

1. I broke up the SCSS in a way which would make sense for an entire application / website, not just one component. This was purposeful to show my ability to think in terms of scale. I recognize it is slightly overkill for one component.
2. I took time to create the HTML with semantics ( yes, the UL / LIs are purposeful! ), accessibility, and SEO microdata in mind.
3. Technical Audit ( If I were asked to make this for a designer )
    - The mockup uses an `h2` without an `h1`.
    - The mockup uses `h4`s without `h3`s.
    - The mockup does not have `cursor: pointer;` on the links which is an accessibility concern.
    - `1109px` is where content begins to go offscreen. This is because  the total width of the elements + grid gap will always equal `1110px` It would be my recommendation to add a media query at `1109px`
