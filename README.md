# What's Markdown?
Markdown is punctuation for the web. It enables authors to easily write documents that feature common online staples like [links](http://google.com), images, as well as *italicized*, **bold**, and other types of rich text, using a simple, lightweight set of symbols that can easily be converted to HTML, doc, pdf, or rtf files. Since markdown files are just plain text, they're an ultra-portable way to write web-compatible content without the mess of a WYSWIG editor or proprietary file types.

# Why Use It?
For the same reasons you've probably used markdown before (if you've ever signalled *emphasis* using `*asterisks*`, you've used it):

1. **It's everywhere**. Although different markdown flavors vary slightly, the core functionality is universal and the number of outlets that support it is constantly growing . Wordpress, Github, Slack, and Jekyll are just a handful of those sites that allow you to write in markdown.  
2. **It's versatile**. Besides blog posts and social media comments, the language can be used for documentation, wikis, books, and anything else that requires a clean but expressive formatting palette.  
3. **It's easy**. With just a few examples, you'll get 95% of everything you'll need to use on a daily basis. Designed to be read just as easily as it's written, markdown allows you to create HTML (or other documents) without the clutter and confusion of endless tags.

# 1-Minute Markdown
Here are markdown's Greatest Hits: Bread-and-butter examples that are a tiny subset of the core functionality commonly available, but most of what you'll often use.

`*italics*` *italics*

`**bold**` **bold**

`[link text](http://somewhere.com)` [link text](http://somewhere.com)

`![caption](http://www.thinkstockphotos.com/CMS/StaticContent/Hero/TS_AnonHP_462882495_01.jpg)`

![caption](http://www.thinkstockphotos.com/CMS/StaticContent/Hero/TS_AnonHP_462882495_01.jpg)

Headers in markdown are given weight proportional to their hash prefixes.

`# Header` `<h1>Header</h1>`

`## Header` `<h2>Header</h2>`

`### Header` `<h3>Header</h3>`

`#### Header` `<h4>Header</h4>`

`##### Header` `<h5>Header</h5>`

`###### Header` `<h6>Header</h6>`

````
- dashes
- create
- bullets
	- and you can nest them
````
- dashes
- create
- bullets
	- and you can nest them

If you'd like to escape the markdown syntax and show something in an inset well (the "code view"), surround your text with ticks ``

Line breaks occur naturally after headers and blank lines. If you'd like to enforce a premature line break, you can add two blank spaces to the end of the line to simulate a `<br>` tag.

And speaking of `<br>` tags, **HTML tags are valid in markdown**, meaning that if you'd like to drop in a regular 'ol `<br>` tag that's OK too.

# How To Use It
Although markdown is ultimately just plain text (so you can write markdown content using any editor) there are many applications that support extra features, like automatically implementing markdown in-page or providing an easy preview window to see what it looks like rendered. There are also many ways to translate `.md` files into other types if you need your content in pdf, doc, or another form. Here's just a smattering of some of the best options:

## Web
[Dillinger](http://dillinger.io/)  
[StackEdit](https://stackedit.io/editor)  
[Markable](https://markable.in/)

## Native
[Mou](http://25.io/mou/) (Mac)  
[Write](http://writeapp.net/) (Mac)  
[iA Writer](https://ia.net/writer/mac) (Mac)  
[BBEdit](http://www.barebones.com/products/bbedit/) (Mac - "HTML and text editor")  
[MarkdownPad](http://www.markdownpad.com/) (Windows)  
[MarkPad](http://code52.org/DownmarkerWPF/) (Windows)  
[Haroopad](http://pad.haroopress.com/) (Windows and Linux)  
[Atom](https://atom.io/) (Windows, Mac, and Linux - "Hackable text editor")

In general, just about every code editor or text editor used to write code will support markdown, either natively or via plugin.  You can even author markdown content using [Microsoft Word](http://www.writage.com/) if you'd prefer.

## Programmatically
There are a few scripts you can use to either translate markdown on the command line or build your own translation application.  
[The original perl script](http://daringfireball.net/projects/markdown/)  
[A PHP port of the original](https://michelf.ca/projects/php-markdown/)  
[pandoc, a universal document converter](http://pandoc.org/)  

# Further Reading
If this has piqued your interest &mdash; or you are encountering scenarios beyond this poor guide &mdash; here are some further resources that investigate the topic in greater depth.
[John Gruber's original markdown syntax](http://daringfireball.net/projects/markdown/syntax)  
[Commonmark, an attempt at unifying markdown versions](http://commonmark.org/)  
[markdowntutorial.com](http://markdowntutorial.com/)  
[whatismarkdown.com](http://whatismarkdown.com/)  
