# Ripple

Provides CSS and JS to add a material ripple effect that is visible on clicking.

* [`winduum/src/libraries/ripple.css`](https://github.com/winduum/winduum/blob/main/src/libraries/ripple.css)
* [`winduum/src/libraries/ripple.js`](https://github.com/winduum/winduum/blob/main/src/libraries/ripple.js)

You can use this together with [Button](/docs/ui/button) component or any other.

## showRipple

* **Type:** `(event) => <void>`
* **Kind:** `sync`

Shows an animated ripple effect

### Example

```js
import { showRipple } from 'winduum/src/libraries/ripple.js'

document.querySelector('#showRipple').addEventListener('click', (event) => {
    showRipple({
        currentTarget: event.currentTarget,
        pageX: event.pageX,
        pageY: event.pageY
    })
})
```
