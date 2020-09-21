# HTML Comprehension Questions

## Q1 - For each of the following HTML documents, is the HTML valid?

Type true/false in the provided [ ].

a) [ false] `<div><span>hello</div></span>`

b) [ false ]

```html
<ul>
<li>one</li>
</ol>
```

c) [ true ] `<ul></ul><img/><ol><li>one</li></ol>`

## Q2 - What is a screenreader and why should we care about them?

_Feel free to use the powers of Google here, but please provide link(s) to your source(s)_

It's a tool that converts digital text int osynthesized speech
 https://webaim.org/techniques/screenreader/

## Q3 - For each of the following cases, which tags will be needed?

a) You want to create a webpage with the photos from your latest vacation
<ul><li></li></ul>, <img src="">

b) You want to create a website that lists all the art gallery websites in your city and links to their website.
<ul><li></li></ul>, <img src="">, <a href=""></a>

c) You want to sell designer hats. You need to receive orders from the user.
<ul><li></li></ul>, <img src="">, <a href=""></a> <button></button>

## Q4 - Can a `button` be a child of a `button`? Explain your reasoning
No, button tag cannot have an interactive child/descendant

https://stackoverflow.com/questions/39386497/can-i-nest-button-inside-another-button#:~:text=2%20Answers&text=It%20is%20not%20valid%20to,inside%20a%20element.&text=Interactive%20content%20includes%3A,embed

## Q5 - What is the most generic tag you can use?
<div></div>
## Q6 - What do the following achronyms stand for?

a) `a` - anchor

b) `ol` - ordered list

c) `ul` - unordred list

d) `li` list

e) `tr` table row

f) `th` table header

g) `td` table data 

## Q7 - Usually, `td` elements are children of what kind of elements?
table row - tr

## Q8 - What is the difference between td and th?
th is used for the table's header information, td is used for an other datas on the table 

## Q9 - Which tag makes the text appear bigger: h1 or h3?
h3

## Q10 - In which situation can you use self closing tags?
when the tag has to dom content (but might need attributes)

## Q11 - What is autofilling and why is it important?
it gives a suggestion to autocomplete an html input if the user has already filled a similar form previously. Important because it lets the user save time and avoid redundancy of action 
## Q12 - Which attributes are always present in an img element?
src attribute

## Q13 - Which attribute is always present for an anchor tag?
href attribute
