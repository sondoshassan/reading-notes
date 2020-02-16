# summary for class-02
## Text
- heading
we are using `<h>` tags from 1 to 6.
we are using `<h1>` for the main heading but another for subheading.
- pragraphs
we are using for write a pragraph `<p>` tag.
- bold & italic 
bold `<b>` , italic `<i>`
- superscript & subscript
1. `<sup>` it contains characters such math concept.
ex: `E=MC<sup>2</sup>`
2. `<sub>` using for foot notes or chemical formulas.
ex: `CO<sub>2</sub>`
- white space 
the browser see all the space as one space. This is known as **white space collapsing**.
- line breaks & horizontal rules
`<br />` it makes every thing after this tag at a new line.
`<hr />` to create a horizontal rules
- strong & emphasis
`<strong>` when using this element we say for the browser this content is strong
`<em>` indicator for emphasis content
- quotations
`<blockquto>` longer quotes it has a pragraph in it
`<q>` short quotes
- abbeviations & acronyms
`<abbr>` using for abbrevation or an acronmy. also, it has a title attribute.
- citations & definitions 
`<cite>` referencing a pice of work
`<dfn>` indicate the defining instance of a new term.
- author details 
`<address>`
- changes to content
`<ins>` underline content
`<del>` delet line through content
`<s>` something is not accurate

## CSS
CSS rules contains selector and declaration.
like: `p {
    color: black;}`
    selector is p, declaration is color: black;.
we can use many selector with one declartion.

connect CSS with Html by using: `<link href="css/styles.css" type="text/css"
rel="stylesheet" />`

- using internal CSS by `<style>` tag.

### why use external style sheets?
1. you can use the CSS sheet for many pages in website
2. when the user upload your page, it will upload faster
3. easy to change in it
4. Html is easy to read

## basic JavaScript
- comment
multi-line `/* multi-lines */`
one line `// one line`

### What is a variable?
- using it for stored data.
- it must be a good name.
you can write the variable like this:
`var nameVar;`
*assign variables*
`nameVar = 5;`
- data types 
data types | example
-----|------
numeric data | 0.5
string data | "hello!"
boolean data | true or false

**for string data type you can use double or single quotation.**

- shorthand for creating variables
`var name = "sondos";`
you can change the value of a variable by reassigning the same var.

### rules for naming variables
1. the name must begin with a letter, $, _
2. must not use - or . 
3. can't use keywords or reserved words.
4. variable is case sensitive.
5. use good name to describe the variable
6. if your variable made from two words, it will be the second-word start with a capital letter like nameVar.

### arrays
stores a list of values
**array literal**
`var colors;
colors ['white', 'black', ' custom '];`
**array constructor**
`var colors = new Array('white ' ,
'black',
'custom ' );`
- each item in the array has an index number.
- accessing items in an array ex: 
`var itemSecond;
itemSecond = colors [1];`
- length of array `colors.length;`

## loops and decisions
we can use if statment for decisions
`if (score>50){
    document.write ("your passed");
}
else {
    document.write ("your fail");
}`

### comparison operators
name of operators | operators
---- | -----
equal to | ==
not equal to | !=
strict equal to | ===
strict not equal to | !==
greater than | >
less than | <
greater than or equal | >=
less than or equal | <=

### logical operator
1. and `&&`
2. or `||`
3. not `!`




























