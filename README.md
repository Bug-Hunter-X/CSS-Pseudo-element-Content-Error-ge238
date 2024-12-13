# CSS Pseudo-element Content Error

This repository demonstrates a common yet often overlooked error in CSS: providing an invalid value for the `content` property within a `::before` or `::after` pseudo-element.  This can be due to an undefined variable or a broken URL that is referenced.

The `bug.css` file contains the erroneous CSS, while `bugSolution.css` provides the correction.

## Bug:
Incorrect use of the `content` property of `::before` or `::after` pseudo-elements leading to rendering failure.   Specifically, attempting to use an undefined variable or an inaccessible URL within the `content` property can break the rendering.

## Solution:
Ensure that variables used within the `content` property are properly defined and that URLs are accessible and correctly formatted.