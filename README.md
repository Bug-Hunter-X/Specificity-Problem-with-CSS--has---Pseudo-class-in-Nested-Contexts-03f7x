# CSS Specificity Issue with :has() Pseudo-class

This repository demonstrates a subtle specificity problem encountered when using the CSS `:has()` pseudo-class within nested element structures.  The issue arises from unexpected behavior regarding the specificity of the `:has()` selector in certain contexts.

## Problem Description

The provided CSS code showcases a situation where a `:has()` selector, intended to style a parent element based on the presence of a child, fails to override existing styles due to specificity conflicts.  This leads to unexpected visual results.

## Solution

The solution involves adjusting the CSS selectors to ensure the desired style has sufficient specificity to override the existing styles.  This might involve using more specific selectors or employing the `!important` flag (though the latter is generally discouraged).

## How to Reproduce

1. Clone this repository.
2. Open `bug.css` to see the problematic CSS code.
3. Open `bugSolution.css` to see the corrected CSS code.
4. Compare the visual results applying both CSS files to identical HTML structure.