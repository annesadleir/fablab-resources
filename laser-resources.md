# List of useful resources for laser-cutting

* TOC
{:toc}

## Box designers
* There is a [useful summary blogpost on makerdesignlab](https://makerdesignlab.com/tutorials-tips/online-file-generators-for-laser-cutting/)
* There are also a ton of resources linked at [https://cleversomeday.com/svgtools/](https://cleversomeday.com/svgtools/)

### [Boxes.py](https://www.festi.info/boxes.py/index.html)
Tons of options, very customizable, for a lot of different boxes.  
Also some wildcards like Wine Racks, Royal Game of Ur.  
Backed by a github repo in python which you can fork and play with.  
0.07mm has worked well as a kerf setting in MDF and plywood with the Exeter FabLab machine.

### [MakerCase](https://www.makercase.com/#/)
Basic boxes.  Has a kerf setting.  0.07mm has worked well for MDF and plywood.

### [Gravini](https://www.gravini.cz/en/laser-box-online)
Nice box designer. I think the premium version has even better options

### [cuttingtemplates.com](https://cuttingtemplates.com/)
This has a big range of templates, including some basic ones, like a random blob generator.
It has a lot of pattern-related ones including one that turns images into dots or lines -- this might be good for engraving.
It does not seem to have a kerf adjustment setting for boxes though.

### [TemplateMaker Paper boxes](https://www.templatemaker.nl/en/)
Lots of options for making paper and cardboard boxes

### [Box Designer in German](http://boxdesigner.frag-den-spatz.de/)
Also has paper box designing.  Looks like it has tons of options but they're mostly in German.

### [Box Designer front end](https://boxdesigner.connectionlab.org/)
I have not used this yet. It's basic but you can fork it on github so maybe it would be good for learning how to generate shapes.

### [EasyPackMaker](https://easypackmaker.com)
Seems to be for designing serious packaging boxes.

### [Joinery tool for adding joins to existing svgs](https://clementzheng.github.io/joinery/)
[Instructables tutorial on Joinery here](https://www.instructables.com/Joinery-Joints-for-Laser-Cut-Assemblies/)
This looks like it has a lot of potential.  
It's quite fiddly to get it to work but I did manage to make a pattern for cork. 
The overlapping tabs were hard to get cutting right. They would work better with a stiffer material.

### [Kyub](https://kyub.com/)
Building stuff out of boxes.  
[Youtube intro](https://www.youtube.com/watch?v=7QXbwj9nT9Y)

### [Svg nest Nesting tool](https://svgnest.com/](https://svgnest.com/)
Efficient placement of materials on a sheet.  See also deepnest.io under [desktop tool](#desktop-tools)

## File converters

### [https://cloudconvert.com/](https://cloudconvert.com/)
Seems to be handy for svg --> dxf when Inkscape is losing colours.  
However you will need to resize the image after importing the .dxf into LaserCut.  
You can resize the file by going to the ```Draw(D)``` option.
If you specify the width, then click on the three dots by the side of the height, 
it will calculate the proportional value for you.

Seems to handle .cdr --> svg better than convertio does.

### [https://convertio.co/](https://convertio.co/)
Seems to work better for [dxf --> svg](https://convertio.co/dxf-svg/) than cloudconvert.

Has trouble with cdr --> svg conversion.

## Sources of files

### [DXF downloads](https://www.dxfdownloads.com/faq/)
You upload files to gain points which let you download files.  Interesting!

### [Thingiverse](https://www.thingiverse.com/)
More 3d printing files but lots of laser files too.

### [Instructables](https://www.instructables.com/)
There are lots of [laser-cutting instructables](https://www.instructables.com/workshop/laser-cutting/projects/).
Brilliant for ideas.

### [www.ameede.com](www.ameede.com)
Lots of free files: project files, 3d-illusion lamp files, vector images, also 3D printing files.

### [3axis.co -- free vectors for laser cutting](https://3axis.co/)
Also has .stl files

### Blog with cutting files including boxes and crackers
[https://monicascreativeroom.se/category/cutting-files/bags-and-boxes/](https://monicascreativeroom.se/category/cutting-files/bags-and-boxes/)

### [Kitronik blog posts](https://kitronik.co.uk/blogs/resources/tagged/news)
Also tutorials.

### Free vector images

#### [Craftmanspace](https://www.craftsmanspace.com/)
Not just a jumble of random files, an organized set of collections of motifs, mostly taken from old books and magazines.
Like a web version of a pattern book.

#### [https://freesvg.org/](https://freesvg.org/)

#### [http://www.publicdomainfiles.com/](http://www.publicdomainfiles.com/)

#### [https://publicdomainvectors.org/](https://publicdomainvectors.org/)
Also has a page to generate simple svgs [https://publicdomainvectors.org/svg-generator.php](https://publicdomainvectors.org/svg-generator.php)

#### [https://www.kisscc0.com/](https://www.kisscc0.com/)

#### [https://openclipart.org/](https://openclipart.org/)

### Bought files

#### [Vector Painter](https://vector-painter.com/)
Also has an [Etsy store](https://www.etsy.com/shop/VectorPainter). 
Proper laser-cutting design files with assembly instructions, 
buy direct from a helpful designer, lots of formats and sizes.
Worth the money.
I cut [this Balrog book nook in 4mm](https://vector-painter.com/products/book-nook-2) and it worked beautifully. I customised this [railway booknook](https://vector-painter.com/collections/bestsellers/products/railway-station-book-nook) and I'm really pleased with it.

#### [Cartonus](https://cartonus.com/)
I haven't yet bought anything from this person but their free patterns are excellent 
and they are clearly selling their own work. 

#### [Etsy](https://www.etsy.com/)
There are a ton of sellers with laser-cutting files on Etsy 
but the problem is that so many of them are just reselling files they've found elsewhere.
The files you get might not be fit for purpose (I've had that a few times) and they might not be able to replace bad files.
(Though people are usually quite helpful about refunds.)
Also it's frustrating to be paying money to someone who isn't the original designer.
But some Etsy sellers do genuinely seem to be selling their own designs.
Don't buy without checking if it's on Thingiverse, Craftmanspace, etc first!

#### [https://giwuart.com/](https://giwuart.com/collections/digital-download)
Good stencil svgs that could be cut as holes in wood

## Desktop tools

### [Inkscape](https://inkscape.org/)
Tons of tutorials on YouTube

#### Inkscape Forum [https://inkscape.org/forums/](https://inkscape.org/forums/)

#### Lasercut Box Inkscape Extension
Under Extensions, Render

Allows simple tabbed boxes, with options for dimensions, material thickness, kerf.  
Allows dimples instead of kerf adjustment.  
You specify the number of tabs.

#### CNC Tabbed Box Maker Inkscape Extension
Under Extensions, CNC Tabbed Tools

Has more options than the above, including dividers which can be attached in various ways.
The output needs a little interpretation.

#### [Inkscape extension to make single-stroke fonts](https://inkscape.org/~khemadeva/%E2%98%85inkscape-stroke-font-extensions)

#### [Living hinges extension](https://github.com/buxtronix/living-hinge)

### [FlatFab](http://flatfab.com/)
A tool to make 3D assemblages from flat cuts.
[Tutorial 1 of 1](https://www.youtube.com/watch?v=Bc_LLZ8fijg)

### [DotGrid](https://hundredrabbits.itch.io/dotgrid)
Looks like a good way to make very plain simple shapes, perhaps like simple letters?

### [SolveSpace](https://solvespace.com/index.pl)
Basic CAD thing.  Can check 2D shapes fit together apparently.

### [Deepnest.io](https://deepnest.io)
Removes duplicate lines. Repeatedly tries an algorithm which involves placing largest items first.

### Autodesk extensions
* [DXF for Laser](https://apps.autodesk.com/FUSION/en/Detail/HelpDoc?appId=7634902334100976871&appLang=en&os=Win64)
* [To view dxf files](https://a360.autodesk.com/viewer)

## Suppliers of materials
 
### [Kitronik](https://kitronik.co.uk/)
Specifically supplies the hobbyist and educational market and will make it clear if things are safe in lasers.
Reliable plus super-helpful phone support. 
If something you want is out of stock you can call and they'll give you a rough idea of when they're expecting it

### Places I haven't used
* [https://theacrylicstore.co.uk/](https://theacrylicstore.co.uk/) Seems to have good prices on mirror acrylic.
* [https://www.engraving-supplies.co.uk/](https://www.engraving-supplies.co.uk/)
* [https://lasersuppliesonline.co.uk/](https://lasersuppliesonline.co.uk/)
* [https://laserply.co.uk/](https://laserply.co.uk/)

## Blogs etc

### [reddit.com/r/lasercutting/](https://www.reddit.com/r/lasercutting/)
Wide variety of posts, some very technical, but interesting info.

### [Inkscape forum cutters/plotter](https://inkscape.org/forums/cutplot/)

### [http://cutlings.wasbo.net/](http://cutlings.wasbo.net/)

### [https://www.lvl1.org/](https://www.lvl1.org/)

### [Tutorial on clock numbers and ticks](https://inkscape.org/forums/tutorials/create-evenly-spaced-hour-and-minute-marks-around-clock-circle/)

### [3D-printing articulated animals](https://www.mcgybeer.xyz/)

### [Tinkercad](https://www.tinkercad.com/) -- can help turn an stl into a flat cutting file


