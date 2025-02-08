# Unexpected Behavior with calc() in CSS @media Query

This repository demonstrates an uncommon CSS error involving the use of the `calc()` function within a CSS `@media` query.  Some browsers do not correctly interpret `calc()` when used to define the breakpoint in a media query.  This can lead to unexpected behavior where the styles defined within the media query are either always or never applied.

The `bug.css` file contains the erroneous code, while `bugSolution.css` shows the corrected approach.

## Solution

The solution involves calculating the breakpoint value beforehand in JavaScript or another suitable language and then using this calculated value in the CSS `@media` query.  See `bugSolution.css` for details.