---
layout: post
title:  Playgrounds and maps
date:   2016-05-31 20:20:20 +0800
excerpt: "3D Modelling with Blender, texturing within GIMP, implemented into UDK."
tag: [Game Dev]
comments: true
feature: http://i.imgur.com/goat4jn.jpg
---
<p>Throwback blog from the old days.</p>

<p>Just some more asset creation going on here. Firstly I did a little update to the trees from before, realised there were some faces in the wrong direction, so I just flipped the normals on them, after removing some unneeded extra polys, and also did a re-texturing, to make it look a bit better!</p>
![alt text](http://i.imgur.com/0qlyyUQ.jpg "Tree")

<p>The tree on the left was the result, it gives a very different appearance, but it was super shiny, which while great for plastic (or I guess if it was raining) isn't so good for a tree, so a little tweaking, and we got a much more natural appearance for it. </p>
![alt text](http://i.imgur.com/g2PwIF2.jpg "Better Tree")

<p>That tweaking aside, the main body of work now was the next asset, I decided to go with a monkey bars play area thingy.</p>

![alt text](http://i.imgur.com/LMnGHad.jpg "DrawingSkillz")

<p>Some AMAZING concept artwork there, but enough to get the idea of how I want it to look.</p>

<p>With that, blender was opened, and construction began.</p>

![alt text](http://i.imgur.com/S7e2bAu.jpg "Unsafe")

<p>The monkey bars themselves were the first bit to go up, just a bunch of cylinders, nothing too tricky.</p>

![alt text](http://i.imgur.com/Uk5MWMQ.jpg "Coming Along")

<p>The main body of the structure, just thrown together from cubes.</p>

![alt text](http://i.imgur.com/ER6gyeY.jpg "Windowssss")

<p>Used more cubes and boolean difference modifier to make the windows in the crawlspace.</p>

![alt text](http://i.imgur.com/qyqBeou.jpg "Looks safe")

<p>Same modifier again to clear out the foundation legs, and the model itself was done. Very easy work.</p>

<p>Next up came the UV mapping.</p>

![alt text](http://i.imgur.com/XWcAVZr.jpg "UV Maps")

<p>Since the sides, and front/back are essentially the same from either direction, I selected the faces I wanted and mapped them from the left/right, front/back viewports. And lined them up on top of eachother as you can see on the right side of the window, the areas are as follows. Bottom left is the view from the front/back, next to that is the view from the left/right. Above that is the sections that is the up/down faces of the floors that are blue in the concept artwork. Left of that is the floors that are red in the concept artwork.</p>

<p>The lines towards the right are the different monkey bar pole layouts.</p>

![alt text](http://i.imgur.com/UaNvxuK.jpg "Paint Paint")

<p>This is how the texturing came along, another very simple job. Grey for the metal poles, blue on the roof and the inside floors and roof, red for everything else. (Notice the difference to the concept artwork, as I didn't like how it turned out when rendered)</p>

![alt text](http://i.imgur.com/hERWfvx.jpg "It's all done in GIMP")

<p>This was the normal map for the same thing. Wood plank textures on all the wooden parts, just a light bumpy texture for the metal.</p>
<p>And that was essentially it done.</p>
<p>Imported into UDK, fiddled around a little to get it looking just right, and here we are!</p>
![alt text](http://i.imgur.com/WEZuJvS.jpg "What's with the robot?")

![alt text](http://i.imgur.com/7YAuveF.jpg "Big Grey Box")

![alt text](http://i.imgur.com/l3GAXTX.jpg "Aerial")

<p>Not too bad.</p>
<p>Thanks for reading!</p>
