# 08: Article

Write the CSS in `style.css`. The HTML is a small editorial article page, so match `goal.png`.

This exercise is about laying out a page so that it reads well, which comes down to two things:

- **A centered column at a readable width.** Give `.post` a `max-width` of around `60ch` (look up what this is!) and center it on the page. A column that runs too wide produces long lines that are harder to read.
- **Rows that split left and right.** The `.byline`, which holds the author and date, and the `.post-foot` are each a flex row whose two ends are pushed apart.

Properties: `max-width`, `margin`, `display: flex`, `justify-content: space-between`.
