# 03: Gallery

Write the CSS in `style.css`. The HTML is done, so match `goal.png`.

There are two parts:

1. `.featured` fills the viewport height and holds a single image centered both across and down. This is the common task of centering one element inside a container, done with a flex container that is tall enough to fill the viewport and centers its content on both axes.
2. `.thumbs` is a row of three images that sit with an even gap and share the width between them. First try spacing them evenly across the row, then give each figure `flex: 1` instead and compare how the two approaches distribute the space.

Also add `max-width: 100%` to the images so that they stay inside their frames.

Properties: `justify-content`, `align-items`, `min-height`, `gap`, `flex`, `max-width`.
