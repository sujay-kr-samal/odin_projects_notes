# Links and Images

## Anchor Element `<a>`
- Links banane ke liye `<a>` tag use karo
- `href` attribute = destination URL

```html
<a href="https://www.theodinproject.com">Odin Project</a>
```

---

## New Tab mein Open karna
```html
<a href="https://google.com" target="_blank" rel="noreferrer">Google</a>
```
- `target="_blank"` → new tab mein open
- `rel="noreferrer"` → security ke liye (tabnabbing prevent karta hai)

---

## Absolute vs Relative Links

### Absolute Link
- Poora URL hota hai (scheme + domain + path)
- Doosri websites ke liye
```html
<a href="https://google.com/about">About</a>
```

### Relative Link
- Sirf file path hota hai
- Same website ke pages ke liye
```html
<a href="./pages/about.html">About</a>
```

> [!summary] Metaphor 
> Domain = shahar, Website folder = museum
> Absolute = poora address (city + museum + room)
> Relative = sirf room number (current location se)

---

## Images `<img>`
- Void element — closing tag nahi hota
- `src` = image ka path
- `alt` = alternative text (accessibility + fallback)
- `width` & `height` = page jump prevent karne ke liye

```html
<img src="./images/dog.jpg" alt="A cute dog" width="300" height="200">
```

---

## File Paths
- `./` → current directory
- `../` → parent directory (ek level upar)
- `./pages/about.html` → current folder ke andar pages folder
- `../images/dog.jpg` → parent folder ke andar images folder

> [!summary] Quick Reference
> `<a href="">` = link
> `<img src="" alt="">` = image
> `./` = current dir | `../` = parent dir
> Absolute = full URL | Relative = file path only

## Image Formats
| Format | Best For                                        |
| ------ | ----------------------------------------------- |
| JPG    | Photos, gradients — no transparency             |
| GIF    | Animations — limited colors                     |
| PNG    | Icons, logos, diagrams — supports transparency  |
| SVG    | Vector graphics — scales without quality loss ✅ |

> [!tip] 
> SVG use karo jab bhi possible — responsive aur crisp!