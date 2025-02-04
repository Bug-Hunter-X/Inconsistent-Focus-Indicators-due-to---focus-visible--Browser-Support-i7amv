# Inconsistent Focus Indicators due to `:focus-visible` Browser Support

This repository demonstrates a common accessibility issue related to the `:focus-visible` pseudo-class in CSS.  The `:focus-visible` pseudo-class aims to improve the user experience by only showing the focus indicator when the user is actually using keyboard navigation or assistive technologies. However, support for this pseudo-class is not consistent across all browsers and versions.

The example shows a button that should only display a visible focus style when it is actively focused via keyboard navigation or assistive technologies.  Older browsers without support for `:focus-visible` will display the focus style at all times, whereas modern browsers will behave as expected.

## Solution

The provided solution uses a JavaScript fallback to detect whether the user is interacting using keyboard or assistive technologies. This ensures a consistent user experience across all browsers, including those lacking `:focus-visible` support.

## How to run:

1. Clone this repository.
2. Open `index.html` in your browser.
3. Test the focus behavior on different browsers (including older ones).
