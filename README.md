<div align="center">

# Business Website
# ✨🏪✨

### A Responsive Multi-Page Persian Business Website

A clean company website with **Home**, **About**, **Products**, **Services**, and **Contact** pages — built with HTML, CSS, and JavaScript, fully right-to-left, and ready to open in the browser.

<br>

# 👨‍💻 **Sadra Hatami**

### *Developer • Software Engineer • Creator*

<br>

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Responsive](https://img.shields.io/badge/Responsive-Yes-success?style=for-the-badge)
![RTL](https://img.shields.io/badge/Direction-RTL%20Persian-brightgreen?style=for-the-badge)
![Cross Platform](https://img.shields.io/badge/Platform-Desktop%20%7C%20Laptop%20%7C%20Tablet%20%7C%20Mobile-6f42c1?style=for-the-badge)
[![GitHub Pages](https://img.shields.io/badge/GitHub%20Pages-Live-blue?style=for-the-badge&logo=github)](https://sadra-hatami.github.io/Business-Website/)
[![License](https://img.shields.io/badge/License-MIT-green.svg?style=for-the-badge)](LICENSE)
![GitHub](https://img.shields.io/badge/Open_Source-Project-black?style=for-the-badge&logo=github)

<br>

[🌐 Live Demo](https://sadra-hatami.github.io/Business-Website/)
•
[📧 Contact](mailto:sadra.hatami.1732@gmail.com)
•
[🔗 GitHub Profile](https://github.com/sadra-hatami)

</div>

---

# 📑 Table of Contents

- [About](#-about)
- [Why This Website?](#-why-this-website)
- [Key Features](#-key-features)
- [Pages](#-pages)
- [Project Structure](#-project-structure)
- [Design System](#-design-system)
- [Technologies](#️-technologies)
- [Usage](#️-usage)
- [Target Audience](#-target-audience)
- [Live Demo](#-live-demo)
- [Roadmap](#-roadmap)
- [FAQ](#-frequently-asked-questions)
- [Contributing](#-contributing)
- [Contact](#-contact)
- [License](#-license)
- [Copyright](#-copyright)
- [Support](#-support)

---

# 📖 About

**Business Website** is a multi-page Persian company website designed as a complete front-end template for introducing a business, showing products, presenting services, and collecting contact messages.

The project uses semantic HTML pages, a single custom stylesheet, local Persian fonts, Bootstrap Icons, and a small script for the mobile menu. There is no backend and no extra framework. The site runs from static files and can be hosted on GitHub Pages.

The copy on the pages is placeholder business text, so the layout can be reused for a real shop or company by replacing titles, prices, images, and contact details.

> **Tagline:** *A responsive multi-page Persian business website with home, about, products, services, and contact pages, built with HTML, CSS, and JavaScript.*

---

# 🚀 Why This Website?

Many business templates are either single-page landings or heavy frameworks.

This project keeps a clear multi-page structure:

- Separate pages for each main section
- One shared visual language across the site
- RTL layout and Vazir font for Persian readers
- Responsive behavior from mobile sidebar to desktop grid
- Easy to edit without a build step

The goal is a practical company website that looks finished in the browser and stays simple to customize.

---

# ✨ Key Features

- 🏠 Five linked HTML pages
- 📱 Mobile-first sidebar navigation with open / close actions
- 🖼️ Hero banner with entrance animations
- 🧩 Feature cards with Bootstrap Icons
- 🛍️ Product cards with image, title, and price in Toman
- 🛠️ Service cards with overlay icons
- 📬 Contact block with address, email, phone, and a message form
- 🎨 CSS custom properties for colors, radius, and transitions
- 📐 Responsive breakpoints at 576px, 768px, 992px, and 1200px
- 🇮🇷 Full RTL direction and right-aligned Persian text
- 🔤 Local Vazir font files (woff2 / woff / ttf)
- 🌐 Static hosting on GitHub Pages

---

# 📄 Pages

| File | Page | What it includes |
|------|------|------------------|
| [index.html](index.html) | Home | Banner, features, about preview, product preview, services, contact, footer |
| [about.html](about.html) | About | About banner, feature row, image and company text |
| [products.html](products.html) | Products | Feature row and three sample products with prices |
| [services.html](services.html) | Services | Feature row and three service cards |
| [contact-us.html](contact-us.html) | Contact | Feature row, contact details, and a name / email / message form |

Shared on every page:

- Hamburger menu and slide-in navbar
- Links to Home, About, Products, Services, and Contact
- Footer with WhatsApp, Twitter, and Instagram icons

Sample product prices currently shown in the catalog:

- 65,000 تومان
- 59,000 تومان
- 369,000 تومان

---

# 📁 Project Structure

```text
Business-Website/
├── index.html
├── about.html
├── products.html
├── services.html
├── contact-us.html
├── css/
│   ├── main.css
│   └── bootstrap-icons.css
├── js/
│   └── app.js
├── images/
│   ├── header.jpg
│   ├── about-bcg.jpg
│   ├── product-1.jpg
│   ├── product-2.jpg
│   └── product-3.jpg
└── fonts/
    ├── vazir/
    └── bootstrap/
```

- `css/main.css` — layout, colors, components, animations, and media queries
- `css/bootstrap-icons.css` — icon font styles
- `js/app.js` — shows and hides the sidebar by toggling `showNav`
- `images/` — header, about, and product photos
- `fonts/vazir/` — Persian text font
- `fonts/bootstrap/` — icon font files

---

# 🎨 Design System

The stylesheet is organized around reusable tokens in `:root`:

| Token | Role |
|-------|------|
| `--clr-primary` (`#e2711d`) | Main orange |
| `--clr-primary-light` (`#ffb627`) | Light accent |
| `--clr-grey-1` (`#102a42`) | Dark text |
| `--clr-grey-5` (`#617d98`) | Muted text |
| `--clr-grey-10` (`#f1f5f8`) | Light surfaces |
| `--ff-primary` | Vazir |
| `--radius` | Card and button rounding |
| `--transition` | Shared hover motion |

Layout uses a centered `.section-center` container, `clearfix` rows, and section components such as `.feature`, `.product`, `.service-card`, and `.contact-form`.

The mobile menu button uses a bounce animation. The home banner titles slide in from the top and bottom.

---

# 🛠️ Technologies

- HTML5
- CSS3 (custom properties, media queries, keyframes)
- Vanilla JavaScript
- Vazir font
- Bootstrap Icons

No package manager, bundler, or backend is required.

---

# ▶️ Usage

### Open locally

1. Clone the repository:

```bash
git clone https://github.com/sadra-hatami/Business-Website.git
cd Business-Website
```

2. Open `index.html` in a browser.

### Live website

https://sadra-hatami.github.io/Business-Website/

### Customize

Replace the placeholder titles, product names, prices, photos, and contact details. Keep the existing class names if you want the current layout and spacing to stay intact.

---

# 🎓 Target Audience

### Businesses

- Small shops and local companies
- Teams that need a simple multi-page company site

### Developers

- Front-end learners practicing RTL layout
- Anyone who wants a static HTML / CSS starting point

### Educators

- Instructors showing a complete multi-page website structure

---

# 🌍 Live Demo

### Website

https://sadra-hatami.github.io/Business-Website/

### Repository

https://github.com/sadra-hatami/Business-Website

---

# 🚀 Roadmap

Possible later improvements:

- 📝 Real company copy instead of placeholder text
- 🛒 Product detail pages
- 🔍 Simple product filtering
- 🌙 Dark theme
- 📩 Working contact form endpoint
- ♿ Further accessibility polish
- 🖼️ Extra image formats and compression
- 📄 Favicon and Open Graph tags

---

# ❓ Frequently Asked Questions

### Does the website need a server?

No. It is static. You can open the HTML files directly or host them on GitHub Pages.

### Is there a shopping cart or payment system?

No. Product cards are presentational. Prices are shown in the layout, but checkout is not implemented.

### Does the contact form send messages?

The form is styled and ready for fields, but it has no backend. Connect it to a form service or server if you need real delivery.

### Can I change the language direction?

The site is built RTL for Persian. LTR would need direction and alignment changes in `main.css` and the HTML `lang` attribute.

### Which devices are supported?

The layout is written to work on phones, tablets, laptops, and desktops.

---

# 🤝 Contributing

Contributions are welcome.

You can:

- Report layout bugs
- Improve responsive behavior
- Suggest visual refinements
- Replace sample content with better examples
- Submit Pull Requests

---

# 📬 Contact

**Developer:**

### **Sadra Hatami**

📧 [Email](mailto:sadra.hatami.1732@gmail.com)

🌐 [GitHub](https://github.com/sadra-hatami)

---

# 📄 License

This project is licensed under the **MIT License**.

You are free to use, modify, and distribute this project under the terms of the MIT License.

---

# © Copyright

© 2026 **Sadra Hatami**

All rights reserved.

The source code, page structure, visual design, documentation, and project assets are protected under applicable copyright laws.

---

# 🙏 Acknowledgements

Thanks to everyone who supports open-source front-end work.

The first version of this layout was prepared as a course capstone at webprog.io.

---

# ⭐ Support the Project

If you found this website useful, please consider:

⭐ Starring this repository

🐛 Reporting issues

💡 Suggesting improvements

📢 Sharing the project with others

---

<div align="center">

## Designed & developed with ❤️ for the developer community of Iran and the world

</div>
