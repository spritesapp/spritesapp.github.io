---
layout: post
title: New charting options
---

# New charting options

Many people were not that happy with the charting capabilities that Sprites was offering. I'm happy to announce that we've substantially improved our charts and I can't wait to share the details with you.

## See it in action

The best way to introduce a new feature is to show an example. Take a look at the following demonstration: [New charts](https://spritesapp.com/view/embed/4673). 

## Switching gears

With this rather big change what we did first is we replaced [Chart.js](http://www.chartjs.org/) (a third-party charting library that we used) with [Google Visualizations](https://developers.google.com/chart/interactive/docs/reference). The main reason for this switch was that Chart.js comes with a very few built-in chart types and also its customization capabilities are quite limited. We didn't feel like it was a good idea to invest time into improving a library while there're plenty of alternatives out there (and Google Visualizations is one of the best ones).

Please note that all existing infographics won't break and will still use Chart.js for rendering all the charts. At the same time all the new infographics will automatically switch to a new charting engine.

## New features

There're several new chart types that are now available to you. Here's the full list:

1. Line chart (was available before)
2. Area chart (new, separated from Line chart)
3. Bar chart (was available before)
4. Pie/Donut chart (were available before)
5. Bubble chart (new)
6. Tree Map chart (new)

![Chart types](/assets/img/posts/chart-types.png "Chart types")

Also, pretty much all the charts are now showing the legend and the X/Y axis with intermediate points (although, it's possible to show only the chart area) so it should be much easier for the viewers of your infographic to interpret and understand the data. As for the tooltips (small "bubbles" which are typically used to describe a given area/point on a chart), they can easily be added via "Callout" element.

![Callouts and legend](/assets/img/posts/chart-line-callout.png "Callouts and legend")

We hope you will like the new charts. If you have any comments/questions/suggestions, feel free to reach out to us at [Twitter](https://twitter.com/spritesapp), [Facebook](https://www.facebook.com/spritesapp) or via our [contact form](https://spritesapp.com/contact).

Cheers!

Sprites team.

