---
layout: post
title: Pan and zoom with maps
---

# Pan and zoom with maps

Another little improvement that we've just shipped is an ability to pan and zoom the area of your "Map" element. This functionality allows you to focus on specific areas of a map (for example, central Europe) rather than choosing a bigger scale in a hope to achieve the same effect (the latter is still supported, by the way so these two features can be used in conjunction).

Here's how the element properties pane has changed for the "Map" element (notice the new "Zoom level and offset from center" property):

![Map pan and zoom](/assets/img/posts/map-pan-and-zoom.png "Map pan and zoom")

The first three buttons allow you to specify zoom level for your map (default is "1x" meaning no zoom). The other two input fields ("Auto" and "33%" on the screenshot above) allow you to specify where is the center of your map should be when zoom is applied. This is specified as a percentage offset fom the original map center. For example, the values "-25%" and "45%" mean that the map center is going to be 25% of the map width to the right from the original map center as well as 45% down from it.

Here's how we can pan and zoom the map of United States to bring focus on Texas:

![Map pan and zoom result](/assets/img/posts/map-pan-and-zoom-result.png "Map pan and zoom result")

We hope you'll find the new functionality useful. If you have any questions or need help, feel free to reach out to use on [Twitter](https://twitter.com/spritesapp) or drop us [an email](https://spritesapp.com/contact) and we will be in touch shortly.

Enjoy!

Sprites team.
