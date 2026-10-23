# Assignment-01 – TuteDude Semantic HTML Page

A single-page website for **TuteDude**, a fictional learning platform, built to practise semantic HTML structure and a wide range of HTML tags.

## 🔗 Live Demo

**Deploy link:** https://pranavpatkari.github.io/Assignment-01/

> Replace the link above if you deploy somewhere else (Netlify, Vercel, Render static site, etc.).

## 📁 Project Structure

```
Assignment-01/
├── index.html        # Main page
├── thank-you.html    # Form submission confirmation page
├── style.css         # Styles
├── images/
│   └── hero.svg      # Hero illustration
└── README.md
```

## 🧱 Page Sections & Tags Used

| Section | Elements |
|---|---|
| **Header** | `<header>`, `<h1>` with `<mark>` and `<strong>`, description using `<em>` / `<strong>`, `<nav>` menu, hero `<figure>` + `<img>` + `<figcaption>` |
| **About** | `<section>`, `<article>` with `<strong>`, `<em>`, `<b>`, `<i>`, `<u>`, `<dfn>`, `<abbr>`, `<small>`; `<blockquote>` with `<cite>` attribution |
| **Menu** | Main `<table>` with `<caption>`, `<thead>`, `<tbody>`, `<tfoot>`, `scope` headers and `colspan`; **nested tables** with per-course "learning nutrition facts" |
| **Trivia** | `<aside>` with `<ul>`, `<ol>`, `<dl>` / `<dt>` / `<dd>`, `<time>`, `<code>`, `<sup>`, `<sub>` |
| **Extras** | `<audio>` and `<video>` with multiple `<source>` fallbacks, `<details>` / `<summary>` |
| **Feedback form** | `<form>`, `<fieldset>`, `<legend>`, `<label>`, text & email inputs, `<select>` dropdown, radio buttons, checkbox, `<textarea>`, submit & reset buttons |
| **Footer** | `<footer>`, `<address>` with `mailto:` / `tel:` links, `<small>` copyright |

## ✅ Features

- Semantic, accessible structure: skip link, labelled sections, `alt` text, `scope` on table headers, visible focus styles.
- All navigation links jump to their sections; "Back to top" link in the footer.
- Media is playable in the browser (audio + video with fallbacks).
- The feedback form validates required fields and **submits** to `thank-you.html`, which displays the submitted values — no backend required.
- Responsive layout (tables scroll horizontally on small screens).

## ▶️ Run Locally

Just open `index.html` in a browser, or serve the folder:

```bash
python3 -m http.server 8000
# then visit http://localhost:8000
```

## 🚀 Deploy (GitHub Pages)

1. Push this folder to a public repo named `Assignment-01`.
2. Go to **Settings → Pages**.
3. Under *Build and deployment*, choose **Deploy from a branch**, select `main` and `/ (root)`, then **Save**.
4. After a minute the site is live at `https://<your-username>.github.io/Assignment-01/`.

## 👤 Author

**Pranav Patkari** – [GitHub](https://github.com/pranavpatkari)
