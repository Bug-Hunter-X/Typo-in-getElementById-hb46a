# Uncommon HTML Bug: Typo in getElementById

This repository demonstrates a subtle but common error in JavaScript when interacting with the HTML DOM: a simple typo in `getElementById`.  The incorrect usage `getElementByIdx` will lead to a runtime error without providing clear debugging information.  The solution demonstrates the correct usage.

## Bug

The `bug.html` file contains the erroneous code.  The script attempts to access the element with the ID "myDiv" using the incorrect function name. This will cause a runtime error in the browser's console.

## Solution

The `bugSolution.html` file presents the corrected code, using the proper `getElementById` method to replace the text content of the div.