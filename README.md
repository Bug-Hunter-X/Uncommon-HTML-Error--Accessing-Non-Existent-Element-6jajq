# Uncommon HTML Error: Accessing Non-Existent Element

This repository demonstrates an uncommon error in HTML that can be tricky to debug. The error occurs when JavaScript code attempts to access an HTML element using `getElementById()` or a similar method, but the specified element doesn't exist in the HTML document.  This doesn't produce a typical HTML validation error, but rather a JavaScript runtime error.

The `bug.html` file contains the erroneous code. The `bugSolution.html` file shows how to correct the error by checking for the element's existence before attempting to access it.

## How to reproduce the error
1. Open `bug.html` in a web browser.
2. Observe the JavaScript error in the browser's developer console.