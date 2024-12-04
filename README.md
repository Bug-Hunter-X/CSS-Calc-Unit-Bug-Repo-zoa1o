# Uncommon CSS Bugs: `calc()` and Unit Issues

This repository demonstrates two uncommon yet critical errors related to the `calc()` function and unit inconsistencies in CSS.  Understanding and avoiding these pitfalls is essential for writing robust and reliable stylesheets.

## Bug 1: Incorrect Spacing within `calc()`

Spaces are crucial when using arithmetic operators within the `calc()` function.  Missing spaces can lead to misinterpretations by the CSS parser, resulting in unexpected calculations and layout issues.

## Bug 2: Inconsistent Units within `calc()`

Mixing different units (e.g., pixels and ems) directly within `calc()` is generally not supported.  The browser may not be able to handle these operations, leading to errors or unexpected rendering. Ensure proper unit conversion or consistency before using `calc()` with multiple units.

## Solutions

The `bugSolution.css` file provides corrected code addressing both issues. Always ensure proper spacing and consistent units within your `calc()` expressions to avoid unexpected behavior.