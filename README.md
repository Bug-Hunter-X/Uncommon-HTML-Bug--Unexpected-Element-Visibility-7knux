# Uncommon HTML Bug: Unexpected Element Visibility

This repository demonstrates an uncommon bug related to manipulating the `display` property of an HTML element using JavaScript.  The bug is subtle and might not manifest consistently across different browsers or versions.

## Bug Description
The bug involves setting the `display` property of a div element to `none` and then to `block`. In some situations, the element remains hidden even after the `display: block;` style is applied. This is because of the timing of the scripts and possibly the browser's rendering engine. The bug shows how subtle timing issues can cause unexpected behavior in HTML. 

## Bug Reproduction
1. Open `bug.html` in your browser.
2. Observe that the text within the div might not always be visible, despite the JavaScript attempting to show it.

## Solution
The solution involves a minor modification to the script to ensure the visibility change takes effect reliably. The solution fixes the timing issues involved.

## How to run
Simply open the HTML files in your browser to reproduce the bug and see the solution.