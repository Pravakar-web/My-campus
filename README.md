# Web Programming Lab - College Webpage Project

A modern, attractive, and responsive college webpage built using **pure HTML5 and CSS3** without any external libraries or frameworks.

---

## 📋 Features & Requirements Mapping

| Requirement | Description | Implementation File | Key Code Snippet / Style |
| :--- | :--- | :--- | :--- |
| **(a) Page Title** | Set page title to **"My College"** | `index.html` (Line 7) | `<title>My College</title>` |
| **(b) Full Background Image & Overlay** | College background covering the complete page with readability overlay | `style.css` (Section 2) | `background-image: url('campus.jpg');`<br>`background-size: cover;`<br>`background-attachment: fixed;`<br>`.page-overlay` with gradient & backdrop filter |
| **(c) Prominent College Header** | Bold prominent college name + address directly below, center-aligned | `index.html` & `style.css` | `.college-title` (2.6rem bold uppercase)<br>`.college-address` (0.95rem centered text) |
| **(d) Courses Offered (Unique Styling)** | Distinct text color, font style, and typeface for each course | `style.css` (Section 6) | • **BCA**: `'Segoe UI'`, Normal Bold, Royal Blue (`#1d4ed8`)<br>• **B.Sc CS**: `'Georgia'`, Italic, Emerald Green (`#047857`)<br>• **B.Tech**: `'Trebuchet MS'`, Oblique, Crimson Red (`#b91c1c`)<br>• **BBA**: `'Palatino Linotype'`, Italic, Amber (`#b45309`)<br>• **B.Com**: `'Courier New'`, Monospace Normal, Purple (`#6d28d9`)<br>• **MCA**: `'Verdana'`, Oblique, Teal (`#0e7490`) |
| **(e) Scrolling Announcements** | HTML marquee scrolling text with exams, fest, seminars, and admissions | `index.html` & `style.css` (Section 4) | `<marquee behavior="scroll" direction="left" scrollamount="7">` with live hover pause effect and animated pulse badge |

---

## 📁 Project Structure

```
WP-Lab-5/
├── index.html       # Semantic HTML5 document structure with student comments
├── style.css        # Pure CSS3 styling (typography, layout, animations, responsive design)
├── campus.jpg       # High-resolution college campus background image
└── README.md        # Lab documentation & viva guide
```

---

## 💡 Quick Tips for Lab Evaluation / Viva

1. **Why use semantic HTML5 tags (`<header>`, `<main>`, `<section>`, `<article>`, `<address>`, `<footer>`)?**
   - They improve document structure, search engine optimization (SEO), and web accessibility for screen readers.

2. **How does the background image cover the screen without distortion?**
   - Using `background-size: cover;` combined with `background-position: center;` ensures the image fills the entire viewport while maintaining its aspect ratio.

3. **How is the text readability maintained over a photographic background?**
   - A semi-transparent overlay (`.page-overlay`) and high-contrast card containers with glassmorphism backgrounds (`rgba(255, 255, 255, 0.94)`) ensure clear text contrast.

4. **How do we test responsiveness?**
   - Resize the browser window or open Developer Tools (`F12` or `Ctrl+Shift+I` / `Cmd+Option+I`) and switch to Mobile/Tablet device simulation.

---

## 🚀 How to Run
Simply open **`index.html`** in any web browser.
