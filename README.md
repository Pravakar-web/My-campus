# Jain Global Campus – Kanakapura Landing Page

A premium, modern, and responsive college landing page for **Jain Global Campus, Kanakapura (Karnataka)**, crafted using **pure HTML5 and CSS3** without any external libraries or CSS frameworks.

---

## 🎨 UI/UX Design System & Features

- **Header & Sticky Navigation Bar**: Academic branding, desktop navigation links, and a highlighted "Apply Now" CTA button with backdrop blur.
- **Full-Screen Modern Hero Section**:
  - Full-page background image (`campus.jpg`) covering the viewport with a dark transparent gradient overlay.
  - Welcome badge: `WELCOME TO JAIN GLOBAL CAMPUS`.
  - Prominent heading: **“Jain Global Campus”** (`font-size: 3.8rem; font-weight: 900`).
  - Location below: **“Kanakapura, Karnataka”** in warm amber gold.
  - Tagline: *“Empowering students through education, innovation and excellence.”*
  - Interactive CTA buttons: `Explore Courses` & `Discover More`.
  - Floating Quick Glance Statistics Strip (300+ Acres, NAAC A++, 200+ Recruiters, 95% Placements).
- **Important Announcements (News Ticker)**:
  - High-visibility banner with a live animated pulse indicator.
  - Smooth HTML `<marquee>` with hover-to-pause functionality covering exam dates, JET admissions, TARANG fest, AI workshops, and project deadlines.
- **About the Campus Section**:
  - Two-column modern layout with academic narrative, feature checklists, and a glassmorphism infrastructure stats card.
- **Courses Offered Section**:
  - 6 modern academic cards with duration tags, eligibility criteria, career paths, and distinct typography requirements.
- **Campus Highlights Section**:
  - 4 interactive feature cards (Modern Learning Environment, Sports & Recreation, Technology & Innovation, Student Activities).
- **Campus Tour & Contact Section**:
  - High-contrast contact grid with official Kanakapura address, admissions email, and helpline numbers.
- **Modern Academic Footer**:
  - Campus branding, quick links, academic streams, office hours, and copyright notice.

---

## 📋 Features & Requirements Mapping

| Requirement | Description | Implementation File | Key Code Snippet / Style |
| :--- | :--- | :--- | :--- |
| **1. Page Title** | Set page title to **"My College \| Jain Global Campus – Kanakapura"** | `index.html` (Line 7) | `<title>My College \| Jain Global Campus – Kanakapura</title>` |
| **2. Background Image & Overlay** | Full-screen campus image with dark transparent gradient overlay | `style.css` (Section 3) | `background-image: url('campus.jpg');`<br>`background-size: cover;`<br>`background-attachment: fixed;`<br>`.hero-overlay` with gradient & blur |
| **3. Prominent Campus Header** | Bold **"Jain Global Campus"** header + **"Kanakapura, Karnataka"** below | `index.html` & `style.css` | `.hero-title` (3.8rem bold uppercase)<br>`.hero-location` (1.45rem amber text) |
| **4. Distinct Course Typography** | Distinct text color, font style, and typeface for each course | `style.css` (Section 6) | • **B.Tech (CSE - AI & ML)**: `'Segoe UI'`, Normal Bold, Royal Blue (`#1d4ed8`)<br>• **B.Tech Aerospace**: `'Georgia'`, Italic, Emerald Green (`#047857`)<br>• **BCA**: `'Trebuchet MS'`, Oblique, Crimson Red (`#b91c1c`)<br>• **B.Sc CS**: `'Palatino Linotype'`, Italic, Amber Gold (`#b45309`)<br>• **BBA**: `'Courier New'`, Monospace Normal, Deep Violet (`#6d28d9`)<br>• **B.Com**: `'Verdana'`, Oblique, Teal (`#0e7490`) |
| **5. Scrolling Announcements** | HTML marquee scrolling text with upcoming exams, events, workshops, admissions | `index.html` & `style.css` (Section 4) | `<marquee behavior="scroll" direction="left" scrollamount="7">` with live hover pause and animated pulse badge |

---

## 📁 Project Structure

```
WP-Lab-5/
├── index.html       # Semantic HTML5 document structure with modern sections & comments
├── style.css        # Vanilla CSS3 stylesheet (Design tokens, layout, hover effects, responsiveness)
├── campus.jpg       # High-resolution Jain Global Campus background image
└── README.md        # Documentation and requirements mapping
```

---

## 🚀 How to Run
Open **`index.html`** directly in any web browser.
