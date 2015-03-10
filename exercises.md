# Exercises

The exercises in this module are about colour, layout, and manipulating graphics - but not necessarily in that order. All students must complete the 'Sprucing up a PDF in Inkscape' exercise, as well as the 'Typography', 'Colour', and 'Layout' exercises. Everything after that is optional (including the option to not do them).

[Sprucing up a PDF in Inkscape](#sprucing-up-a-pdf-in-inkscape) | [Typography](#typography) | [Colour](#colour) | [Layout](#layout) | [More](#more)

### By the way: Raster v Vector
The first thing to know is that graphic images come in two distince flavours - raster, and vector.

Raster images are composed of pixels, such that if you zoom into them, they become a pointilist blur (if you remember _Ferris Beuller's Day Off_, there's a scene where Cameron stares and stares at a painting, falling into its individual points of colour...). Vector images on the other hand are described by mathematical functions, of lines and arcs and areas. No matter how deep you delve into these kinds of images, the image is always sharp - because the zoom is just another function of the mathematics describing the image.

Rasters: blocks of colours

Vectors: descriptions of points and arcs

## Sprucing up a pdf in Inkscape

Some of the tools that we used in Module 4 give visual output as raster images, others as vectors. Sometimes, we would like to tweak these outputs to make them more visually appealling, or clearer, or more useful. A program like MS Paint is only useful for dealing with raster images (and then, only in certain kinds of cases). We need a program that can deal with both, and also, lets us edit the image by treating each edit we do as a mostly-transparent layer on top of the image. That way, we can add, rearrange, hide or reveal, our edits to create a composite image. A free program that is immensely useful in this regard is [Inkscape](https://inkscape.org/en/). Inkscape is also quite useful in that we can open a pdf file in it, break the visual elements of the pdf into individual layers, and then rearrange/touch up/fix them up to make them more esthetically appealing.

In this first exercise, we will take the plot we generated in Module 4's exercise on topic modeling in R where we made a bar chart showing the number of articles by year. In R we exported that plot as a PDF. In Inkscape, we can import that pdf and 'explode' it so that we can manipulate its parts individually. We are going to take the simple bar chart and make it more legible, more visually appealing, for incorporation on a webpage.

1. Download and install [Inkscape](https://inkscape.org/en/) *nb Mac* the installation instructions are a bit more complicated for Mac. Pay attention and follow closely!
2. Download the pdf we generated in R [publication-year.pdf](/publication-year.pdf) 
3. Open that pdf. It's a pretty plain graphic. Right away there are at least two things we could do to make it more visually appealling. We could change the orientation of the characters in the y-axis to make them more legible. We can highlight bars of interest. And we could apply a colour scheme more generally that would make our graphic legible to folks with colour-blindness (see the 'going further' section at bottom).
4. Start Inkscape. Click File >> Import >> and then navigate to where you save the 'publication-year.pdf'. Click Ok when you've got it selected. In the next pop-up, just accept the default settings and click 'ok'. Your Inkscape window should now look like this:<br>![inkscape1](/inkscape1.png)
5. The pdf is now a layer in the new image you are creating in Inkscape. You can save this drawing, _with its information about the layers and what is in each one_ by clicking File >> Save As. ([here's my version](/exercise1drawing.svg)). 'SVG' stands for 'scalable vector graphic'.
6. Do you see the bounding box around the plot? If you grab any of those handles (the double-arrow things), you can make it bigger or smaller on your sheet. We can't edit any of the other elements yet - we can't change the colour of the bars, or the fonts of the text. We have to tell Inkscape to 'explode' these elements into their own 'objects'. In the menu bar at top, got to Object >> Ungroup. There are now a series of overlapping bounding boxes around each object.
7. Zoom in (by pressing the + sign on your keyboard) so that you're looking at the numbers of the y-axis. We're going to rotate these by 90 degrees to make them more legible. Select the arrow icon from the toolbar on the left side of the screen.
8. Click on the '50'. You'll get a bounding box around it. Click Object >> Rotate 90 CW. The 50 is now rotated! Do the same for the other numbers. Save. (If you double-click on the number, you might trigger the 'text edit' function. If you do that, no problem - you can change the font, change the number... although if you did that, it'd be a bit dishonest, right? Click on the arrow pointer icon in the toolbar again to get out of the text-editing function).
9. Let's imagine, for whatever reason, that you wanted to change one of the bars to a different colour, to highlight its importance to your argument. With the arrow icon, click on one of the bars so that you get the bounding box around it. Then, click on one of the colours from the palette at the bottom. Boom! You've got a newly colourized bar. Save. 
10. To export your image so that you can use it in a website or paper, click Edit >> Select All in All Layers. Every element of your image will now have a bounding box around it.
11. Go to File >> Export Bitmap. Never mind the options in the popup; just hit 'Export'. Inkscape will automatically assign your drawing a name with .png; here's [mine](/g3161.png). Remember, if you want to edit this image again later, hit the 'save' button to save it as an svg. The svg will preserve all your layer information, while the png file is the visual representation (the png is in fact a raster graphic). Most browsers can handle svg files, so you could use that in your website; programs like Word seem to be able to handle raster graphics better than they do svg. You might want to experiment. In any event, every journal has different requirements for image formats. You would export your image to whatever those specifications are.

### Going further

In this [tutorial, you will learn how to load a custom colour palette](http://infoheap.com/create-and-use-color-palettes-in-inkscape/). Why might you want to do that? You should be designing your work so that it is as universally accessible as possible. Many folks are colour-blind. Use [Color-brewer](http://colorbrewer2.org/) to generate a colour-blind safe palette. Then look for the 'GIMP and Inkscape - GIMP color palette for this scheme.' Click on that link, and you'll get a text file with the scheme you generated. Use that scheme to alter the colours on your plot.

-----

## Typography

Typographic plays an important role in visual communication. It can do everything from reduce eyestrain (do a search for 'easiest fonts to read on screen') to communicate power and authority. Is it any wonder that strong bold capitals come to be known as 'Roman'? In this exercise, 
+ I want you to read and understand the section on [font choices from the Owl at Purdue](https://owl.english.purdue.edu/owl/resource/705/01/). 
+ Then, play some rounds of [Typeconnection](http://www.typeconnection.com/index.php). Pay attention to why - or why not - various pairings work. 
+ Then, I want to consider the document you will be preparing for me that accounts for your learning in this course - the document where you choose your best exercises from the modules and explain how your approach to history, data, the digital, etc, has changed over this course. What typographic pair would work best for you? 
+ Finally, you'll make a webpage that uses those fonts and explains why they work.

The first part of this exercise then is to find a pair and to understand why they work best for you - go read the materials above, and once you're done with the Typeconnection site, go to [Google Fonts](https://www.google.com/fonts) and search for a pair that are *suitable for your purpose*. When you find a font you like, click the 'add to collection' button. Then, at the bottom of the screen, you'll see a link for 'use'. Click on this - google will ask you if you want to use any of the variants of the font. Tick off accordingly. Then, do you see the embed code that google provides, and the code to integrate the font into your CSS (stylesheet)? Leave this window open - we're going to use it in a moment.

1. In your repository, click the button beside 'branch'. In the search box that opens, type in ```gh-pages```. This will create a version of your repository that can be served as a website.
2. You're now in the gh-pages branch. Click on the + sign beside the repository name. This will create a new file in your gh-branch of your repository. Call it ```myfontchoice.html``` <- the .html is important to specify; otherwise your browser will not know how to render your page.
3. You now need to put some html in there. I've written a simple webpage that will use two fonts from Google Fonts, and then applies the font to my text depending on whether or not it is a header, which you specify like this: ```<h1> this is a header in between header tags </h1>``` or a paragraph, which you specify like this: ```<p>blah blah blah a paragraph of text blah blah blah</p>```. My webpage is [here](/fontexample.html); right-click the link and open in a new tab. Copy the html into your new html document. Commit your changes (ie, save!).
4. Let's see what we've got. To see the website version of your gh-pages branch, you go to ```<yourusername>.github.io/<reponame>/myfontchoice.html``` <- ie, the final part of the url is the name of the document in your repo. Do that now. You should see a simple webpage, with two very distinctive fonts.
5. Now: let's slide your font choices into the html. Go to your html page in your gh-pages repo (ie, not the ```github.io``` version, but the ```github.com/<yourusername>/<repo>/myfontchoice.html``` version. Hit the edit button. Look closely at line 6. Do you see my two fonts? Do you see the pipe character between them? That tells google you want *both* fonts. Go look at the google fonts page again to grab the exact name for your fonts (ie, uppercase letters make a difference!) and paste them into line 5 appropriately.
7. Lines 8 and 14 specify which font to use for headers, and which font to use for body text. Change appropriately. 
8. Change my silly text for a paragraph that explains what the fonts are, and why they work for this purpose. Commit your changes.
9. Go to the ```github.io``` version of your repository (if you forget the address, you can find it under the 'settings' button on your normal repository page when you're in the gh-pages branch). Reload the page a couple of times to clear the older version you've already looked at and to replace it with your version. Ta da! Not only have you thought carefully about typography and fonts, you've also learned how to serve a webpage from a Github repository.

*Hint* You could use this as the basics of your submission for assessment, for your exercises. Build a webpage, link to your evidence, embed your images... For basic html [here's a really good guide to keep around](http://www.w3schools.com/html/default.asp). 

-----

## Colour


-----

## Layout


-----
_____
## More

More resources, tutorials, and things to explore.


## Poster Design


-----

## Infographics
[The Difference between Infographics and Visualizations](https://eagereyes.org/blog/2010/the-difference-between-infographics-and-visualization)
