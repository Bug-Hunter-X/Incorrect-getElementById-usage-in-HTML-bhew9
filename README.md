# Incorrect getElementById usage in HTML
This repository demonstrates a common error when using the `getElementById` method in JavaScript within an HTML file. The incorrect usage is highlighted and a correct solution is provided.

## Bug
The bug lies in the JavaScript code that attempts to select the HTML element with the ID "myDiv". The incorrect code includes the '#' symbol, which is not needed.  The correct usage involves only passing the element ID string.

## Solution
The solution corrects the JavaScript code to properly use the `getElementById` method without the '#' symbol. This ensures the correct element is selected.

## How to reproduce
1. Clone this repository.
2. Open `bug.html` in a web browser.
3. Observe that the console will log `null`, indicating the element was not found.
4. Open `bugSolution.html` to see the corrected code and confirm that the element is found correctly.