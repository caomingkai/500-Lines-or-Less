# 500 Lines

## I. A Template Engine

#### Main idea: similar to Python string's **format method** like " A is {title} of B".format(title="father"); Whereas, **template engine** is also a formatter, but much more powerful.
> An important phase in any web application is generating HTML to be served to the browser.

> Very few HTML pages are completely static: they involve at least a small amount of __dynamic data__, such as the user's name. Usually, they contain a great deal of dynamic data: product listings, friends' news updates, and so on.

> The mostly-static style used in templates is the opposite of how most programming languages work.

> A template language flips this around: **the template file is mostly static literal text, with special notation to indicate the executable dynamic parts.**

#### template syntax
1.  dot : {{product.price}}
```html
...<p>The price is: {{product.price}}, with a {{product.discount}}% discount.</p>
```
2. filters with pipe character:  {{story.subject|slugify|lower}}
```html
<p>Short name: {{story.subject|slugify|lower}}</p>
```
3.
