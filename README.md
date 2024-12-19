# Uncommon HTML Bug: Accessing Non-Existent DOM Element

This repository demonstrates a subtle bug in HTML related to accessing DOM elements before they are fully rendered in the DOM tree. Attempting to manipulate a DOM element that hasn't been fully added to the DOM can lead to errors. The solution is provided as an example of how to fix the issue and a brief explanation of the problem.

## Bug

The `bug.html` file contains an example of this error. We try to access and modify `myDiv`'s `innerHTML` before the element is fully parsed and added to the page's DOM.

## Solution

The `bugSolution.html` file offers a corrected version. This fix ensures the element has been added to the DOM before any manipulations take place, preventing the error.