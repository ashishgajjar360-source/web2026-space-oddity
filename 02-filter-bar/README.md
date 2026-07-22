# 02: Filter bar

Fix the CSS in `style.css`, and do not change the HTML.

The filter buttons should wrap onto new lines when the row runs out of width, with an even gap between them. At the moment they are squashed onto a single line instead of wrapping, and there is no gap between them. Two things are wrong:

- `flex-wrap` is set to `nowrap`.
- There is no `gap`.

After you fix both, narrow the window and the buttons will reflow onto new lines. Note that `gap` sets the spacing between rows as well as between columns.

Properties: `flex-wrap`, `gap`.
