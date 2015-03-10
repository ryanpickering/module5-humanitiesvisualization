# Exercises

The exercises in this module are about colour, layout, and manipulating graphics. The first thing to know is that graphic images come in two distince flavours - raster, and vector.

Raster images are composed of pixels, such that if you zoom into them, they become a pointilist blur (if you remember _Ferris Beuller's Day Off_, there's a scene where Cameron stares and stares at a painting, falling into its individual points of colour...). Vector images on the other hand are described by mathematical functions, of lines and arcs and areas. No matter how deep you delve into these kinds of images, the image is always sharp - because the zoom is just another function of the mathematics describing the image.

Rasters: blocks of colours
Vectors: descriptions of points and arcs

## Sprucing up a pdf in Inkscape

Some of the tools that we used in Module 4 give visual output as raster images, others as vectors. Sometimes, we would like to tweak these outputs to make them more visually appealling, or clearer, or more useful. A program like MS Paint is only useful for dealing with raster images (and then, only in certain kinds of cases). We need a program that can deal with both, and also, lets us edit the image by treating each edit we do as a mostly-transparent layer on top of the image. That way, we can add, rearrange, hide or reveal, our edits to create a composite image. A free program that is immensely useful in this regard is [Inkscape](https://inkscape.org/en/). Inkscape is also quite useful in that we can open a pdf file in it, break the visual elements of the pdf into individual layers, and then rearrange/touch up/fix them up to make them more esthetically appealing.

In this first exercise, we will take the plot we generated in Module 4's exercise on topic modeling in R where we made a bar chart showing the number of articles by year. In R we exported that plot as a PDF. In Inkscape, we can import that pdf and 'explode' it so that we can manipulate its parts individually. We are going to take the simple bar chart and make it more legible, more visually appealing, for incorporation on a webpage.

1. Download and install [Inkscape](https://inkscape.org/en/) *nb Mac* the installation instructions are a bit more complicated for Mac. Pay attention and follow closely!
2. Download the pdf we generated in R [publication-year.pdf](/publication-year.pdf) 
3. Open that pdf. It's a pretty plain graphic. Right away there are at least two things we could do to make it more visually appealling. We could change the orientation of the characters in the y-axis to make them more legible. And we could apply a colour scheme that would make our graphic legible to folks with colour-blindness.
4. Start Inkscape. Click File >> Import >> and then navigate to where you save the 'publication-year.pdf'. Click Ok when you've got it selected. In the next pop-up, just accept the default settings and click 'ok'. Your Inkscape window should now look like this:<br>![inkscape1](/inkscape1.png)
5. 
