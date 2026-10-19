# goit-js-hw-01

GoIT Fullstack homework #1 for JavaScript: variables, arithmetic, template strings and simple functions.

**Live page:** [https://vladyslav-humenskyi.github.io/goit-js-hw-01/](https://vladyslav-humenskyi.github.io/goit-js-hw-01/) (open DevTools → Console to see the output)

## Tasks

| File | Function | What it does |
| --- | --- | --- |
| `js/task-1.js` | `makeTransaction(quantity, pricePerDroid)` | Returns `"You ordered <quantity> droids worth <total> credits!"` |
| `js/task-2.js` | `getShippingMessage(country, price, deliveryFee)` | Returns `"Shipping to <country> will cost <price + fee> credits"` |
| `js/task-3.js` | `getElementWidth(content, padding, border)` | Returns the full element width: `content + padding * 2 + border * 2` |

Each file logs its sample calls to the console. `index.html` loads all three scripts as ES modules.

## Run locally

Serve the folder with any static server (for example the VS Code Live Server extension) and open `index.html`, then check the browser console.

## Structure

```
index.html
js/
  task-1.js
  task-2.js
  task-3.js
```
