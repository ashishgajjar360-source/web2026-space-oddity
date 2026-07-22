# 09: Front page

Write the CSS in `style.css` for a magazine front page laid out entirely with flexbox, and match `goal.png`.

- **The page is a column.** `.paper` is a column, so the masthead, stories, and footer stack down the page with a gap between them.
- **The masthead and footer are rows.** Each one puts its title at the left and its issue or note at the right, on a single row, vertically centered.
- **The stories are a row.** `.stories` is a row with a gap, and the lead is about twice the width of the rail because it uses `flex: 2` against the rail's `flex: 1`.
- **The rail is a column.** `.rail` is itself a column, so its two small stories stack.

Properties: `flex-direction`, `justify-content`, `gap`, `flex`.
