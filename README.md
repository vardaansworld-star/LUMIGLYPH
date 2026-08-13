CharSketch

I made this small web tool to convet images into ascii text directly in the browser,no complex dependecies or backend, just basic html css and js.

to behonest i just wanted a quick way to generate ascii art without downloading heavy software or using random websites filled with ads.

Features

Drag and drop image file(less than 15mb)

change character set (detailed, simple, binary, blocks)

adjust resolution width slider

copy output to clipboard


How to run

Download or clone the files

open index.html in any browser

drop an image and check output

OR

Use live server extension


Known some issues & problems

If u upload a huge image (like 4k photo), browser might freeze for a second because i do pixel math on main thread.

Copied ascii only looks right in monospace fonts. if u paste into word or standard text editor it will look stretched or broken until font is changed to courier or code font.

Height ratio calculation is approx 0.55 so some wide images might look slightly squished depending on screen font rendering.


Project files

index.html - main structure

styles.css - dark layout styles

script.js - canvas pixel math and ascii generator

feel free to change anything if needed.
