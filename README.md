# Jain Global Campus, Kanakapura – Web Programming Practical Project

A simple, clean, and modern single-page practical assignment website for **Jain Global Campus, Kanakapura** created using **pure HTML5 and CSS3** (without any external libraries or frameworks).

---

## 📋 Structure & Assignment Requirements Mapping

| Requirement | Implementation Details | Key Code / CSS Tokens |
| :--- | :--- | :--- |
| **1. Page Title** | `<title>My College \| Jain Global Campus, Kanakapura</title>` in `index.html` (Line 7). | Title related to "My College" & "Jain Global Campus". |
| **2. Full-Screen Background Image** | High-resolution campus image (`campus.jpg`) covering the full screen with a subtle dark transparent overlay (`.background-overlay`). | `background-size: cover;`<br>`background-position: center;`<br>`background-attachment: fixed;` |
| **3. Prominent Header** | **“JAIN GLOBAL CAMPUS”** in large bold text (`font-size: 2.75rem; font-weight: 900`) and **“Kanakapura, Karnataka”** in a clean accent font directly below. | `.college-name`<br>`.college-location` |
| **4. Central Glassmorphism Card** | Single, centered, modern card with a slightly transparent white background, subtle blur, rounded corners, and soft shadow. | `.glass-card`<br>`background: rgba(255, 255, 255, 0.95);`<br>`backdrop-filter: blur(14px);` |
| **5. Courses Offered (Distinct Typography)** | 6 course names, each styled with a **different font color, font style, and typeface**: <br>• **BCA**: `'Segoe UI', sans-serif` \| Normal Heavy Bold \| Royal Blue (`#1d4ed8`)<br>• **B.Com**: `'Courier New', monospace` \| Normal Monospace \| Deep Violet (`#7c3aed`)<br>• **BBA**: `'Palatino Linotype', serif` \| Italic \| Warm Amber (`#b45309`)<br>• **B.Sc CS**: `'Georgia', serif` \| Italic \| Emerald Green (`#047857`)<br>• **B.Tech**: `'Trebuchet MS', sans-serif` \| Oblique \| Crimson Red (`#dc2626`)<br>• **MBA**: `'Verdana', sans-serif` \| Oblique \| Deep Teal (`#0891b2`) | `.course-bca`<br>`.course-bcom`<br>`.course-bba`<br>`.course-bsc`<br>`.course-btech`<br>`.course-mba` |
| **6. Announcements Ticker** | Scrolling text with “Upcoming Semester Examinations • Annual College Events • Workshops & Seminars • Important Academic Announcements • Admissions Open” in a clean modern ticker bar with hover pause. | `<marquee>` with `.ticker-box`<br>and `.pulse-dot` indicator |
| **7. Minimal Footer** | Clean and subtle copyright text at the bottom: `“© 2026 Jain Global Campus, Kanakapura”`. | `.college-footer` |

---

## 📁 Files in Repository

```
WP-Lab-5/
├── index.html       # Clean HTML5 single-page document with student comments
├── style.css        # Pure CSS3 stylesheet (typography, glassmorphism, alignment)
├── campus.jpg       # Full-screen campus background image
└── README.md        # Project documentation and assignment mapping
```

---

## 🚀 How to Run
Simply open **`index.html`** in any web browser.
