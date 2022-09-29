# Lazy Load Images
The script lazy load images without using any external javascript library. It is done with the help of Intersection Observer API. The Intersection Observer API lets code register a callback function that is executed whenever an element they wish to monitor enters or exits another element (or the viewport), or when the amount by which the two intersect changes by a requested amount.

## Usage
1. Change src attribute of image to data-src
2. Add class="lazy" to image element

## How to Test
1. Press Ctrl+Shift+I on the web page
2. Go to Network tab
3. Select Img

Image will only be displayed just before we are about to enter to the image section.
 
