# 01: Navbar

Fix the CSS in `style.css`, and do not change the HTML.

The logo should sit on the left and the three links on the right, all on one row and vertically centered, with a gap between the links. Four things are currently wrong:

- `.navbar` is not a flex container.
- The logo and the links are not pushed to opposite ends of the row.
- They are not vertically centered.
- `.links` has a `gap` set, but the links are still stacked, because a `gap` does nothing until its element is a flex container as well.

Properties: `display`, `justify-content`, `align-items`, `gap`.
