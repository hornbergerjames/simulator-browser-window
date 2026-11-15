
The wrapper will change the space available to the project, rather than simply shrink its appearance. That lets viewers see whether columns stack, images resize, and navigation adapts. It demonstrates screen sizes.

This code creates a responsive website preview page that displays a project inside an iframe.

    Toolbar buttons change the preview width: Desktop (100%), Tablet (860px), Mobile Phone (605px), and Small Mobile Phone (375px).
    The iframe loads the homepage from student/index.html.
    JavaScript changes the preview container’s width when a button is clicked.
    CSS centers the preview, sets its height to 80% of the browser window, and smoothly animates width changes.

Because the iframe gives the website its own viewport, its CSS media queries can respond to the selected width. This demonstrates responsive layouts without manually resizing the browser window.

The sizes are demonstration presets; the preview cannot grow wider than the available browser space.


Folder / file Structure - this arrangment is critical

Note: Starting pages must be named Index.html

WebsitePreview/
 ├── index.html       ← Preview page with resize buttons
 └── student/
     ├── index.html   ← homepage
     ├── style.css
     ├── script.js
     └── images/



Layout Desicription

Button	Preview width
Desktop	100% of available width
Tablet	860px
Mobile Phone	605px
Small Mobile Phone	375px




