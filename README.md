Assignment: CSS Hell
====================

You will skin 3 project gutenberg stories with custom CSS.

You will skin 2 versions of a possible professional homepage for your
self with 2 versions of CSS.

Read requirements.org

Read this comic http://theoatmeal.com/comics/design_hell

git clone https://github.com/abramhindle/CMPUT404-assignment-css-hell.git

License/Copyright
=================

Textual content is copyright Raghav Chandak (C) 2013 under the CC-BY-SA
4.0 unported license. Attribution should be a hyperlink to the
repository and (C) 2013 Raghav Chandak visibile in the text.

Code is licensed under the Apache 2.0 license.

Changes made to gutenberg html files
====================================

These changes are made in the style.css file:

First, I made the background color of the entire document to a light-yellow shade and set the font family of the document to use serif. The code to do so is,
*{
    background-color: #FFFFE0;
    font-family: serif;
}

Then, I changed the colour of all paragraphs to use a navy blue color, and increased the font size of the paragraphs. Code to do so is:
p{
    color: #000080;
    font-size: 1.2rem;
}

I then changed the color of all headers to green, by:
h1, h2, h3, h4, h5, h6{
    color: green;
}

For the images, I changed the border-radius of all images to give them rounded corners, by:
img{
    border-radius: 5rem;
}
