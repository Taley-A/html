# HTML Comprehension Questions

## Q1 - For each of the following HTML documents, is the HTML valid?

Type true/false in the provided [ ].

a) [false] `<div><span>hello</div></span>`

b) [false]

```html
<ul>
<li>one</li>
</ol>
```

c) [false] `<ul></ul><img/><ol><li>one</li></ol>`

## Q2 - What is a screenreader and why should we care about them?

A screen reader is a software application that enables people with severe visual impairments to use a computer. Screen readers work closely with the computer’s Operating System (OS) to provide information about icons, menus, dialogue boxes, files and folders. The device provides access to the entire OS that it works with, including many common applications. We should care about them because when designing a website, we want it to be accessible to everyone.

Source: https://www.nomensa.com/blog/what-screen-reader

## Q3 - For each of the following cases, which tags will be needed?

a) You want to create a webpage with the photos from your latest vacation 

<html>
  <body>
    <h1>My Website</h1>
    <article>    
        <img
        src="https://example.com/images/thailand-sunset.png"
        alt="Sunset on the beach in Thailand"
        />
    </article>    
  </body>
</html>

b) You want to create a website that lists all the art gallery websites in your city and links to their website.

<html>
  <body>
    <h1>My Website</h1>
        <article>
        <ul>
        <li><a href="http://google.com">The googs</a></li>
        </ul>
        </article>    
  </body>
</html>


c) You want to sell designer hats. You need to receive orders from the user.

<html>
  <body>
    <h1>My Website</h1>
        <article>
        <button><a href="foobar"></button>
        </article>    
  </body>
</html>


## Q4 - Can a `button` be a child of a `button`? Explain your reasoning

The button tag is used to display a clickable button. Its descendants cannot be a clickable element.
It is also an inline element and it should only contain text and nothing else. Therefore, it can't be a child.

## Q5 - What is the most generic tag you can use?

<div>

## Q6 - What do the following achronyms stand for?

a) `a` anchor tag

b) `ol` ordered list

c) `ul` unordered list

d) `li` list item

e) `tr` table row 

f) `th` table head

g) `td` table cell

## Q7 - Usually, `td` elements are children of what kind of elements?

`tr` element

## Q8 - What is the difference between td and th?

`th` contains the headers for the columns of the table. `td` is for the table data.

## Q9 - Which tag makes the text appear bigger: h1 or h3?

Usually h1, but it depends on the CSS.

## Q10 - In which situation can you use self closing tags?

When the element has no text between its tags. 
`<img>` is a good example

## Q11 - What is autofilling and why is it important?

It is when the browser fills input field and it makes it easier.

## Q12 - Which attributes are always present in an img element?

src=""
alt=""

## Q13 - Which attribute is always present for an anchor tag?

href=""