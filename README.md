# Image Emojifier

A Pen created on CodePen.io. Original URL: [https://codepen.io/jkantner/pen/OoXvMB](https://codepen.io/jkantner/pen/OoXvMB).

An app that turns images into emoji art! Very accurate, but not 100%.

What this does is group the canvas pixels into squares of the emoji size then calculate the average RGB color of each square. Then it converts the RGB values to HSL to simplify emoji matchups, as sets of emojis are structured like this: hue and two arrays for high and low saturation containing emojis arranged from darkest to lightest. Yellow for example uses a hue of 60 and these emoji arrays: [📻,💰,⚱️,📜], [🥃,☀️,😀,🏠]. Incidentally, average pixel colors of black, gray, white, and transparent will override this with 💣, 👽, 👻, and blank.

Update 2/22/21: Theme updates, added dark theme