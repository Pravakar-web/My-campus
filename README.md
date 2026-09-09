# Jain Global Campus – Web Programming Lab Assignment

A modern and responsive college webpage for **Jain Global Campus, Kanakapura** built using **pure HTML5 and CSS3** without any external libraries or frameworks.

---

## 📋 Features & Assignment Requirements Mapping

| Requirement | Implementation Details | Key Code / CSS Tokens |
| :--- | :--- | :--- |
| **(a) Page Title** | `<title>My College</title>` in `index.html` (Line 7). | Title set to "My College". |
| **(b) Full-Page Background Image** | Campus background image covering the complete page with a semi-transparent overlay. | `background-image: url('campus.jpg');`<br>`background-size: cover;`<br>`background-attachment: fixed;`<br>`.page-overlay` with dark gradient. |
| **(c) Prominent College Header** | **“Jain Global Campus”** in large, bold prominent text with **“Kanakapura, Karnataka”** directly below, center-aligned. | `.college-title`<br>`.college-address` |
| **(d) Courses Offered (Unique Styling)** | Section titled **"Courses Offered"** with distinct color, font style, and typeface for each course: <br>• **BCA**: `'Segoe UI', sans-serif` \| Normal Extra-Bold \| Royal Blue (`#1d4ed8`)<br>• **B.Sc CS**: `'Georgia', serif` \| Italic \| Emerald Green (`#047857`)<br>• **B.Tech**: `'Trebuchet MS', sans-serif` \| Oblique \| Crimson Red (`#b91c1c`)<br>• **BBA**: `'Palatino Linotype', serif` \| Italic \| Amber Gold (`#b45309`)<br>• **B.Com**: `'Courier New', monospace` \| Normal Monospace \| Deep Violet (`#6d28d9`)<br>• **MCA**: `'Verdana', sans-serif` \| Oblique \| Teal (`#0e7490`) | `.course-bca`<br>`.course-bsc`<br>`.course-btech`<br>`.course-bba`<br>`.course-bcom`<br>`.course-mca` |
| **(e) Scrolling Announcements** | HTML marquee scrolling text with upcoming exams, college fest (TARANG 2026), AI workshops, and admissions notifications with live hover pause effect. | `<marquee>` with `.announcement-banner` and `.pulse-icon` |

---

## 📁 Project Structure

```
WP-Lab-5/
├── index.html       # Semantic HTML5 document structure with student comments
├── style.css        # Pure CSS3 stylesheet (typography, layout, animations, responsive design)
├── campus.jpg       # Campus background image
└── README.md        # Lab documentation and requirements mapping
```

---

## 🚀 How to Run
Simply open **`index.html`** in any web browser.
