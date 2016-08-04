# Pure-js-tab

Pure-js-tab is plugin for tab navigation without dependencies.

### How to use

Add js to your site\project:

```html
<script src="'PATH_TO_FILE'/pure-js-tab.js"></script>
```

Initialize plugin:

```js
var connectTabs = new Tabs();
```

Give your menu tab elements `data-tab` attribute, corresponding to tab id's, like:

```html
<a href="#orange" data-tab="orange">
  Orange
</a>
<a href="#green" data-tab="green">
  Green
</a>
<a href="#blue" data-tab="blue">
  Blue
</a>
<div id="orange">
  Orange tab content
</div>
<div id="green">
  Green tab content
</div>
<div id="blue">
  Blue tab content
</div>
```

When you click on menu tab elements your tab and menu tab element achieve class `active`, so write some `css` to show\hide tab.

You can find example at - *[codepen](http://codepen.io/wangel13/pen/OXBrRp)*
