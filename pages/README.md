# Brightpath Maths Tutoring: HTML-Only Website

## Project name and description

**Brightpath Maths Tutoring** is a small business website for a fictional maths tutoring service. It is the final project for Module 02 (HTML Foundations). The site is written in **HTML only**: it has no CSS, no JavaScript, no frameworks, no website builders, no templates and no inline style attributes. The plain browser appearance is intentional, because the project is assessed on structure, meaning, accessibility and correctness.

All business details are fictional. The email address uses the reserved `.example` domain, and the telephone number is a dummy number. The forms are demonstrations and do not send data anywhere.

## Pages included

| File                         | Purpose                                                                              |
| ---------------------------- | ------------------------------------------------------------------------------------ |
| `index.html`                 | Home page with introduction, hero image, lists and links to the rest of the site     |
| `about.html`                 | Story, teaching approach (description list) and the tutor                            |
| `services.html`              | Topics, a prices table, frequently asked questions and how to book                   |
| `blog.html`                  | Three articles with dates, a figure and an external link                             |
| `contact.html`               | Contact details, opening hours table and a contact form                              |
| `pages/application.html`     | Full student application form (in a child folder)                                    |
| `images/`                    | Logo, favicon, hero image, tutor portrait, whiteboard image and a decorative divider |
| `media/sample-worksheet.pdf` | One-page downloadable sample worksheet                                               |

## HTML features used

- **Document structure on every page:** `<!DOCTYPE html>`, `lang="en"`, UTF-8 charset, descriptive `<title>`, description, author and viewport metadata, and a favicon link.
- **Semantic landmarks:** `<header>`, `<nav>` (labelled), `<main>`, `<footer>`, `<section>`, `<article>`, `<address>`, plus a "Skip to main content" link.
- **Headings:** one `<h1>` per page with logical `<h2>` and `<h3>` levels and no skipped levels.
- **Text:** paragraphs, `<strong>`, `<em>`, `<time>` and `<details>`/`<summary>` for the FAQ.
- **Lists:** unordered lists (`index.html`, `services.html`), ordered lists (how it works, how to book, exam steps) and a description list (`about.html`).
- **Links:** internal relative links (`about.html`), fragment links (`#approach`, `#faq`, `#top`, `#main`), cross-page fragment links (`services.html#prices`), external links (Khan Academy), email links (`mailto:`), telephone links (`tel:`), and a file link to the PDF.
- **Paths:** child-folder paths (`pages/application.html`, `images/hero-lesson.png`, `media/sample-worksheet.pdf`) and parent-folder paths from `pages/application.html` (`../index.html`, `../services.html#prices`, `../images/logo.png`).
- **Images:** meaningful `alt` text, an empty `alt=""` on the decorative divider, `width` and `height` on every image, and `<figure>` with `<figcaption>`.
- **Tables:** two data tables with `<caption>`, `<thead>`, `<tbody>`, `<tfoot>`, column and row header cells (`scope`) and a `colspan`.
- **Forms:** text, email, telephone, number, select, radio, checkbox and textarea controls; every control has a `<label>` linked with `for` and `id`; `<fieldset>` and `<legend>` groups; constraints (`required`, `minlength`, `maxlength`, `min`, `max`, `step`, `pattern` with a `title`); `autocomplete` hints; and submit buttons.
- **Keyboard and accessibility:** native elements only (links, buttons, form controls, details), clear link text, labelled landmarks and `aria-current="page"` on the active navigation link.
