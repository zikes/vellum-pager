# vellum-pager

A pagination control.

### [Demo](http://polymer.zikes.me/bower_components/vellum-pager/demo/index.html)

## Simple Example

```
<vellum-pager pages="50"></vellum-pager>
```

![basic](./screenshots/basic.png)

## Custom Distance

```
<vellum-pager distance="5" pages="100"></vellum-pager>
```

![distance](./screenshots/distance.png)

## Bound Page

```
<template is="dom-bind">
  <vellum-pager pages="100" page="{{page}}"></vellum-pager>
  <p>Current page: <strong>{{page}}</strong></p>
</template>
```

![bound-page](./screenshots/bound-page.png)

## Arrows

```
<template is="dom-bind">
  <vellum-pager just-arrows pages="100" page="{{page}}"></vellum-pager>
  <p>Current page: <strong>{{page}}</strong></p>
</template>
```

![arrows](./screenshots/arrows.png)

## a11y

The host element is focusable (as well as the clickable links) and as long as
the component has focus you can navigate with `left` and `right` arrow keys and
use `home` and `end` to go to the first and last pages.

![a11y](./screenshots/a11y.png)
