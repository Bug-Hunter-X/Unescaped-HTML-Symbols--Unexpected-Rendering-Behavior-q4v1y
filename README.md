# Unescaped HTML Symbols: Unexpected Rendering Behavior

This repository demonstrates a common yet often overlooked error in HTML: unescaped less than and greater than symbols.  These symbols, when used without proper escaping, can cause unexpected rendering issues and break the HTML structure.

The `bug.html` file showcases the problem, while `bugSolution.html` presents the corrected code.  The core issue is the browser's misinterpretation of unescaped `&lt;` and `&gt;` as HTML tags instead of plain text.

## How to Reproduce

1. Clone this repository.
2. Open `bug.html` in a web browser.
3. Observe the unexpected rendering behavior.
4. Open `bugSolution.html` to see the corrected code and expected output.

## Solution

The solution involves escaping the `&lt;` and `&gt;` symbols using their HTML entities, `&amp;lt;` and `&amp;gt;`, respectively.  This ensures that the browser interprets them as plain text and renders them correctly.