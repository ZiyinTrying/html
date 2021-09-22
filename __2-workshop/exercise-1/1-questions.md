# HTML Comprehension Questions

## Q1 - For each of the following HTML documents, is the HTML valid?

Type true/false in the provided [ ].

a) [ false] `<div><span>hello</div></span>`

b) [ false]

```html
<ul>
<li>one</li>
</ol>
```

c) [ false] `<ul></ul><img/><ol><li>one</li></ol>`

## Q2 - What is a screenreader and why should we care about them?

_Feel free to use the powers of Google here, but please provide link(s) to your source(s)_
screen readers are software programs that allow visually impaired users to read text by speaking automatically when change occur on the website.
https://www.afb.org/blindness-and-low-vision/using-technology/assistive-technology-products/screen-readers

## Q3 - For each of the following cases, which tags will be needed?

a) You want to create a webpage with the photos from your latest vacation

<nav> <h1> <img> <p> <div><footer>


b) You want to create a website that lists all the art gallery websites in your city and links to their website.
<nav> <h1> <img> <p> <div><footer> <a> <ul> <li>
c) You want to sell designer hats. You need to receive orders from the user.
<h1><form><input><label><select>

## Q4 - Can a `button` be a child of a `button`? Explain your reasoning
no, because button is inline elements. inline elements can not contain other elements.

## Q5 - What is the most generic tag you can use?
<div>

## Q6 - What do the following achronyms stand for?

a) `a`anchor tag

b) `ol` ordered list

c) `ul`list no order

d) `li` list item

e) `tr`table row

f) `th`table head

g) `td`table cell

## Q7 - Usually, `td` elements are children of what kind of elements?
`td` is always the child of `tr`

## Q8 - What is the difference between td and th?
`th` is the header row which format differently.`td` is the content of the table cell.

## Q9 - Which tag makes the text appear bigger: h1 or h3?
h1 is normally bigger than h3, but with the use of css, h3 can be bigger

## Q10 - In which situation can you use self closing tags?
`br` `hr` `img` `input`

## Q11 - What is autofilling and why is it important?
browser can predict the value when the user start to type in a field.

## Q12 - Which attributes are always present in an img element?
`scr=""` `alt=""`

## Q13 - Which attribute is always present for an anchor tag?
`href=""`
