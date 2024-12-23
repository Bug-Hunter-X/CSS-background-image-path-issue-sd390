# CSS Background Image Path Issue

This repository demonstrates a common issue encountered when using background images in CSS: the inability to load an image when its path is incorrect. The `bug.css` file contains the problematic code, while `bugSolution.css` provides the corrected solution.

## Bug
The image path in the CSS is relative, leading to the image not being found if the CSS and image files are not in the same directory.

## Solution
The solution involves using an absolute or correctly relative path to the image, ensuring the browser can locate and display it correctly.  Using absolute paths is often preferred for maintainability and avoiding path resolution issues across different environments.