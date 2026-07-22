# 06: Card

Build both the HTML and the CSS from scratch to match `goal.png`.

Work in this order:

1. Look at `goal.png` and mark out the boxes. There is a header row with two sides, an avatar and name on the left and a button on the right, and below it a row of three stats.
2. Write the HTML for those boxes.
3. Style them. The header is a flex row that pushes its two sides apart and centers them vertically. The stats are a flex row of three equal columns, and each column is itself a small flex column with the number stacked above the label.

The main idea here is a row that contains columns, which means a flex container whose children are themselves flex containers running top to bottom.

Properties: `display: flex`, `justify-content`, `align-items`, `flex`, `flex-direction`.
