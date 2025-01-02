# CSS Specificity Bug: Unexpected Style Override

This repository demonstrates a common CSS specificity issue that leads to unexpected style overrides. The problem arises when selectors with different specificity levels target the same element.

## Bug Description
The primary issue is an unexpected style application. A later-defined CSS rule with higher specificity overrides the style set by an earlier rule with lower specificity.

## How to Reproduce
1.  Clone this repository.
2.  Open `bug.html` in your web browser.
3.  Observe that the paragraph text is red instead of blue, demonstrating the incorrect style application.

## Solution
The `bugSolution.css` file provides a solution by either adjusting the specificity of the initial selector, or changing the selector order to ensure the correct styling is applied. Understanding CSS specificity is crucial for avoiding these common errors.