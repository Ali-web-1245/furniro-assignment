# Furniro - E-Commerce Blog Page

A responsive, pixel-perfect recreate of the **Furniro E-Commerce Blog Page** based on the official Figma design. Built using clean, semantic **HTML5**, modern **CSS3**, and lightweight **Vanilla JavaScript**.

---

## 📌 Project Overview

This project is a clean and exact implementation of the Furniro Blog Page template. It features a main blog feed with detailed post previews, a dynamic sidebar (with live title search, category counts, and recent post thumbnails), pagination controls, a value proposition features bar, and a global header and footer consistent with the entire Furniro website ecosystem.

---

## 🛠️ Tech Stack

- **HTML5**: Semantic markup (`<header>`, `<nav>`, `<main>`, `<article>`, `<aside>`, `<footer>`) for accessibility and structure.
- **CSS3**: Flexbox, Grid layout, CSS custom variables, and media queries for full responsiveness across all screen sizes.
- **Vanilla JavaScript**: Lightweight DOM manipulation for interactive features (search filter, mobile navigation, pagination toggle, and form validation).
- **FontAwesome**: Iconography for header navigation, post metadata, and feature highlights.

---

## ✨ Features & Functionality

### 1. Navigation Header
- **Desktop Layout**: Furniro logo mark, navigation links (`Home`, `Shop`, `About`, `Contact`), and utility icons.
- **Mobile Drawer**: Responsive hamburger menu with `aria` accessibility attributes (`aria-expanded`, `aria-hidden`), close-on-click, click-outside, and `Escape` key controls.
- **About Link Routing**: Points directly to `index.html#about`.

### 2. Hero Banner
- Clean banner structure using HTML `<img>` rendering with centered overlay showing Furniro branding and page breadcrumbs (`Home > Blog`).

### 3. Blog Main Feed
- Display of main blog posts with metadata (author, date, tag), image container, title, excerpt, and "Read more" links.
- Consistent image ratios using `object-fit: cover`.

### 4. Interactive Sidebar
- **Live Search**: Instant JavaScript filtering that filters blog post cards by title in real-time. Displays a *"No posts found"* message when no titles match the query.
- **Categories Widget**: Itemized topic list with post counter badges.
- **Recent Posts Widget**: Compact thumbnail listings using standard HTML `<img>` elements.

### 5. Pagination & Features
- Interactive pagination state toggles.
- Standard Furniro beige value-proposition bar (`High Quality`, `Warranty Protection`, `Free Shipping`, `24 / 7 Support`).

### 6. Global Footer & Newsletter Validation
- Multi-column footer layout matching Furniro design standards.
- Basic client-side JavaScript regex email validation with dynamic success/error feedback.

---

## 📂 Project Structure

```text
furniro-blog/
│
├── images/
│   ├── logo.png
│   ├── blog-banner.jpg
│   ├── blog-1.jpg
│   ├── blog-2.jpg
│   └── blog-3.jpg
│
├── blog.html      # Main HTML file for the Blog page
├── style.css      # Custom styling & responsive media queries
├── script.js     # Vanilla JavaScript functionality
└── README.md      # Project documentation
