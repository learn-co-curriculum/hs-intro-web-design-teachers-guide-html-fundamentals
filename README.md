###SWABTS
***Create a brand new HTML page and style it with CSS***
  + HTML - structure an html page using doctype, html, head and body tags
  + HTML - explain what goes into the head of the document
  + HTML - add text to a page using p and h1 tags
  + HTML - add images using img tags
  + HTML - add links using a tags and understand the difference between relative and absolute paths
  + HTML - create multiple pages and link them
  + HTML - create an ordered list using ul and ol tags
  + HTML - include comments
  + HTML - Understand HTML elements that are deprecated and why they shouldn't be used
  + HTML - create tables
  + CSS - link a CSS stylesheet to an HTML page
  + CSS - explain the purpose of CSS
  + CSS - change the font style using font-size, font-family and font-color
  + CSS - centering text
  + CSS - Change image size with height and width
  + CSS - add background

### Motivation / Why Should You Care?
Yesterday you used a prepared template to create personal pages for our student directory. Today you are going to learn how to create an HTML site from scratch, create your own styles for the page and deploy it to the world wide web with GitHub.

### Lesson Plan
+ Will be publishing sites on Github Pages, so conventions we need to follow 
  * GitHub automatically gives you a platform to publish your own site and reserves this url for your <your github username>.github.io.
+ In terminal from inside `development` directory make a directory called your_github_username.github.io
+ cd into that directory and make a `css` directory and an `index.html` file.
+ In `index.html`:
  * `<!doctype html>` 
  *  `<html></html>`
  * `<head></head>`
  * `<body></body>`
+ What do you want your website to be about, and three things you love about it:
  * [Corgis?](http://corgiaddict.com/) 
  * [Bacon?](http://www.royalbaconsociety.com/)
  * [Sanwiches?](http://fortheloveofsandwich.tumblr.com/) 
  * [Norwegian Olympic Curling Team’s pants?](https://www.facebook.com/NOCTP)
+ Header: h1 tags
 * Visitors can see right away what your site is about 
 * Google looks for h1 tags for page topics
+ Add the following to your page for each of the three reasons you love your topic:
  * a subheader for the top
  * a p tag with a short descriptive paragraph
  * an image that goes along with the thing 
  * a link to somewhere on the web where I can find more information about the topic. 
+ CSS: 
  * write in a separate file - separation of concerns, easier to debug
  * create directory called `css` and inside a file called `style.css`
+ In `style.css` to make h1 font color red: `h1 { color: red; }`
  * h1 is CSS selector
  * property and value go between curly braces
  * colons and semi-colons are important
  * refresh browser: won't see change because not linked
+ `<link rel="stylesheet" type="text/css" href="css/style.css">` inside head tag in `index.html`
  * `rel` attribute: relationship of file being linking
  * `type` attribute: the type of file being linked
  * `href` attribute: where to find the file being linked
    * have to tell our `index.html` how to find `style.css`, so it needs to go inside css directory first
+ Other styling:text size, image size, centering text, background color, background image and have them style their page.
  * see code snippets!!!! NEED TO WRITE THESE
+ RGBA vs Hexadecimal color - introduce color picker !!!! NEED TO WRITE THESE
+ Google fonts !!!! NEED TO WRITE THESE
+ Adding pages to your site: create three separate html files 
+ Inside of those files set up your html file structure
+ To link to pages in the same site, use a tag.
  * If site has `index.html` and `pig_facts.html` and theyre in the same directory, having a link from `index.html` to `pig_facts.html` looks like this: `<a href="pig_facts.html">click here for pig facts</a>`
+ Put links in an unordered list using ul and li tags
  * will style next class as a nav bar

### Conclusion / So What?
CSS allows us to add styling to our page. Together, HTML and CSS give us the we as we know it. 

### Hints and Hurdles
+ Test all your CSS examples first and know how you're going to live code them. It's easy to make mistakes here that are hard to get out of