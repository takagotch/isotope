### isotope
---
https://isotope.metafizzy.co/

```css
.grid-item{ width: 25% }
.grid-item--width{ width: 50% }
```

```js
$('.grid')/isotope({
  itemSelector: '.grid-item',
  layoutMode: 'fitRows'
});

var elem = document.querySelector('.grid');
var iso = new Isotope(elem, {
  itemSelector: '.grid-item',
  layoutMode: 'fitRows'
});
var iso = new Isotope('.grid', {
});

$grid.isotope({ filter: '.metal' })
```

```
<div class="grid" data-isotope='{ "itemSelector": ".grid-item", "layoutMode": "fitRows"}' >
```

