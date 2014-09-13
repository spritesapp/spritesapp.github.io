---
layout: post
title: Displaying live data in your infographics
---

# Displaying live data in your infographics

We're excited to announce a new major feature in [Sprites](https://spritesapp.com) - an ability to display live data in your infographics. This is achieved by connecting selected elements (such as charts, tables, images, etc.) to third-party data sources. 

Connecting your Sprites elements to live data feeds makes it possible to display various real-time data such as competition results, voting results, live feeds from the various events and so on. This, in turn, will make your infographics much more engaging and up-to-date with latest information on specific topics.

Here's how it works. When you hover over an element in Sprites editor, you may notice that there's a new context menu item which now appears (it has a "lightning" icon):

![Connect to live data feed](/assets/img/posts/realtime-contextmenu.png "Connect to live data feed")

Once clicked, a modal window appears allowing you to configure live data feed for the given element:

![Connect to live data feed - dialog](/assets/img/posts/realtime-dialog.png "Connect to live data feed - dialog")

Every Sprites element works with its own data format. For example, Fact element, among other things, accepts (or "understands") three properties: "quantity", "measure" and "description" that can be set by using the respective form fields when you're composing your infographic inside the editor.

When using live data feeds, Sprites expects the data in a same format to be returned from the feed. For example, when you connect your Fact element to Google Sheets, you will need to define three columns in your spreadsheet: "quantity", "measure" and "description". This way Sprites can easily pick up cell values for each of the columns and display them to the user.

Currently, we support connecting elements to Google Sheets as well as to a custom URL (which must return a valid [JSON](http://en.wikipedia.org/wiki/JSON) objects). Furthermore, out of the current twelve Sprites elements ten support connecting live data. The only two elements that don't support live data feeds are Line and Widget.

We've put together a set of spreadsheets, one for each element, to illustrate how your live feed should look like. The spreadsheets are available here: [Sprites - Live data feeds](https://drive.google.com/open?id=0B19ekNcwy_ciME5Tcm1JdVJXMXc&authuser=0). If you'd like to test elements yourself, feel free to use the links to the respective sample spreadsheets in your infographics (open the spreadsheet in your browser, copy the URL from the browser address bar and use that URL when configuring your element). 

There's also a quite comprehensive documentation on live data format available on our GitHub Wiki: [Live data format - Sprites](https://github.com/spritesapp/sprites-sdk/wiki/Live-data-format).

Try it out and let us know what you think! You can connect with us on [Twitter](https://twitter.com/spritesapp), [Facebook](https://www.facebook.com/spritesapp) or by sending us a message via our [contact form](https://spritesapp.com/contact).

Enjoy!

Sprites team.
