---
layout: post
title: Importing data from Microsoft Excel and Google Spreadsheets
---

# Importing data from Microsoft Excel and Google Spreadsheets

Today we're rolling out a new cool feature - an ability to import data for your charts and tables from various third parties such as Microsoft Excel and Google Spreadsheets. Let's take a look!

When you're opening a data editor (by clicking under "Data to display" in element properties pane) for "Chart" and "Table" elements, you can see that there's now a new little button called "Import data" at the bottom right corner of the modal window:

![Import data](/assets/img/posts/import-button.png "Import data")

When clicked, a new dialog appears allowing you to choose where to import data from. We currently support three options:

1. Microsoft Excel (.xlsx files) and [CSV](http://en.wikipedia.org/wiki/Comma-separated_values).
2. Google Sheets (formely Google Spreadsheets).
3. Custom URL.

Let's look at each option in more detail.

The "Microsoft Excel" option allows you to upload the XLSX or CSV file from you computer. Once uploaded, you'll see the following:

![Import from Excel](/assets/img/posts/import-excel.png "Import from Excel")

The "Has column names" option allows you to specify whether the first row in the uploaded file contains column headers. The "Has row labels" option indicates whether the first cell in every row contains a text representing a label for a given row. When the file is Microsoft Excel file (and not the CSV file), you can choose from which worksheet to import data (in case there're multiple worksheets exist).

The "Google Sheets" option allows you to import data from an arbitrary Google Spreadsheets document. All you need to do is to specify the URL of the document in the text box:

![Import from Google Spreadsheets](/assets/img/posts/import-google.png "Import from Google Spreadsheets")

One thing to remember here: the target Google Spreadsheets document must be published ("File -> Publish to the Web..." option in Google Drive).

The last option, "Custom URL", makes it possible to take any URL and load data from it as long as on the other end there's a [JSON](http://en.wikipedia.org/wiki/JSON) document with the format that can be understood by Sprites:

![Import from URL](/assets/img/posts/import-url.png "Import from URL")

That's all, folks. Enjoy!

Sprites team.

