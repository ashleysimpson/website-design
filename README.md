# website-design

A repo with my notes from the [Design for Developers](https://frontendmasters.com/courses/design-for-developers/) on Frontend Masters.

## Introduction

The course provided a high level overview of design from a developers perspective and was meant to help developers understand what constitutes good design versus poor design. I have often found that I cannot really add to the discussion of what makes a good design and this was something I wanted to improve upon by taking this course.

I created this repo as an area to list all the resources noted in the course and as a reference for myself later on. It could be that this might be more appropriate as a blog post but not looking to venture into that space yet.

## Basic Design Approach

Here is the list of things you can do when starting to think of a design for a website. The key is to start with the easy to throw away designs, then work your way up from there (leave coding until the last step). You do not want to feel stuck with a design because you put so much effort into the code.

* Start by thinking of a layout ([grid by example](https://gridbyexample.com/) for basic grid layout inspiration)
  * Thumbnails (messy designs on paper)
  * Storyboards (higher fidelity sketches)
  * Low fidelity mockups (simple boxes, layouts with grid, photoshop)
  * High fidelity mockups (interaction designs, images)
* Add filler to the layout (ie. images, lorem ipsum, etc.). You want to start to see how the website could look with content
* Start to think of the color palette (tools like [coolors](https://coolors.co/generate) for inspiration)
* Find some fonts
  * Start with 2 simple fonts and only add more if it makes sense
  * [Free resources](https://fonts.google.com/) to [more expensive](https://www.typography.com/) depending on your needs
* Gather your images
  * Decide on masks, gradients, etc.
* Think about animations (not the easiest to implement but check out [SVG Essentials & Animation](https://frontendmasters.com/courses/svg-essentials-animation/) for inspiration)
* At this point you have probably started coding but the rest is implementation

This all may seem fairly straight forward but by breaking down the design into manageable steps you can quickly make progress. I personally found it much easier to work through the design in this way.

## Books

* Art and Fear
* Making and Breaking the Grid
* Typography for Lawyers
* Stealing your way to original design (an essay)

## Course Notes

Simple list of notes that I took from the course. I would only look through this if you are interested.

* Need to practice more to get better at things, you cannot expect to be a good designer without putting in the effort
* Be mindful that designers go through entire degrees to acquire their skills so simply following an online course will not make you a designer (ie. try not to upset the designers you work with)
* Symmetry in balance, but breaking the symmetry provides a call to action, there is a subtle balance to symmetry and asymmetry
* Edo period prints are really interesting for design inspiration
* Asymmetry is common in nature, this is hard to use in a design but is generally more interesting if you can make use of it
* Rule of thirds, break down an image into 9 equal parts, and position the attention to one of those thirds
* Triadic compositions, triangles to keep the eye from leaving the canvas (examples in many art pieces)
* Circles draw you eye more than other shape, they are therefore useful tools in a designers toolkit
* Saccade, eye movement that scans to create a spatial map
* Make sure of photoshop, sketch, illustrator to help with designs
* Progressive enhancement with @supports in css, helps with designs that may not work for all your potential users
* Transforming text can add interesting elements to your design
* Checkout grid by example and grab some examples to start with when looking for inspiration
* Use calc in css to take into account margins in designs
* Emmet will forever be a great tool if you write css
* Grid is great, and as subgrid is better supported you should probably make use of that oo
* Color mixing and color mode (RGB for screen, and CMYB for printing)
* Cyan, Magenta, and Yellow (subtractive colour mixing) -> Combine to black (or deep brown), need black to actually make black
* Red, Green, and Blue (additive colour mixing) -> Combine to white
* Colors
  * Monochromatic (variations of shades of a single colour)
  * Complementary (opposite ends of the color wheel)
  * Analogous (beside each other on the colour wheel)
  * Triadic (complementary in three ways on the colour wheel)
* Colour is only a colour when it is next to another color (you can see dramatic differences just with shade variance)
* Contrast is important for accessibility
* Monotone, duotone, these can add interesting elements to your designs
* Shadows are the opposite color to the light cast on the object
* Things that are closer have higher contrasts, and things further have lower contrasts, check different photographs to understand how distance affects contrast and how you can use that in your designs
* RGB(A), 0-255 for the first 3 args, 0-1 for the last arg
* HEX, easy to copy paste, #RRGGBB
* HSL(A), hue (color wheel), saturation (0-100%), lightness (0-1), easiest to not mess up
* Animated gradients aren't the best, use animated transparent masks
* Transforms are cheaper than most other things that cause repaints
* Typography balances are important for conveying meaning
* Serif, sans serif, slab serif, script font, display font (can be both), novelty fonts, all different types of fonts to be aware of
* Basic font pairing: one display and one sans-serif, one serif and ones sans-Serif
* Do not use more fonts than three, try for two
* Don't match in font pairing (google fonts helps here with their recommendations)
* Line length, 45-90 characters is very good line limit to aim for with line length
* Typographic color: Blur your eyes and look for an even distribution, these would be good for body text
* Text lockup as a tool
* Proportional and monospaced fonts
* Kerning vs no Kerning (letter-spacing)
* Leading (line-height), to set the difference between lines (old printing method)
* The safe setting: letter-spacing: 0.03em, line-height: 1.4, vertical-align: baseline
* Widows are a word that is left alone after a paragraph end
* Orphans are lines that appear by themselves on the next column
* Ligatures, connect up characters to make things look less clumsy
* Text cannot be centered on a page, it is a phenomena called falling down and you will notice this in any book
* Check font performance if you are losing performance on a page
* Lots of ipsums if you want your text to be more interesting (Harry Potter ipsum)
* Consider popularity with fonts because you can save on the download cost if you use a font that is likely to be cached already
* Check into variable fonts if you want to have some difference
* Get inspiration, wait and then create from memory, this is a way to avoid simply copying someone’s design
* Master copies, these allow you to learn how to paint or how to recreate something
* ui kits: shutterstock for some starting point in designs, you can adjust these however you want
* Take inspiration, play with it, change it and make it your own
* Images are a huge consideration for website design
* Raster (jpeg) vs Vector (svg)
* Lossy jpeg (images that are compressed too much)
* Image export tips, double the size, lower compression
* TinyJPG/TinyPNG (image compression)
* Webpack plugins, gatsby plugins, there are many things out there to help with images
* SVGOMG great for optimizing SVG
* inline svg because it makes it easier to work with
* Sprite sheets save multiple requests to the server
* Loaders help with perceived load times (custom loaders are best, they hook people for longer)
* Anxiety makes peoples wait times feel longer (doctors office example, they tend to bring you into the room and make you wait there instead)
* Motion design language, your own languages add character to your website
* Types of prototypes: thumbnails (messy designs for yourself), storyboards (higher fidelity), low-fi, hi-fi 
