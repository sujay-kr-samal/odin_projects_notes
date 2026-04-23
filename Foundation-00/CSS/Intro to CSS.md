# Intro to CSS

## CSS Basic Syntax
```css
selector {
  property: value;
  property: value;
}
```

---

## Selectors

### Universal Selector
```css
* { color: purple; }  /* sab elements */
```

### Type Selector
```css
div { color: white; }  /* sab div elements */
```

### Class Selector
```css
.alert-text { color: red; }  /* class="alert-text" */
```
- `.` + class name
- Ek element mein multiple classes ho sakti hain

### ID Selector
```css
#title { background-color: red; }  /* id="title" */
```
- `#` + id name
- ID unique hoti hai — ek page pe sirf ek baar

### Grouping Selector
```css
.read, .unread {
  color: white;  /* dono pe same style */
}
```

### Chaining Selector
```css
.subsection.header { color: red; }  /* dono class honi chahiye */
```

### Descendant Combinator
```css
.ancestor .child { }  /* .child sirf tab select hoga jab .ancestor ke andar ho */
```

---

## Common Properties

### Colors
```css
color: red;              /* text color */
background-color: blue;  /* background color */

/* Color formats */
color: #1100ff;          /* HEX */
color: rgb(100, 0, 127); /* RGB */
color: hsl(15, 82%, 56%);/* HSL */
```

### Typography
```css
font-family: "Times New Roman", serif;
font-size: 22px;
font-weight: bold;  /* ya 700 */
text-align: center;
```

### Image Size
```css
img {
  width: 500px;
  height: auto;  /* proportion maintain karta hai */
}
```

---

## CSS add karne ke 3 tarike

### 1. External CSS ✅ (Best)
```html
<head>
  <link rel="stylesheet" href="styles.css">
</head>
```
- Alag `.css` file
- Clean aur reusable

### 2. Internal CSS
```html
<head>
  <style>
    div { color: white; }
  </style>
</head>
```
- Single page ke liye theek hai

### 3. Inline CSS ❌ (Avoid)
```html
<div style="color: white;">...</div>
```
- Messy, repetitive, overrides other styles

> [!summary] Selectors Cheatsheet
> `*` = universal | `div` = type | `.class` = class
> `#id` = ID | `.a, .b` = grouping | `.a.b` = chaining
> `.parent .child` = descendant combinator