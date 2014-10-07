---
layout: post
title: Displaying data from Google Analytics in Sprites
---

# Displaying data from Google Analytics in Sprites

We've just released a nice little addition to our "[Live Data Feeds](http://blog.spritesapp.com/2014/09/13/displaying-live-data-in-your-infographics.html)" feature: you can now display real-time data from Google Analytics in Sprites!

The whole set up process should be really straightforward (especially for those who used to compose custom reports in Google Analytics). There's now a new option called "Google Analytics" which is available in the "Live data" modal dialog (to bring up the modal, select an element and click on a little "Bolt" icon in the context menu):

![Google Analytics - Mappings](/assets/img/posts/ga-mappings.png "Google Analytics - Mappings")

The "View ID" (formerly, "Profile ID") field allows you to specify where to read your Google Analytics data from (if you have a Google Analytics account, you should have at least one view or a profile). Next, you can choose for which date period to select the data (for example, you can tell Sprites to pull the numbers for the last month or for the entire year). The last thing you need to do is you need to tell Sprites which Google Analytics data goes where for the given element by using the "Assign metrics to fields" table (in the example above I'm mapping "Bounce rate" to the percentage of items to highlight in the "Figure" element).

Here's another example. Let's say on a bar chart you'd like to display the number of user sessions by browser. In this case the settings will look a bit different:

![Google Analytics - Any data](/assets/img/posts/ga-anydata.png "Google Analytics - Any data")

So, you simply select the dimension (in this case, "Platform or Device: Browser") and the metric (in this case, "Sessions: Sessions") and Sprites will display a nice-looking bar chart based on this information. Again, all this should be really straightforward for people who used to work with custom reports in Google Analytics.

Searching for specific dimension or metric is also extremely simply: just start typing what you're looking for and Sprites will offer you options based on what's available in Google Analytics:

![Google Analytics - Suggestions](/assets/img/posts/ga-autocomplete.png "Google Analytics - Suggestions")

As usual, like us on [Facebook](https://facebook.com/spritesapp) or follow us on [Twitter](https://twitter.com/spritesapp) to get product updates, hints and tips on creating amazing infographics and online presentations!

Enjoy!

Sprites team.
