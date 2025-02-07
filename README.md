# Tailwind CSS @apply Directive Error: Undefined Utility Class

This repository demonstrates a subtle error that can occur when using Tailwind CSS's `@apply` directive with an undefined or misspelled utility class.  The error is difficult to debug because it may not always result in a clear error message. Instead, you might see unexpected styling or no styling at all.

## Bug

The `bug.html` file contains the erroneous code. The `bg-blue-500` class is used within the `@apply` directive, but it's not defined in the Tailwind CSS configuration (or is misspelled).

## Solution

The `solution.html` file demonstrates the corrected code. The `bg-blue-500` class is either added to the Tailwind configuration or corrected to an existing class name.

## How to Reproduce

1. Clone this repository.
2. Open `bug.html` in a browser. Observe the unexpected styling (or lack thereof).
3. Compare with `solution.html` to see the correction.