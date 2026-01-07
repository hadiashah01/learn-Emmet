## Emmet Basics Practice

Hands-on practice files for learning core **Emmet syntax**:

- [text`{}`](text.html)
- [child`>`](child.html)
- [multiplication`*`](multiplication.html)
- [grouping`()`](grouping.html)
- [sibling`+`](sibling.html)

Each file demonstrates one Emmet concept with a simple HTML example.

## Emmet Syntax and Its Generated HTML Output

### Emmet Text Syntax `{}`
```emmet
p{Paragraph} 
```
**Output**
```html 
<p>Paragraph</p>
```

### Emmet Child Syntax `>`
```    html 
header>h1{Heading} 
```
**Output**
```html 
<header>
    <h1>Heading</h1>
</header>
```

### Emmet Multiplication Syntax `*`
```    html 
ul>li*5{list item} 
```
**Output**
```html 
<ul>
    <li>list item</li>
    <li>list item</li>
    <li>list item</li>
    <li>list item</li>
    <li>list item</li>
</ul>
```

### Emmet Grouping Syntax `()`
```    html 
main>(ul>li*4{List Item})*3
```
**Output**
```html 
<main>
    <ul>
        <li>List Item</li>
        <li>List Item</li>
        <li>List Item</li>
        <li>List Item</li>
    </ul>
    <ul>
        <li>List Item</li>
        <li>List Item</li>
        <li>List Item</li>
        <li>List Item</li>
    </ul>
    <ul>
        <li>List Item</li>
        <li>List Item</li>
        <li>List Item</li>
        <li>List Item</li>
    </ul>
</main>
```

### Emmet Sibling Syntax `+`
```    html 
div>(section>h2{Heading}+p*3{Paragraph})*2+section*2
```
**Output**
```html 
<div>
    <section>
        <h2>Heading</h2>
        <p>Paragraph</p>
        <p>Paragraph</p>
        <p>Paragraph</p>
    </section>
    <section>
        <h2>Heading</h2>
        <p>Paragraph</p>
        <p>Paragraph</p>
        <p>Paragraph</p>
    </section>
    <section></section>
    <section></section>
</div>
 
```


