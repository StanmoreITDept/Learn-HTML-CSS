## The HTML Page Structure

![image](https://github.com/user-attachments/assets/1ac6375c-75af-4b76-8657-e7be86f3acc2)

## The HTML Site Map

```html
📄 HTML Document
│
├── 🧠 <head>
│   ├── 📌 <title>Title of the Page</title>
│   └── 🔗 <link> / <meta> (metadata, CSS links, etc.)
│
└── 🖼️ <body>
    ├── 🧢 <header> - Top section (e.g. logo, nav)
    ├── 🧭 <nav> - Navigation menu
    ├── 📦 <main>
    │   ├── <section> - Group of related content
    │   └── <article> - Independent content
    ├── 🪟 <aside> - Sidebar (optional)
    └── 🦶 <footer> - Bottom section (e.g. copyright)
```

## Sample Website based on sitemap

you can write this code out on Notepad.

```html
<!DOCTYPE html>
<html>
  <head>
    <meta charset="UTF-8">
    <title>My First Webpage</title>
    <link rel="stylesheet" href="styles.css">
  </head>

  <body>
    <header>
      <h1>Welcome to My Site</h1>
    </header>

    <nav>
      <ul>
        <li><a href="#">Home</a></li>
        <li><a href="#">About</a></li>
        <li><a href="#">Contact</a></li>
      </ul>
    </nav>

    <main>
      <section>
        <h2>About Us</h2>
        <p>We are learning HTML!</p>
      </section>

      <article>
        <h3>Latest News</h3>
        <p>This is our first article.</p>
      </article>
    </main>

    <aside>
      <p>Did you know? HTML is not a programming language.</p>
    </aside>

    <footer>
      <p>&copy; 2025 My Website</p>
    </footer>
  </body>
</html>
```

![image](https://github.com/user-attachments/assets/d88266b5-4294-4c85-806f-d73b5a3ca34b)



### Reference
- W3Schools (https://www.w3schools.com/)
