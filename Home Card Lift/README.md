# Home Card Lift

Standalone CSS Loader theme that rounds the Home and Library cover tiles to 12px, clips the cover art so the corners are actually cut, adds a 1px highlight along the top edge and a 1px inner contour, and gives the tiles a soft drop shadow — wider and softer once focused — so the cards read as lifted off the background. The geometry matches tvdeck's cards, so enabling both does not produce two different corner radii.

## Install

Copy the `Home Card Lift` folder into `~/homebrew/themes/` and enable it in CSS Loader; there are no options, it applies as soon as the toggle is on.

## Known limitation

It only styles the portrait cover tiles on the Home screen and the Library grid — wide hero/carousel artwork and in-game pages are untouched — and it depends on Steam class names that a client update can rename.
