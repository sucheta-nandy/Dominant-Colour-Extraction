# Dominant-Colour-Extraction

How do you find the dominant color in an image?
It turns out a good strategy of finding dominant color involves k-means. 
If we choose the right value of k then the centroid of the largest cluster will be a pretty good representation of the image’s dominant color.

## Application:
One possible application of dominant color is for use in sorting images.
Another possible application of this dominant color extraction is in data viz. 
Let’s say we want to generate line plots for our sample of apps. We could use a default color palette, but it might add to our users’ experience if our line colors matched the colors of the app icons they’re familiar with. 
Using dominant color extraction we can assign appropriate colors for use in our plot automatically.
