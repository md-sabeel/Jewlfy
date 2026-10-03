# 💎 Jewlfy - Jewelry & Accessories eCommerce HTML Template

Jewlfy is a modern, responsive, and elegant eCommerce HTML template designed for jewelry, luxury accessories, watches, and premium retail storefronts. Built with clean HTML5 structure, SCSS styling, and jQuery-powered interactions, it offers a polished storefront experience without requiring a framework or build setup.

## ✨ Overview

This project is a static multi-page template with a premium boutique aesthetic. It includes a complete storefront flow covering landing pages, product browsing, cart/checkout pages, blog sections, account pages, and custom utility screens. The codebase is organized for easy customization and fast deployment into any static hosting environment or CMS integration.

## 🛍️ Features

- 6 distinct home page variations
- 40+ prebuilt HTML pages
- Responsive layout for mobile, tablet, and desktop
- Luxury jewelry-focused design system
- Shop, product detail, cart, wishlist, and checkout flows
- Blog grid and article detail pages
- Account pages: login, register, password reset, order tracking
- Working UI interactions using Swiper, Nice Select, LightGallery, Odometer, and jQuery
- SCSS source files for easy color, spacing, and typography editing
- Clean and reusable component-based structure

## 🧱 Tech Stack

- HTML5
- CSS3
- SCSS
- Bootstrap
- jQuery
- Swiper.js
- Remix Icon
- LightGallery
- Nice Select
- Odometer

## 📁 Project Structure

```text
Jewlfy - Template/
├── index.html
├── home-v2.html
├── home-v3.html
├── home-v4.html
├── home-v5.html
├── home-v6.html
├── shop.html
├── shop-v2.html
├── shop-v3.html
├── shop-v4.html
├── shop-v5.html
├── shop-v6.html
├── product-details.html
├── product-details-v2.html
├── product-details-v3.html
├── product-details-v4.html
├── product-details-v5.html
├── product-details-v6.html
├── product-details-v7.html
├── cart.html
├── checkout.html
├── wishlist.html
├── blog.html
├── blog-v2.html
├── blog-v3.html
├── blog-v4.html
├── blog-v5.html
├── blog-details.html
├── about.html
├── contact.html
├── faq.html
├── team.html
├── login.html
├── register.html
├── password-reset.html
├── order-state.html
├── order-tracking.html
├── location.html
├── privacy-policy.html
├── terms-condition.html
├── comming-soon.html
├── error.html
├── categories.html
├── shop-layouts.html
├── assets/
│   ├── css/
│   ├── fonts/
│   ├── img/
│   ├── js/
│   ├── scss/
│   └── video/
├── .gitignore
├── .prettierignore
└── README.md
```

## ⚙️ How to Run

### Option 1: Open directly in browser

Open any HTML file, such as `index.html`, in your browser to preview the template.

### Option 2: Use a local web server

For a smoother development experience, you can run a local static server:

```bash
python -m http.server 8000
```

Then open:

```text
http://localhost:8000
```

You can also use VS Code Live Server or any static hosting tool.

## 🎨 Customization Guide

### Theme colors

The main color palette and design tokens are managed in:

```text
assets/scss/default/_variable.scss
```

Update the variables there to change branding, accent tones, neutral colors, and layout styling.

### Global styles

Core template styling is defined in the SCSS partials inside:

```text
assets/scss/
```

Key files include:

- `default/` for variables, mixins, fonts, and typography
- `common/` for general layout, header, footer, sliders
- `shortcode/` for product cards, hero section, cart, blog, modals, and more

### JavaScript behavior

Interaction logic is managed in:

```text
assets/js/main.js
```

This file handles:

- preloader
- sticky header
- mobile navigation
- slider initialization
- modals and dialogs
- product filtering
- cart and wishlist interactions
- countdown timers
- scroll-to-top behavior

## 🖼️ Media and Assets

The template includes custom and vendor assets stored in:

```text
assets/img/
assets/fonts/
assets/video/
```

Replace the demo images and branding assets with your own store visuals to match your business identity.

## 📦 Notes for Development

- The compiled CSS is generated in `assets/css/style.css`.
- The source styles live in `assets/scss/style.scss` and related SCSS partials.
- If you edit SCSS, recompile it to keep the CSS output updated.

Example Sass compile command:

```bash
sass assets/scss/style.scss assets/css/style.css
```

## 🧾 Licensing and Usage

This project is a commercial HTML template distributed under the terms of its licensing agreement. Use the template according to the purchase license and replace demo content with your own brand assets before publishing a live website.

## 🙌 Credits

- Design and template development: Laralink
- Frontend framework: Bootstrap
- Icon pack: Remix Icon
- Slider: Swiper
- jQuery utilities and interactions: jQuery
- UI form controls: Nice Select
- Lightbox gallery: LightGallery

## ✅ Summary

Jewlfy is a premium storefront template built for jewelry and luxury retail businesses. It combines a strong visual identity, ready-made pages, and extensible frontend logic to help you launch a refined online store quickly and efficiently.

---

If you want, I can also generate a more polished project-specific README with a screenshot section, demo links, and a custom setup guide tailored to your exact business brand.
