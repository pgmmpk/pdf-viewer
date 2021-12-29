# pdf-viewer
A full screen PDF viewer with pdf.js

https://blog.kroutikov.net/pdf-viewer/

Main point here is to play with the pdf.js library and learn to implement efficient scrolling (with IntersectionObserver). As a bonus I have now full
control over how document is displayed.

## Features

1. Client side rendering: files never leave your local comupter (thanks, pdf.js!)
2. Automatically scales to fit window width.
3. PageDown/PageUp scroll size adjusted (to the half of the scroll window) - I like it more this way :)
4. No dependencies, no third-party libraries - just html and vanilla JS
