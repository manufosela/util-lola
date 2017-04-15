# util-lola [![Published on webcomponents.org](https://img.shields.io/badge/webcomponents.org-published-blue.svg)](https://www.webcomponents.org/element/owner/my-element)

Polymer component based in (LoLa (loading layer)) https://github.com/manufosela/LoLa

# Use
<util-lola active="true" message="Loading app..." timeout="30"></util-lola>

Put the component in your polymer app.

* **active** value attribute to show Loading Layer
* **message** value to show in Layer
* **timeout** value if you want to close in that seconds.

Change **active** attribute to **false** in a callback to close the Loading Layer when all process has loaded.

<!--
```
<custom-element-demo>
  <template>
    <link rel="import" href="https://raw.githubusercontent.com/Download/polymer-cdn/master/lib/polymer/polymer.html">
    <link rel="import" href="util-lola.html">
    <next-code-block></next-code-block>
  </template>
</custom-element-demo>
```
-->
```html
<util-lola active="true" timeout="2" message="2 seconds demo"></util-lola>
```
