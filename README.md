# Rollover buttons

There are multiple ways to do rollover buttons, but this one is a standout because it uses CSS very efficiently.

1. Create an image - top half with the "on" effect, and bottom half with the "off" effect.
2. Create a HTML div and style it. The size of the div should only fit one half of the image.
3. Use the *hover* pseudoselector. Upon mouseover, the *background-position* property should be changed to reflect what state the button is.

This is good as it cuts down the number of images required by 50%. For small buttons, the images required are correspondingly small. Accordingly, the loading time is negligible, and in any case, the loading time is only felt upon loading the page, and subsequently the image is simply "shifted" to show different states of the button. No JavaScript required for this effect.
