# \<scary-gallery\>

[![Published on webcomponents.org](https://img.shields.io/badge/webcomponents.org-published-blue.svg)](https://www.webcomponents.org/element/Scarygami/scary-gallery)

`<scary-gallery>` will (try to) layout any of its `<scary-image>` children
to make best use of available space, and rearranges the images, when the
size changes.

Sample usage:
<!---
```
<custom-element-demo>
  <template>
    <script src="../webcomponentsjs/webcomponents-lite.js"></script>
    <link rel="import" href="scary-gallery.html">
    <next-code-block></next-code-block>
  </template>
</custom-element-demo>
```
-->
```html
<scary-gallery min-height="100">
  <scary-image src="https://lorempixel.com/300/200/"></scary-image>
  <scary-image src="https://lorempixel.com/350/250/"></scary-image>
  <scary-image src="https://lorempixel.com/350/200/"></scary-image>
  <scary-image src="https://lorempixel.com/800/200/"></scary-image>
  <scary-image src="https://lorempixel.com/320/200/"></scary-image>
  <scary-image src="https://lorempixel.com/200/200/"></scary-image>
</scary-gallery>
```

Disclaimer:

Work in progress, the algorithm to layout the images is far from perfect.
