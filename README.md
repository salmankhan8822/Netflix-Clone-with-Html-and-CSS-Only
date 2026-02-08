# Netflix Clone – Responsive Streaming Homepage

A **highly detailed, professional, and responsive streaming website** that closely mimics the real Netflix homepage (`netflix.com`), built with **only HTML and CSS** (no JavaScript). This is a **static prototype** optimized for all devices (mobile, tablet, desktop, large screens) and uses Netflix’s color scheme and modern UI patterns.

---

## 🎯 Project Overview

This project is a **full‑page Netflix homepage clone** with:

- Sticky top navbar.
- Large hero banner with play button overlay.
- Multiple horizontal rows of movie/TV posters (100+ items).
- Hover effects (play button, My List heart, scale).
- Responsive layout using **CSS Grid** and **Flexbox**.
- Dark mode by default, with red accents (`#E50914`).

It is ideal for:

- Learning responsive layouts.
- Practicing hero banners and dark‑theme UI.
- Building a portfolio project that looks production‑ready.

---

## 🖼️ Screenshots (Conceptual)

- Desktop: Hero banner, multiple rows of 6–8 posters, full‑width footer.
- Tablet: Narrower rows (4–5 posters), stacked sections.
- Mobile: 2–3 posters per row, vertical stacking, centered footer.

*(You can add actual screenshots later in your GitHub repo.)*

---

## 🧩 Features

- **Sticky Top Navbar**:
  - Netflix logo.
  - Search bar with magnifying glass icon.
  - “Kids” toggle button.
  - Genre dropdown (“All”, “Movies”, “TV Shows”, “My List”).
  - Profile avatars and “Sign In” button.
  - “My List” heart, notification bell, profile dropdown.
- **Hero Section**:
  - Full‑bleed background image.
  - Dark overlay gradient.
  - Large play button overlay.
  - Title, subtitle, and two buttons (“Play”, “My List”).
- **Main Content Rows**:
  - 10 sections (e.g., “Trending Now”, “Action Movies”, “Top 10 TV Shows”, “New Releases”, “Because You Watched Stranger Things”, “Sci‑Fi Hits”, “Romantic Comedies”, “Documentaries”, “Kids & Family”, “Because You Watched Inception”).
  - Each row has 10 posters (200×300px).
  - Hover effects:
    - Scale up (1.1).
    - Play button overlay.
    - Title fade‑in.
    - “My List” heart turns red.
  - Horizontal scrolling simulation via `overflow-x: auto`.
- **Promotional Banner**:
  - Full‑width banner for “Watch Stranger Things now”.
- **Footer**:
  - “Questions? Contact us.” text.
  - Multi‑column links (Help Center, Terms of Use, Privacy, etc.).
  - Country selector (“Netflix Pakistan”).
  - Language toggle (English).
  - Social icons (Facebook, Twitter, Instagram) in red.
  - Copyright notice.

---

## 🎨 Design & Styling

- **Colors** (Netflix‑inspired):
  - Background: `#141414`.
  - Secondary: `#221F1F`.
  - Text: `#FFFFFF`.
  - Accent: `#E50914` (red).
- **Typography**:
  - Font family: `Helvetica Neue`, Arial, sans‑serif.
  - Headings: 24px–48px.
  - Body text: 12px–14px.
- **Layout**:
  - Flexbox for navbar and forms.
  - CSS Grid for rows and footer columns.
  - Responsive media queries for:
    - Desktop (`≥1024px`).
    - Tablet (`≥768px`).
    - Mobile (`≤480px`).

---

## 🛠️ Technologies Used

- **HTML5** – Semantic structure (`<header>`, `<nav>`, `<main>`, `<section>`, `<footer>`).
- **CSS3** – Flexbox, Grid, transitions, hover effects, responsive design.
- **Font Awesome 6** – Icons (search, play, heart, bell, social icons).
- **Placeholder images** – via `placehold.co` (movie/TV posters).

---

## 📁 Project Structure

```text
netflix-clone/
├── index.html
├── style.css
└── README.md
