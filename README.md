# Website Performance Optimization Project

Optimization of an inefficient web application's JavaScript, CSS and assets delivery, ensuring it runs at 60fps and achieves a PageSpeed score of at least 90.
## Installation
Either clone the repository using GIT, or use the download ZIP link on the right hand side of the screen. Open the directory and double click the index.html file.
## Changes
-Scripts were moved to the bottom of the page but inside the body tag.
-Stopped forced synchronous layout.
-Reordered loop to read layout properties first then batch styled changes.
-Reduced the number of iterations for pizza images.