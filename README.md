# Welcome to the Mobile Developer Challenge

## Task:

When tapping on one of the arrows within the given inner square (see index.html) that square should smoothly move
in the requested direction, most of it then being clipped although not entirely, but leaving the edge
visible that contains the button now pointing back to the center (so that the square can be returned
the center).

When tapping that button the square should return to its original position; e.g. if the square has
been moved to the top, clicking the downwards arrow (which is the only one visible then) causes the square
to move back down, returning it to the center.

In addition to tapping the buttons, swiping the square in each of the four
directions should be possible, including swiping back (single direction) to its original position.
If for instance the square has been moved upwards, swiping down should return it to the center, but
swiping in any other direction in that case shouldn't have any effect.

If you cannot test on an iOS/touch platform, leave away the swipe part and use click events.

Implement for WebKit based browsers only (preferably Safari) and don't use any libraries.

**Have fun!**
