# HTML Boilerplate

> Related : [[Links and Images]], [[Lists]], [[Working with Text]], [[Elements and Tags]]

## Basic Boilerplate Structure
```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8">
    <title>My First Webpage</title>
  </head>

  <body>
    <h1>Hello World!</h1>
  </body>
</html>
```

---

## Boilerplate ke Parts

### DOCTYPE
- `<!DOCTYPE html>` → browser ko batata hai HTML5 use karo
- Har HTML file ki **pehli line** honi chahiye

### `<html>` Element
- Root element — sab elements iske andar hote hain
- `lang="en"` → accessibility ke liye language specify karo

### `<head>` Element
- Meta information hoti hai — browser ke liye, user ko nahi dikhta
- `<meta charset="UTF-8">` → special characters sahi dikhne ke liye
- `<title>` → browser tab mein naam dikhta hai

### `<body>` Element
- Yahan sab **visible content** jaata hai
- Text, images, links, buttons — sab kuch

---

## Important Notes
- Homepage file ka naam hamesha **`index.html`** rakhna
- VSCode shortcut → `!` + Enter = poora boilerplate auto-generate

## Browser mein Open karna (WSL)
```bash
explorer.exe index.html
```

> [!summary] Structure
> DOCTYPE → html → head → body
> Head = browser info | Body = user content