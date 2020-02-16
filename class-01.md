# summary 
in the introduction the book intruduce how you can learn and how you can use this book.
the book will give you knowladge about 90% but you need to study and use google to git 100%.
## how people access the web
1. browser
like: firefox, chrom, safari and opera.
2. web server which hosts your web
3. devices include PC, laptops, tablet and phone.
3. screen readers 
programs that read out the contents of a computer screen to a user.
## how websites are created
1. what you see
web pages include text, image audio, video, and animation.
2. how it is created 
Small websites are often written just using HTML and CSS.
large website use a content management system (CMS), blogging tools, or e-commerce software.

**when visit your web, the browser will first connect to a domain name system (DNS) server**
the structure has the main heading and maybe have also subheading like *an article in the newspaper*.

## Html elements 
the elements have 2 tags opining tag and close tag.
the close tag have /
Html use element to describe the structure of pages.
- attributes tell us more about element:
1. appear in the open tag
2. have a two part: name and value

`<body>` every things inside this element is shown in the main browser window.
`<head>` contains information about page. usually the `<title>` will be inside this element.
`<title>` shown in the tab of browser

DOCTYPE to tell a browser which version of html you use
- comment in Html `<!-- comment goes here -->'
- ID attribute help us when usig CSS. The id attribute is known as a global attribute because it can
be used on any element.
- CLASS attribute can use this attribute many time.
- block element 
like: `<h1>, <p>, <ul> and <li>`
- inline element appear on the same line
like: `<a>, <b>, <em> and <img>` em for italic b for bold
- grouping text and elements in a block
like: `<div>` will start in a new line
- grouping text and elements inline
`<span>`
- iframes 
little window that has been cut into your page.
`<iframe width="450" height="350" src="http://maps.google.co.uk/maps?q=moma+new+york
&amp;output=embed">
</iframe>`
seamless attribute can be applied to an iframe where scrollbars are not desired.
- information about page 
`<meta>` not visible to users but fulfills a number of purposes such as telling search engines
about your page, who created it.
attribute with meta: p191-192
1. description
2. keywords
3. robots
4. author
5. pragma
6. expires
 if you need to use a chracter in web use what are termed "escape" characters also known as escape codes or
entity references).
For example, to write a left angled bracket, you can use either &lt; or &#60;.p194

## tags are in Html5 just
- `<header>`
- `<footer>`
- `<nav>`
- `<article>`
- `<aside>`
- `<section>`
- `<hgroup>` element is to group `<h>`tags.
- `<figure>` includes: Images, Videos, Graphs ,Diagrams ,Code samples and Text that supports the main
body of an article. also, it contains `<figcaption>` which provide a text element decription for the 
content of `<figure>`.

## help our browser to understand Html5
need to use a simple JavaScript known as the HTML5 shiv or HTML5 shim.
using additional comment `<!--[if lt IE 9]> <script src="http://html5shiv.googlecode.com/svn/trunk/html5.js"></script>
<![endif]-->`

- site maps
is a diagram of the pages that will be used to structure the site.
- wireframe make design easier because you know what information needs to appear on
which page before considering how the the page should look.

## Visual hierarchy
1. size
2. color
3. style

## javascript
added last and enhances the usability of the page or the experience of
interacting with the site.
link javascript with Html by using `<script>` tag

**using objects and methods in Javascript**
document.write ('good afternoon');
object: document
parameters: good afternoon
