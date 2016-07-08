URL Rotator
=============

Great for QA/QE of your website's query string-enabled values.

0. Download the Bookmark Generator index.html file from this repo.
0. Open the index.html file in your local browser.
0. Modify and add various strings that you may want to change in the URL in the Strings box.
0. Click the "Generate bookmarklet" button at the bottom of the page. A new link will be displayed.
0. Click and drag that link to your bookmarks bar.

Now when you are on a page, clicking the bookmarklet will cause the browser to:

0. Look through the current URL of the window for the first string you entered.
0. If it finds that string, the URL will be changed to replace that string with the next string in the list. (If it is the last string, the first string will be put into the URL.)
0. The page will reload using the new URL.
0. If none of the strings are found, no change will be made.


Installation
-----------

* Download the index.html file to your computer.

Usage
-----

* Open the index.html file in your browser on your computer.


Thank you
------------

Thank you to https://github.com/rik/server-switch for a base of code to work from, implementing a tool I've recreated 4 times in 10 years. Maybe this repo will keep me from re-inventing it.
