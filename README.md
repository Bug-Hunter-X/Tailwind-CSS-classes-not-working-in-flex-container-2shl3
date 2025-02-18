# Tailwind CSS issue in flex container
This repository demonstrates a problem where Tailwind CSS classes don't seem to apply correctly to elements within a flex container.  The expected behavior is for both divs to have their respective background colors. However, only one or neither may be styled correctly. This often happens due to unexpected order or conflicting styles.

## Steps to reproduce:
1. Clone this repository.
2. Open `index.html` in your browser.

## Solution:
The solution involves carefully reviewing your CSS order and ensuring that your Tailwind directives are correctly applied and not being overridden by other styles. The `bugSolution.js` file provides a working example.