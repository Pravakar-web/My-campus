# Jain Global Campus – Kanakapura Webpage

A modern, attractive, and responsive college webpage for **Jain Global Campus, Kanakapura (Karnataka)** built using **pure HTML5 and CSS3** without any external libraries or frameworks.

---

## 📋 Features & Requirements Mapping

| Requirement | Description | Implementation File | Key Code Snippet / Style |
| :--- | :--- | :--- | :--- |
| **1. Page Title** | Set page title to **"Jain Global Campus – Kanakapura"** | `index.html` (Line 7) | `<title>Jain Global Campus – Kanakapura</title>` |
| **2. Background Image & Overlay** | Sprawling Jain Global Campus background covering full screen with readability overlay | `style.css` (Section 2) | `background-image: url('campus.jpg');`<br>`background-size: cover;`<br>`background-attachment: fixed;`<br>`.page-overlay` with dark gradient & backdrop filter |
| **3. Prominent Campus Header** | Bold **"Jain Global Campus"** header + **"Kanakapura, Karnataka"** address below, center-aligned | `index.html` & `style.css` | `.college-title` (2.75rem bold uppercase)<br>`.college-tagline` & `.college-address` (centered location text) |
| **4. Courses Offered (Unique Styling)** | Distinct text color, font style, and typeface for each course | `style.css` (Section 6) | • **B.Tech (CSE - AI & ML)**: `'Segoe UI'`, Normal Bold, Royal Blue (`#1d4ed8`)<br>• **B.Tech Aerospace**: `'Georgia'`, Italic, Emerald Green (`#047857`)<br>• **BCA**: `'Trebuchet MS'`, Oblique, Crimson Red (`#b91c1c`)<br>• **B.Tech ECE**: `'Palatino Linotype'`, Italic, Amber Gold (`#b45309`)<br>• **B.Des**: `'Courier New'`, Monospace Normal, Deep Violet (`#6d28d9`)<br>• **MCA**: `'Verdana'`, Oblique, Teal (`#0e7490`) |
| **5. Scrolling Announcements** | HTML marquee scrolling text with exams, admissions, college events, workshops, and academic notices | `index.html` & `style.css` (Section 4) | `<marquee behavior="scroll" direction="left" scrollamount="7">` with hover pause effect and animated pulse badge |

---

## 📁 Project Structure

```
WP-Lab-5/
├── index.html       # Semantic HTML5 document structure with student comments
├── style.css        # Pure CSS3 styling (typography, layout, animations, responsive design)
├── campus.jpg       # Jain Global Campus, Kanakapura background image
└── README.md        # Project documentation & viva guide
```

---

## 🚀 How to Run
Simply open **`index.html`** in any web browser (Chrome, Edge, Firefox, Safari).
