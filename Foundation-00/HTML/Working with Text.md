# Working with Text


## Paragraphs
- Browser whitespace compress kar deta hai → sab ek line mein aa jaata hai
- Paragraph ke liye `<p>` tag use karo

```html
<p>Yeh ek paragraph hai.</p>
<p>Yeh doosra paragraph hai.</p>
```

---

## Headings
- 6 levels hote hain: `<h1>` se `<h6>`
- `<h1>` = sabse bada, `<h6>` = sabse chhota
- `<h1>` = page ka main heading (sirf ek hona chahiye)

```html
<h1>Main Heading</h1>
<h2>Sub Heading</h2>
<h3>Sub Sub Heading</h3>
```

---

## Strong & Em Elements

### `<strong>` — Bold + Important
- Text bold karta hai
- Screen readers ke liye important mark karta hai

### `<em>` — Italic + Emphasis
- Text italic karta hai
- Screen readers emphasis dete hain

```html
<p>Yeh <strong>important</strong> hai.</p>
<p>Yeh <em>emphasized</em> hai.</p>
```

---

## Nesting & Relationships
- Elements ke andar elements = **nesting**
- **Parent** = outer element
- **Child** = inner element
- **Siblings** = same level ke elements

```html
<body>          <!-- parent -->
  <p>Para 1</p> <!-- child + sibling -->
  <p>Para 2</p> <!-- child + sibling -->
</body>
```

---

## HTML Comments
- Browser ko nahi dikhta — sirf developers ke liye
- Shortcut: `Ctrl + /`

```html
<!-- Yeh ek comment hai -->
```

> [!summary] Quick Reference
> `<p>` = paragraph
> `<h1>`-`<h6>` = headings
> `<strong>` = bold + important
> `<em>` = italic + emphasis
> `<!-- -->` = comment