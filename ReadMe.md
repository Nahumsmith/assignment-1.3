# Assignment 1.3
#### Nahum Smith
---------------------------------------------------------

This is assignment 1.3 from NYCDA's Part-Time Full Stack Immersion Course. 

# CSS Layout

Create 3 different web pages exemplifying some of the different layouts possible with CSS:

- Two-column layout, fixed "social media bar" on the left side of the page with a link to Facebook and Twitter

- Three-column layout web page

- An image gallery using floats

## Grading Criteria

- At least 3 different web pages, including:

- Two-column layout, fixed "social media bar" on the left side of the page with a link to Facebook and Twitter
__3 Points__

- Three-column layout web page
__3 Points__

- An image gallery using floats
__3 Points__

- Inline code commenting and a ReadMe
__1 Points__

__Total__: 10 Points

Each web page represents 3 points of the assignment. 1 additional point is available for students that did an exceptional job.

*You should use floats and positioning to create the different layouts. Look up examples of these different layouts, and try to emulate them.

# My Approach

First, I reset my styles by importing [Eric Meyers Reset stylesheet](http://meyerweb.com/eric/tools/css/reset/).  Next, I decided to create a universal `<header>`, `<nav>`, and `<footer>` that was present on each of the three pages.  I practiced using `inline <ul>` that were styled using `:hover`. 

For **Page 1, a two column layout with fixed social media bar**, I placed a `background-image` as part of the CSS of a container.  For the social media bar, I imported from [We Love Fonts](http://weloveiconfonts.com/api/?family=entypo).  Additionally, I placed two short columns of text on the page. 

For **Page 2, a three column layout**, I wanted to create a `<nav>` as the left column that functions as an indexing table of contents for the document, as if the site were for reading longer imported documents/text. The center column is the main container that the document is presented in.  The right column is for whatever advertising or other links required by the site. 

For **Page 3, an image gallery using floats**, I (obviously) used a variety of headshots from famous philosophers.  `float` was used on these pics and they were all placed in a sized `thumbnail-window`.  Each thumbnail was markuped as a link to a separate page, where further design could create some form of written content for the specific philosopher.  
