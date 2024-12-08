# Tailwind CSS Gradient Rendering Issue

This repository demonstrates a subtle bug in Tailwind CSS where a gradient might not render correctly, appearing as a solid color instead. This is not a syntax error but a visual issue that can be hard to track down.

## Bug Description

The issue occurs when using the `bg-gradient-to-r`, `from`, and `to` classes to create a linear gradient. In certain cases, particularly when the `from` and `to` colors are very similar or if there's a browser rendering quirk, the gradient might not be applied, leaving only a single solid color.

## Solution

The solution involves ensuring sufficient color contrast between the `from` and `to` colors and using developer tools to investigate browser-specific rendering issues.  Consider using more distinct colors, or using a different gradient approach if the issue persists.