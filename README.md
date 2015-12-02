###SWABTS
***Create a brand new HTML page from scratch***
+ Structure an html page using doctype, html, head and body tags
+ Explain what goes into the head of the document
+ Add text to a page using p and h1 tags
+ Add images using img tags
+ Add links using a tags and understand the difference between relative and absolute paths
+ Create multiple pages and link them
+ Create an ordered list using ul and ol tags
+ Include comments
+ Understand HTML elements that are deprecated and why they shouldn't be used
+ Create and understand when to use tables
+ Understand how to use HTML5 `audio` and `video` tags


### Motivation / Why Should You Care?
Yesterday you used a prepared template to create personal pages for our student directory. Today you are going to learn how to create an HTML site from scratch, create your own styles for the page and deploy it to the world wide web with GitHub.

### Lesson Plan
+ Will be publishing sites on Github Pages, so conventions we need to follow 
  * GitHub automatically gives you a platform to publish your own site and reserves this url for your <your github username>.github.io.
+ In terminal from inside `development` directory make a directory called your_github_username.github.io
+ cd into that directory and make a `css` directory and an `index.html` file.
+ In `index.html`:
  ```HTML
  <!doctype html> 
  <html></html>
  <head></head>
  <body></body>
  ```
+ What do you want your website to be about, and three things you love about it:
  * [Corgis?](http://corgiaddict.com/) 
  * [Bacon?](http://www.royalbaconsociety.com/)
  * [Sanwiches?](http://fortheloveofsandwich.tumblr.com/) 
  * [Norwegian Olympic Curling Team’s pants?](https://www.facebook.com/NOCTP)
+ Header: h1 tags
 * Visitors can see right away what your site is about 
 * Google looks for `h1` tags for page topics
+ Add the following to your page for each of the three reasons you love your topic:
  * a subheader for the top
  * a `p` tag with a short descriptive paragraph
  * an image that goes along with the thing 
  * a link to somewhere on the web where I can find more information about the topic. 
+ Adding pages to your site: create three separate html files 
+ Inside of those files set up your html file structure
+ To link to pages in the same site, use a tag.
  * If site has `index.html` and `pig_facts.html` and theyre in the same directory, having a link from `index.html` to `pig_facts.html` looks like this: `<a href="pig_facts.html">click here for pig facts</a>`
+ Put links in an unordered list using ul and li tags
  * will style next class as a nav bar

### Conclusion / So What?
HTML allows us to define and label the content of our page. Across browsers, there isn't a specification about how text without tags should be rendered. You have no control over how it's displayed, and in future versions of a browser, your code might not be displayed.

### Hints and Hurdles
+ An HTML element is composed of an opening tag, content, and a closing tag
<a href='https://learn.co/lessons/hs-intro-web-design-teachers-guide-html-fundamentals' data-visibility='hidden'>View this lesson on Learn.co</a>
