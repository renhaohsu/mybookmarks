# Invert the whole page's color

add a new bookmarklet and paste this in URL field

```js
javascript:(function objColor() { d = document.querySelector('html'); d.style.filter = 'invert(1)'; })();
```
