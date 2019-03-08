
## Try it out

Here's how to set up and run the GUI app under windows and to grab some article data to play around with:

1. Grab a copy of steno from the [downloads](downloads) page.

2. Unzip it and run `steno.exe`.

3. Click menu "File"->"New..." to create a new `.db` file (eg enter `test.db` as a filename and click "Save").

4. Click menu option Menu "Tools"->"Slurp articles from server..."
    Pick "UK Govt blogs" in the "Source" selector.

    For date, you can drag out a range of up to 14 days.
    Then click the "OK" button and wait for the download to complete.

    ![Screenshot of slurp dialog](img/slurpdialog.png)

    The UK Govt blogs source has articles going back to around the beginning of March 2018.


5. Once you have some data loaded, the screen should look something like:

    ![Screenshot of steno with data](img/gui_shot1.png)

    The bar above the article list lets you enter full text queries to filter the articles (Some notes on query syntax [here](https://github.com/bcampbell/steno/blob/master/steno/doc/syntax.md))

6. Hold down the CTRL/SHIFT keys to multi-select articles of interest. The tag and delete buttons will affect the currently-selected items.

