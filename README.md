# Tailwind CSS Configuration Error: Undefined Color

This repository demonstrates a common error in Tailwind CSS configuration files: using undefined colors.  The `tailwind.config.js` file attempts to use the color `theme-color-primary`, but it's not defined in the `theme` section.

The solution (`tailwind.config.fixed.js`) demonstrates the correct way to define custom colors.

## How to reproduce the bug

1.  Clone this repository.
2.  Try to compile your Tailwind CSS using your preferred method (e.g., `npx tailwindcss -i input.css -o output.css --watch`).
3.  Observe the error related to the undefined color.

## How to fix the bug

Refer to the `tailwind.config.fixed.js` file for the solution, which involves correctly defining the custom color in the `theme.extend.colors` object.