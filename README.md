# Safari Background Image Issue

This repository demonstrates a CSS bug where the `background-image` property fails to render an image in Safari, while working correctly in other browsers like Chrome and Firefox.

The bug is described in `bug.css`, and the solution is in `bugSolution.css`.

## Bug Report

The `background-image` property is set using a relative path to an image file.  The image file is confirmed to exist and the path is correct. However, in Safari, the background remains blank.

## Solution

The solution involves making sure that the image is in the correct path relative to the CSS file. Add the correct `base-url` in the header of the html file. Check for any caching issues and try to clean browser cache. 