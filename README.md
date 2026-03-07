# 🪡 Libaas Studio — Luxury Fashion E-Commerce



![Libaas Studio Banner](screenshots/banner.png)

**A premium Pakistani ladies fashion e-commerce website built with pure HTML, Tailwind CSS & Vanilla JavaScript.**

[![Live Demo](https://img.shields.io/badge/🌐_Live_Demo-Visit_Site-c9a96e?style=for-the-badge)](https://yourusername.github.io/your-repo-name/)
[![License: MIT](https://img.shields.io/badge/License-MIT-black?style=for-the-badge)](LICENSE)
[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![TailwindCSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)](https://tailwindcss.com/)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)



---

## 📸 Project Screenshots

> _Add your screenshots to a `/screenshots` folder and update the paths below._

| Homepage | Product Catalog |
|----------|----------------|
| ![Homepage](screenshots/homepage.png) | ![Products](screenshots/products.png) |

| Product Detail | Checkout / Order |
|---------------|-----------------|
| ![Detail](screenshots/product-detail.png) | ![Order](screenshots/order.png) |

| About Page | Contact Page |
|------------|-------------|
| ![About](screenshots/about.png) | ![Contact](screenshots/contact.png) |

---

## ✨ Features

- **Dark Luxury Theme** — Premium black & gold design language throughout every page
- **Fully Responsive** — Optimised for desktop, tablet, and mobile screens
- **Product Catalog** — 27+ products across Casual, Formal, Party Wear & Bridal categories
- **Dynamic Filtering** — Filter products by category with no page reload
- **Product Detail Pages** — URL-based routing (`?id=lawn1`) with dynamic content rendering
- **Shopping Cart** — Persistent cart using `localStorage` shared across all pages
- **WhatsApp Checkout** — One-click order confirmation via WhatsApp with full order summary
- **Sticky Cart & Header** — Smooth header scroll behaviour with cart item badge
- **Accordion UI** — Animated accordion sections on Returns and FAQ pages
- **Contact Form** — Validated form that forwards enquiries directly to WhatsApp
- **Brand Story / About Page** — Scroll-reveal animations, founder's message, stats strip
- **Returns Policy Page** — Structured 5-section accordion policy with visual process timeline
- **Auth Modal** — Login / Sign Up modal with smooth transitions
- **Search Overlay** — Full-width animated search bar
- **Mobile Hamburger Menu** — Full-screen animated mobile navigation
- **Announcement Ticker** — Scrolling promotional banner
- **Scroll Reveal Animations** — IntersectionObserver-powered reveal on all pages
- **PKR Pricing** — All prices displayed in Pakistani Rupees

---

## 🗂️ Pages

| File | Description |
|------|-------------|
| `index.html` | Homepage — hero banner, collections, product grid, testimonials |
| `products.html` | Full product catalog with sticky filter bar (27 products) |
| `product-detail.html` | Dynamic product detail — URL-param driven (`?id=...`) |
| `order.html` | Cart review & WhatsApp checkout page |
| `about.html` | Brand story, philosophy, founder's message, stats |
| `contact.html` | Contact form, WhatsApp card, social links, FAQ |
| `return.html` | Returns & Exchange Policy with accordion sections |

---

## 🛠️ Tech Stack

| Technology | Usage |
|-----------|-------|
| **HTML5** | Semantic page structure |
| **Tailwind CSS** (CDN) | Utility-first styling |
| **Custom CSS** | CSS Variables, animations, accordion logic |
| **Vanilla JavaScript** | Cart, modals, routing, WhatsApp integration |
| **localStorage** | Persistent cart state across pages |
| **Google Fonts** | Playfair Display, Montserrat, Great Vibes |
| **Font Awesome 6** | Icon library |

---

## 📁 Project Structure

```
libaas-studio/
│
├── index.html              # Homepage
├── products.html           # Product catalog
├── product-detail.html     # Product detail (dynamic)
├── order.html              # Cart & checkout
├── about.html              # Brand story
├── contact.html            # Contact & FAQ
├── return.html             # Returns policy
├── README.md               # This file
│
└── image/                  # All product & UI images
    ├── banner-d.jpg         # Desktop hero banner
    ├── banner-r.jpg         # Mobile hero banner
    ├── favicon.jpg
    ├── newarrival1-5.jpg    # Collection grid images
    ├── lawn1-9.jpg          # Casual/Lawn product images
    ├── formal1-6.jpg        # Formal product images
    ├── party1-6.jpg         # Party wear product images
    └── bridal1-6.jpg        # Bridal product images
```

---

## 🚀 Getting Started

No build tools or dependencies required — this is a pure static site.

### 1. Clone the repository

```bash
git clone https://github.com/CodeWithAliyan/libaas-studio.git
```

### 2. Navigate into the project folder

```bash
cd your-repo-name
```

### 3. Add your images

Place all product images inside the `/image` folder following the naming convention in the structure above.

### 4. Open in browser

Simply open `index.html` in any modern browser:

```bash
# macOS
open index.html

# Windows
start index.html

# Or use VS Code's Live Server extension for best results
```

---

## ⚙️ Configuration

Before going live, update these values across all HTML files:

| What to change | Where to find it | Example |
|----------------|-----------------|---------|
| WhatsApp number | `const WA_NUMBER = '923700256087'` | Replace with your number |
| Business email | `connect.aliyansaleem@gmail.com` | Your actual email |
| Store address | Address block in `contact.html` | Your real address |
| Social media links | Footer & contact page `href` values | Your profile URLs |
| Product prices | Product data arrays in each HTML file | Your actual pricing |

---

## 🌐 Deployment (GitHub Pages)

1. Push this repository to GitHub
2. Go to **Settings → Pages**
3. Set source to **main branch / root**
4. Your site will be live at:

```
https://yourusername.github.io/libaas-studio/
```

---

## 🎨 Design System

```css
--dark:        #111111   /* Page background      */
--dark-card:   #181818   /* Card backgrounds     */
--dark-border: #222222   /* Borders & dividers   */
--gold:        #c9a96e   /* Primary accent       */
--gold-light:  #e1c99a   /* Hover/lighter gold   */
--off-white:   #f5f0eb   /* Body text            */
--text-muted:  #888888   /* Secondary text       */
```

**Fonts:** Playfair Display (headings) · Montserrat (body) · Great Vibes (script accents)

---

## 📄 License

This project is licensed under the **MIT License** — see the [LICENSE](LICENSE) file for details.

```
MIT License

Copyright (c) 2024 Libaas Studio

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.
```

---

## 🤝 Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

---

<div align="center">

Made with ❤️ for Libaas Studio — Lahore, Pakistan

⭐ Star this repo if you found it helpful!

</div>