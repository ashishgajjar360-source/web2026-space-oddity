# 04: Columns

Write the CSS in `style.css`. The HTML is done. Match `goal.png`.

Three feature blocks should sit side by side as equal-width columns with a gap between them. This is the shape of most pricing tables and feature sections.

- `.features` is a flex row with a `gap`.
- `.feature` gets `flex: 1` so the three columns share the width equally, whatever the text length.

Change one block's text to be much longer and confirm the columns stay equal. That is what `flex: 1` buys you over fixed widths.

Properties in play: `display: flex`, `gap`, `flex: 1`.
