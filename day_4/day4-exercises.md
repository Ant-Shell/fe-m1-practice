# Day 4 Exercises
## Images - HTML
1. In an image element, why is the alt attribute important?
- The alt attribute is important because it gives a description of an image in case it does not render properly, the link is broken, etc.

2. What determines if an image element is inline or block?
- If the image element is inside a block level element, any text or other inline elements will flow around the image.
- If the image is is followed by a block level element, then the block level element will sit on a new line after the image

3. What are the benefits of jpg or png image file formats?
- Jpeg - used for photographs with many different colors
- Png - used for illustrations or logos with few colors or large areas of the same color

## Images - CSS
1. What is the benefit of specifying the height and width of images in CSS compared to specifying in the HTML?
- Specifying image sizes helps pages load more smoothly because the CSS will often load before the images - telling the browser the space to leave for images allows it to render the rest of the page without having to wait for the image to download


2. What is an image sprite, and why is it useful?
- An image sprite is used for several parts of an interface (logo, buttons). This is useful because the web browser only needs to request one image rather than many images, which results in faster web page loads
