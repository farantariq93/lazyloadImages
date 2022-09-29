# Lazy Load Images
The script lazy load images without using any external javascript library. It is done with the help of Intersection Observer API. The Intersection Observer API lets code register a callback function that is executed whenever an element they wish to monitor enters or exits another element (or the viewport), or when the amount by which the two intersect changes by a requested amount.

## Usage
1. Change src attribute of image to data-src
2. Add class="lazy" to image element
Example: <img class="lazy" data-src="https://via.placeholder.com/300/000.png/fff/O?text=I+Will+Lazy+Load">
 
