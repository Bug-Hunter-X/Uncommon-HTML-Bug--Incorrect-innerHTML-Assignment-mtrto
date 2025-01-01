# Uncommon HTML Bug: Incorrect innerHTML Assignment

This repository demonstrates an uncommon bug in HTML related to the incorrect usage of `innerHTML`.  The bug arises from attempting to directly assign an array to the `innerHTML` property, which expects a string. This leads to the content not being displayed as intended.

The `bug.html` file shows the incorrect implementation, while `bugSolution.html` provides the correct solution.

## Bug Description
The primary issue is assigning an array of strings to the `innerHTML` property.  The browser cannot directly interpret the array as HTML content, resulting in an empty or unexpected output. 

## Solution
The solution involves converting the array elements to strings and concatenating them together before assigning to `innerHTML` or using a more appropriate method like `insertAdjacentHTML`. This ensures the browser correctly interprets and renders the HTML content. 